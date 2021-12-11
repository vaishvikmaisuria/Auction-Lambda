# Auction-Lambda
Item Auction using reliable and scalable back-end applications effortlessly using Serverless Framework

## 📝 Table of Contents
- [Auction-Lambda](#auction-lambda)
  - [📝 Table of Contents](#-table-of-contents)
  - [🏁 Getting Started <a name = "getting_started"></a>](#-getting-started-)
  - [Folder Structure <a name = "folder_structure"></a>](#folder-structure-)
  - [Prerequisites <a name = "prerequisites"></a>](#prerequisites-)
  - [🎈 Usage <a name="usage"></a>](#-usage-)
    - [Install dependencies](#install-dependencies)
    - [Deploy serverless app](#deploy-serverless-app)
  - [⚡ UI <a name="ui"></a>](#-ui-)
    - [Images coming soon](#images-coming-soon)
    - [Starting dashboard](#starting-dashboard)
    - [Main page to add items](#main-page-to-add-items)
    - [NavBar](#navbar)
  - [Current Issues <a name = "issues"></a>](#current-issues-)
  - [Authors <a name = "authors"></a>](#authors-)


## 🏁 Getting Started <a name = "getting_started"></a>
This Application uses Serverless Architecture to build a back-end application that can scale effortlessly and serve users reliably. 

Serverless Framework intelligently helps you manage your infrastructure as code (IaC), which eliminates the chance of paying for services that are not in use. Therefore,  you only pay for what you use.

Serverless framework is a alternative to Terraform, when creating basic lambda api, It is easier to use. 

## Folder Structure <a name = "folder_structure"></a>
- src/
    - handlers/
      - hello.js
- /
  - serverless.yml
  - package.json
  - .gitignore

## Prerequisites <a name = "prerequisites"></a>
What things you need to install and run the application
- Node.js and npm -> `https://nodejs.org/en/` -> node --version
- AWS CLI -> `https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html`
- ServerLess Framework CLI -> `npm install -g serverless`, `sls --version`
- AWS IAM -> `https://console.aws.amazon.com/iamv2/home?#/home`
  - After creating [IAM user](img/IAM/UserConfig.png)
  - In terminal, `aws configure` to [get](img/IAM/AWSConfig.png) 
- AWS Budget -> `https://console.aws.amazon.com/billing/home?region=us-east-1#/budgets/overview`
- Postman -> `https://www.postman.com/`
- code editor -> `https://code.visualstudio.com/`
- Serverless IDE for Visual Studio Code -> `https://marketplace.visualstudio.com/items?itemName=ThreadHeap.serverless-ide-vscode`

## 🎈 Usage <a name="usage"></a>
### Install dependencies 
> npm install 

### Deploy serverless app
> sls deploy -v 

## ⚡ UI <a name="ui"></a>
### Images coming soon 
### Starting dashboard

### Main page to add items 
![screenshot2](/imgs/screenshot-2.png)
### NavBar
![screenshot3](/imgs/screenshot-4.png)


## Current Issues <a name = "issues"></a>
1. Time 
2. Add frontend for Auction 

## Authors <a name = "authors"></a>

- Vaishvik Maisuria







