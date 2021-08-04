# <p align="center">Zowe Explorer Extension Templates
## <p align="center">Status Report
<p align="center">30th July, 2021

## Project Members:
* Daniel Kelosky - Mentor - Broadcom
* Muhammad Ali - Mentee - University

## Accomplishment for the week 
* Code for the API, CLI and VSCE all hosted in the monorepo - [zowe/zowe-client-sample-apps](https://github.com/zowe/zowe-client-sample-apps)

## List of Milestones to be completed and anticipated date
* Add a Code that will prompt and collect input(Name of the user) immidiately after running the "Hello World" command in the new vsce and add the input to the greeting API to greet the user
* Write test cases to unit test the Greeting API  
* At first, when trying to run the "Hello World" command, The application crashed because of the absence of the zowe.config and zowe.schema files - Handle that more gracefully by debugging the code and detecting which line is crashing, Then add some code to tell the user what he needs to do instead of the application just crashing and the user don't know what to do

## List of issues, problems or concern(s)
* Nil