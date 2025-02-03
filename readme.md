# ASP Net

This is a practice tutorial for ASP .NET and how to use it to create a functional backend.
Video: [ASP.NET Core Full Course For Beginners](https://www.youtube.com/watch?v=AhAxLiGC7Pc&ab_channel=JulioCasal) <br />
Length: 3:43

Path: ebravo/Practice/aspNET

### VSCode Pluggins
- SQlite
    -    Allows us to easily interact with our SQLite database we use for this tutorial.
- Rest Client
    - Improved the way we interact with REST API's

## .NET
Given this is a tutorial, there will be many notes on the steps taken to achieve this backened, as well as, terminal commands and what htey do.

### Start:
- dotnet new list
    - this gives you the full list of applications that you can create with your local SDK installation
    - Another way you can go about this is View>Command Pallette (ctrl shift P) then type ".NET New Project"
    - Here we are selecting ASP.NET Core Empty

- After selecting "ASP.NET Core Empty, name the file NAME.Api
    - In this case GameStore.Api

## Files

### Program.cs 

<h6>Path: (GameStore.Api/Program.cs)</h6>

- Is the **host** of your web application 
- Listens to HTTP requests
- "builder" object can introduce services
- Allows us to send output into the terminal


### GameStore.Api.csproj 

<h6>Path: (GameStore.Api/GameStore.Api.csproj)</h6>

- Known as the **"project file"**
- This is where we add dependencies 

### appsettings.json 

<h6>Path: (GameStore.Api/GameStore.Api.csproj)</h6>

- Known as the **"project file"**
- This is where we add dependencies 

### appsettings.Development.json  

<h6>Path: (GameStore.Api/GameStore.Api.csproj)</h6>

- Known as the **"project file"**
- This is where we add dependencies 


