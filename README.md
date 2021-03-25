# Cloud Adoption Framework Project Template for non-ADO customers

This repository is a collection of CSVs and Microsoft Project files which mimic the adoption templates we have created for the Cloud Adoption Framework and housed in the [Azure DevOps generator](https://azuredevopsdemogenerator.azurewebsites.net/). 

The templates we have in the Azure DevOps Generator are simple ways to create projects in Azure DevOps. For non-ADO customers these projects can still be used by importing the CSV or Project file into the work item management tool of your choice for eg: [Jira](https://www.atlassian.com/software/jira) or [SmartSheet](https://www.smartsheet.com).

Each CSV has the following fields:
- ID
- Parent
- Work Item Type
- Priority
- Value Area
- Title
- Tags
- Description

NOTE: the description field provides detail on the work item. These details are further supported with content on the https://docs.microsoft.com platform.

Microsoft project: you can use Microsoft Project to connect to your Azure DevOps boards.
- https://docs.microsoft.com/en-us/azure/devops/boards/backlogs/office/create-your-backlog-tasks-using-project?view=tfs-2018&viewFallbackFrom=azure-devops&tabs=office-365 
- https://docs.microsoft.com/en-us/azure/devops/boards/backlogs/office/track-work?view=tfs-2018&tabs=open-excel 


Should you need additional fields in the CSV, you can [create a new Azure DevOps organization](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/create-organization?view=azure-devops), deploy the template and use Excel to create the CSV:

- How to use [Excel to connect to Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/boards/backlogs/office/bulk-add-modify-work-items-excel?view=azure-devops&tabs=agile-process)

- How to connect [Microsoft Project to Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/boards/backlogs/office/create-your-backlog-tasks-using-project?view=tfs-2018&tabs=office-365)

