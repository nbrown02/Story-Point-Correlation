# Story Point Correlation
Most teams believe Story Points are something you MUST do as part of any Agile framework. This is a Power BI template to challenge this notion, allowing you the ability to connect to your Jira, Azure DevOps, Azure DevOps Server and/or TFS data and see the correlation (or not!) of story points.

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* For the Jira version:
  - [Follow these steps](https://support.atlassian.com/atlassian-account/docs/manage-api-tokens-for-your-atlassian-account/) to setup a Jira API token and note it down (e.g. copy/paste into Notepad)
  - You will need to know the 'customfield_xxxxx' value for story points, you can get this by going to https://your-jira-instance.atlassian.net/rest/api/3/field (replace your-jira-instance with what it actually is) and then identifying the field that represents Story Points. Look for the field with a name similar to "Story Points" or "Story Point," and note its ID. It will be something like 'customfield_10000' 
* Download the appropriate template file:
  - [ADO - Scrum process template (including inherited)](https://github.com/nbrown02/Story-Point-Correlation/raw/main/StoryPointsCorrelation%20-%20Scrum.pbit) 
  - [ADO - Agile process template (including inherited)](https://github.com/nbrown02/Story-Point-Correlation/raw/main/StoryPointsCorrelation%20-%20Agile.pbit)
  - [Jira](www.google.com)
* Then you're good to get started!

### Connectivity for Azure DevOps
* Open the .pbit file
* Select http/https (only choose http if your Azure DevOps Server is HTTP)
* Add the Analytics / Azure DevOps Server URL - for Azure DevOps services enter 'analytics.dev.azure.com' / for Azure DevOps Server enter your server details
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* It should then look something like this:

Azure DevOps Services:
![alt text](https://raw.githubusercontent.com/nbrown02/Story-Point-Correlation/main/Screenshots/AzDO%20Login.png)


Azure DevOps Server:
![alt text](https://raw.githubusercontent.com/nbrown02/Story-Point-Correlation/main/Screenshots/AzDO%20Server%20Login.png)

* Hit 'Load' 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!

### Connectivity for Jira
* Open the .pbit file in Power BI Desktop
* Add your Jira URL 
* Add your Jira Project Key(s) - don't confuse the project name with the project key, a common mistake! Your project key will be in the URL when viewing an item.
* Add your field value for story points

* It should then look something like this:
  
![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Login1.PNG)

* For multiple projects, it should look like:
  
![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Multiple.jpg)

* Hit 'Load' 
* You will be prompted for a login, choose Basic and enter:
  - Your email associated with your Jira account for your username
  - Your API token you created in the Prerequisities

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Login2.png)

* Then hit 'Connect' and wait for the data and charts to load!

### Screenshots
![alt text](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshots/Screenshot.png?raw=true)

![alt text](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshots/Screenshot2.gif?raw=true)

![alt text](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshots/StPC.gif?raw=true)

Example of looking at multiple teams data and story point correlation with the best result seen (note: not comparing teams to each other!)

![Euq4843XYAQ3ZuZ](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshots/Screenshot2.png?raw=true)
