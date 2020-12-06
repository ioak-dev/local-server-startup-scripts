# Supported methods
1. Startup the servers from within vs code editor
2. Startup the servers from windows command line by running a single batch file

## Visual studio code (VS code) setup
Install following extension in visual studio code
https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-terminals

Open the desired application workspace from visual studio code

Open command palette [Ctrl + Shift + P] and run following based on the requirement. First time, you should type in "Terminals: " to show up following choices on the list
Terminals: Run > to bring up all necessary servers for the project/app
Terminals: Run Single > to choose which module to start

### First time setup in local
From VS code, File -> Open Workspace
browse to vscode/appname-firsttime.code-workspace

### Day to day use case (after first time setup is completed once)
From VS code, File -> Open Workspace
browse to vscode/appname.code-workspace

## Windows command line setup
### First time setup in local
open windows/appname-firsttime.bat

### Day to day use case (after first time setup is completed once)
open windows/appname.bat
