# electron-dotnet-app

### Prerequisite Software
Node JS
.NET Core 3.1 or above

Install the Electron command-line tool using the following command
dotnet tool install ElectronNET.CLI -g

### Packages 
```sh
$ dotnet add package ElectronNET.API 
```

#How to run the Application
 
If you have installed the Electron CLI then open the command-line tool and go to the File path where your .csproj file exist in file explorer and put the following command,

### Entity framework Commands

```sh
$ electronize init
$ electronize start /watch
``` 
 
electronize init is one time command when you run the application for the first time.
 
electonize start /watch This command is to run the application and also get refreshed automatically if any changes doing in code. It will launch the window application.

### Build win
electronize build /target win /PublishReadyToRun false

### Build Mac
electronize build /target osx /PublishReadyToRun false 

### Build linux
electronize build /target linux /PublishReadyToRun false
