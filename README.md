![Build and Deploy](https://github.com/timheuer/aspnet-core-sample-deploy/workflows/Build%20and%20Deploy/badge.svg?branch=master)

# ASP.NET Core Deployment with Actions Sample
This is a sample repo that uses the basic ASP.NET Core web app template and GitHub Actions to build and deploy the web app to Azure App Service.

This repo is really meant only to be an example of the Actions and not the ASP.NET Core content.

## What does the workflow do?
The [workflow](.github/workflows/build-and-deploy.yml) does a few things...

Build:
- Uses .NET Core SDK 
- Restores any NuGet packages
- Builds the project
- Executes any tests
- Publishes the project for deployment

Deploy:
- Deploys the published layout to Azure App Service

Artifacts:
- Uploads the published layout as an artifact of the build


## Where can I get more information?
Some resources:

- My blog :-) [timheuer.com](https://timheuer.com/blog) or [@timheuer](https://twitter.com/timheuer)
- [Get a Free Account for Azure](https://azure.microsoft.com/free/?WT.mc_id=timheuer-github-timheuer)
- [Azure Actions](https://github.com/azure/actions)
