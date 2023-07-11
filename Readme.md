## Trello Enterprise Member & Workspace Report

This is an open source script that generates a report of your Enterprise Members and Enterprise workspaces. 

---
### User Paramaters 
There are 3 variables that the user must input for the script to work:
- **API Token** - This is the API token used to authenticate that the script has permission to run the needed operations against the chosen Enterprise. The API token must be tied to a user of the Enterprise with Enterprise Admin Permissions. See the [Trello API documentation](https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/)
 for more details. 
- **API Key** - This is the API Key used to authenticate that the script has permission to run the needed operations against the chosen Enterprise. The API token must be tied to a user of the Enterprise with Enterprise Admin Permissions. See the [Trello API documentation](https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/)
- **Enterprise ID** - This is the ID of the Enterprise that the user would like to run the script against. See the [Trello API documentation](https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/)
 
In addition there is 1 other customizations that the user can manage if they would like: 
- **batchCount** - This variable allows you to define how many members you want to full from the API at once. The default is set to 100. 

---
## Other Notes
- The Members report only include Enterprise Members. Deactivated users and Free Managed users are not included. 
- The Workspace report only inlclude Enterprise Workspaces. It does not include Pending or Non-Enterprise Workspaces. 
- An NaN value in the  Day Since Last Active or Last Active means that the user has never logged in and thus has not last active date. 

---
## Have Questions?
Post on the Atlassian Community [here](https://community.atlassian.com/t5/Trello/ct-p/trello) and tag @Alexandros Mathopoulos.

