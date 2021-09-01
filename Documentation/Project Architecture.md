# [Zowe](https://www.zowe.org/) Explorer Extension Templates Architecture

![alt text](Project_Architecture.png)

## Components

  * ["Zowe Sample API service"](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md)  - web service
  * "Zowe CLI plug-in " will connect and call a REST API in ["Zowe Sample API service"](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md) and bring back response 
  * "VS Code extension" will be build on the developed "zowe CLI plug-in"
  * The "User" will interact with all these components through the generated "VS Code Extension"
## Description
* a user interacts with Zowe Sample VS Code Extension or Zowe CLI Sample Plugin
* the common Zowe Sample SDK code reads config or profiles
* then calls the Zowe Sample REST API with optional query parameters
* the "hello" message response is returned via the API, to the SDK, and to the end user

## Technologies Used

* Typescript
* Javascript
* JSON
* [Node.js](https://nodejs.org)
