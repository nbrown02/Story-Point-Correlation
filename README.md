# Story Point Correlation
Most teams believe Story Points are something you MUST do as part of any Agile framework. This is a Power BI template to challenge this notion, allowing you the ability to connect to your Azure DevOps data and see the correlation (or not!) of story points.

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download the appropriate template file:
  - [Scrum process template (including inherited)](https://github.com/nbrown02/Story-Point-Correlation/raw/main/StoryPointsCorrelation%20-%20Scrum.pbit) 
  - [Agile process template (including inherited)](https://github.com/nbrown02/Story-Point-Correlation/raw/main/StoryPointsCorrelation%20-%20Agile.pbit) 
* Then you're good to get started!

### Connectivity
* Open the .pbit file
* Select http/https (only choose http if your Azure DevOps Server is HTTP)
* Add the Analytics / Azure DevOps Server URL - for Azure DevOps services enter 'analytics.dev.azure.com' / for Azure DevOps Server enter your server details
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

### Screenshots
![alt text](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshot.png?raw=true)

Example of looking at multiple teams data and story point correlation with the best result seen (note: not comparing teams to each other!)

![Euq4843XYAQ3ZuZ](https://user-images.githubusercontent.com/29369962/109392664-54dd5e80-7915-11eb-9ac0-6f447c1d99f3.jpeg)
