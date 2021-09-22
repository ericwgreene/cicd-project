# Overview

The goal of the project is to demonstrate the principles of project manager, continuous development, continuous delivery and continuous deployment using modern development tools. To implement project management, Google Sheets and Trello are used. To implement CI/CD and Continuous Deployment, GitHub, Azure Pipelines, and Azure were used.

## Project Plan

Below are links to the Trello Board and Google Sheets Plan for the project.

* A link to a Trello board for the project

[Trello Board](https://trello.com/invite/b/etbnUf31/b86a08131718cbb6a897d8c9e64812fb/udacity-cicd-project)


* A link to a spreadsheet that includes the original and final project plan>

[Google Sheet](https://docs.google.com/spreadsheets/d/1J4IJ6MtrwWjDxFMhZ4iPvKVqBqMQsCUKJnpsnHzpDKc/edit?usp=sharing)

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

![Azure App Service](images/azure-app-service.png "Azure App Service")


* Project cloned into Azure Cloud Shell

![Cloned to Azure Cloud Shell](images/clone-to-azure-cloud-shell.png "Cloned to Azure Cloud Shell")

* Passing tests that are displayed after running the `make all` command from the `Makefile`

![Make All Cloud Shell](images/make-all-azure-cloud-shell.png "Make All Cloud Shell")


* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

![Azure Pipeline Successful Build](images/azure-pipeline-successful-build.png "Azure Pipeline Successful Build")

* Running Azure App Service from Azure Pipelines automatic deployment

![Azure Pipeline Deployment](images/azure-pipeline-deployment.png "Azure Pipeline Deployment")

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

![Azure Pipeline Deployment](images/predictor-app-cloud-shell.png "Azure Pipeline Deployment")

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

![Live Stream Logs](images/live-stream-log.png "Live Stream Logs")



## Enhancements

The project could be enhanced to consolidate the CI/CD process to just GitHub Actions or Azure Pipelies. The project code demonstrated running unit tests with GitHub Actions and doing the deployment with Azure Pipelines. Azure Pipelines and GitHub Actions solve the same problem. Either technology could be used to implement both the testing and the deployment.

The project could be enhanced to deploy a Docker Image to a Kubernetes cluster instead of a single App Service. Such an improvement would improve the scalability and resiliency of the application.

Finally, GitHub, Trello and the Google Sheet could be replaced with Azure DevOps. Generally, I prefer Azure Boards to Trello. I could use the hierarchical nature of Azure Boards to create Epics to manage much of the information in the spreadsheet. And finally, Azure Repos could be used in place of GitHub. This could enable tighter integration between the task management system and commits.

## Demo 

<TODO: Add link Screencast on YouTube>


