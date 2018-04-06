---
Order: 1
Area: staticsite
TOCTitle: Getting started
PageTitle: Website Deployment with Azure Storage
MetaDescription: Website Deployment to Azure Storage with Visual Studio Code
DateApproved:
---
# Deploy a Static Site to Azure

This tutorial walks you through deploying a static website, such as an Angular or React [SPA](https://en.wikipedia.org/wiki/Single-page_application) or simple HTML/CSS/JS site, to Azure using [Azure Storage](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureappservice).

> Note! If you have your own server code, such as a Node.js/Express server, see the [App Service tutorial](../app-service-extension/getting-started.md) instead.
If you're unsure what type of app you building, see our description of [common app types](//TODO).

## Game Plan
Because you are building a static website, your production website should just be a collection of HTML, CSS, JavaScript and other static files (images, fonts, etc).
You can host and serve these files using either App Service or Azure Storage, but we will use Azure Storage because it's a little simpler and a lot cheaper.

In this tutorial we will deploy your static site to Azure Storage by doing the following:
1. Get the required accounts and dependencies
2. Create or prepare app for deployment
3. Choose your preferred deployment method
4. Deploy!

## Prerequisites

**Azure Account** - If you don't have an Azure account, [sign up today](https://azure.microsoft.com/en-us/free/?utm_source=campaign&utm_campaign=vscode-tutorial-static-website&mktingSource=vscode-tutorial-static-website) for a free 30-day account with $200 in Azure credits to try out any combination of services.

**Node.js** - Download [Node.js and npm](https://nodejs.org/en/download), we recommend the LTS (long term support) version.

> Note! - If you already have some code, you don't actually need Node.js. We just use it to generate a sample project later.

## Prerequisite check

Before we continue, ensure that you have all the prerequisites installed and configured.

- Login to [Azure Portal](https://portal.azure.com) to make sure you Azure Account is working.
- From a terminal, execute:
```bash
$ node -v
v8.7.0

$ npm -v
5.4.2
```
to ensure that both Node and npm are installed.

----

<a class="tutorial-next-btn" href="/tutorials/static-website/create-app">I've installed the Azure Extension</a>
<a class="tutorial-feedback-btn" onclick="reportIssue('node-deployment-staticwebsite', 'getting-started')" href="javascript:void(0)">I ran into an issue</a>