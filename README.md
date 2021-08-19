# *Zowe explorer extension templates*
## *Short Project Description*
The directory structure in this GitHub is to allow the project to have all its resources self-contained.
Open Source software should not just be a repository of code.  There are a number of directories to help you and others that will 
follow in your foot steps.  It'll also allow the Linux Foundation OMP Mentorship program to keep track of your project and get
a better understanding of the problems you encountered during the developmemnt of this project.

| Folder | Description |
|---|---|
| [Documentation](https://github.com/muhammad-md/Zowe-explorer-extension-templates/tree/master/Documentation) |  all documentation the project team has created to describe the architecture, design, installation and configuratin of the peoject |
| Notes and Research | Relavent information useful to understand the tools and techniques used in the project |
| [Status Reports](https://github.com/muhammad-md/Zowe-explorer-extension-templates/tree/master/Status%20Reports) | Project management documentation - weekly reports, milestones, etc. |
| [scr](https://github.com/muhammad-md/Zowe-explorer-extension-templates/blob/master/src/Readme.md) | Source code - create as many subdirectories as needed |

## CODE
All code for this project are hosted in the Monorepo [`zowe/zowe-client-sample-apps`](https://github.com/zowe/zowe-client-sample-apps)
- This project provides Sample Zowe Client applications which connect and use a sample REST API service and adhere to Zowe conformance standards.

## Building Prerequisites
 `npm` version `7.20+` (`npm install -g npm`)
## Building


1. `git clone https://github.com/zowe/zowe-client-sample-apps`
2. `npm install`
3. `npm run build`

## Backend service used in the project
* [`Zowe Sample Api Service`](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md)

## Project Team
- *Daniel Kelosky*  - *Broadcom* - Mentor
- *Muhammad Ali* - *University* - Mentee
