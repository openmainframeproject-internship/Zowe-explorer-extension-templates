
[Zowe](https://www.zowe.org) is an integrated and extensible open source framework for z/OS which offers modern interfaces to interact with z/OS and allows you to work with z/OS in a way that is similar to what you experience on cloud platforms today. You can use these interfaces as delivered or through plug-ins and extensions.The Zowe Explorer Extension is a Visual Studio Code extension that modernizes the way developers and system administrators interact with z/OS mainframes. 

The main goal of this project is to Build a Zowe VS Code Extension Template. To archieve that, we would create a zowe CLI plug-in which will us [cURL](https://curl.se/) to connect to ["Zowe Sample API service"](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md) and get data from a REST API and bring back response in JSON format, and then VS Code Extension will be build on top of the developed zowe CLI plug-in