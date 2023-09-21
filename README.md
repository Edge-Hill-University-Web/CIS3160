# CIS3160 Development and Analysis Environment 

A preconfigured environment for CIS3160

## Requirements

The following Applications and extensions need to be installed!

- **Docker Desktop**

- **VS Code** and the following extensions
  - *Docker*: [get](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  - *Dev-Containers* [get](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  
 ## Instructions

 1. Clone repository
 2. launch VS Code
 3. In the bottom left corner of VS Code there will be a green icon (if not you will need to install the Dev-Containers extension). Click on it and a menu will appear. Select the "Open Folder In Container..." option.
 4. Navigate to the directory you cloned the repository into and select the `CIS3160` directory.
 5. This will then begin to build the container (this may take some time).
 6. If successful you should now see in the bottom left corner of the VS Code window a green element in the status bar that states `Dev Container: CIS3160 @ desktop-linux`. Green means go.
 7. Congrats you have a working environment
