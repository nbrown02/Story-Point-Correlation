# Story Point Correlation
Most teams believe Story Points are something you MUST do as part of any Agile framework. This is a Power BI template to challenge this notion, allowing you the ability to connect to your Azure DevOps data and see the correlation (or not!) of story points.

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download the .pbit file based on your process template (inherited processes also work)
* Then you're good to get started!

### Connectivity
* Open the .pbit file
* Add your Organization and Project Name - this will be in your Azure DevOps URL https://dev.azure.com/{OrganizationName}/{ProjectName}/ 
* Choose either Effort or StoryPoints depending on your process template (Hint: Scrum template = Effort. Agile template = StoryPoints).
* Hit load (note: you may get prompted for a login here, choose organisational account and enter your Azure DevOps email)
* Voila - your report is created!

### Screenshots
![alt text](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshot.png?raw=true)

Example of looking at multiple teams data and story point correlation with the best result seen (note: not comparing teams to each other!)

![Euq4843XYAQ3ZuZ](https://user-images.githubusercontent.com/29369962/109392664-54dd5e80-7915-11eb-9ac0-6f447c1d99f3.jpeg)
