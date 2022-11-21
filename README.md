# BenAzureDB-demo :
 Example based on the code linked to the [video](https://youtu.be/3XgepwpBJP8?list=PLLasX02E8BPDT2Z2pdCHNCkENpcQWy5n6).
 
 *Drew Skwiers-Koballa shows Scott Hanselman a new option for developing with Azure SQL Database: 
 The Azure SQL Database emulator, which is a containerized database for a desktop dev experience. Use your favorite client 
 OS and dev tools for cloud development without the cloud.*
 
 Prerequisits to running well :
 - Docker in windows was started
 - dotnet6 SDK (include by itself the runtime) was installed
 - VSCode
 
 ## Source code forked from:
 - [Drew Skwiers-Koballa  - Azure Friday](https://github.com/dzsquared/azure-friday)
 
 ## Note 01: Fixed issue with azure function tools in VSCODE:
 - Issue was there with azure function tools so it's running well after that in my case I just executed this command in my vs code project where the tool 
 where I would use the v4 :npm install -g azure-functions-core-tools@4 --unsafe-perm true
 
 ## Note 02: Extension used in VS Code
 - "REST Client" extension by Huachao Mao (good to test http endpoints in VSCODE as a bit in POSTMAN) :
    - [Market place](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
    - [Github vscode-restclient] https://github.com/Huachao/vscode-restclient
    
 ## Note 03: the syntax of the json in the local.settings.local was important:
 - to check it, see the file: **exampleof__local.settings.json** 
 
 ## TIPS VS CODE: 
 - **Multi cursors** shortcut in vs code : **Ctrl+Shift+L** ;0)  (Tx to [stackoverflow](https://stackoverflow.com/questions/29953479/how-can-you-create-multiple-cursors-in-visual-studio-code))
