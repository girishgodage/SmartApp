# **SmartApp** - ASPNET Core 5 / Angular 11 project template


A startup **Angular 11 / ASP.NET Core 5** (cross-platform ) **project template** with an end-to-end login, user and role management implementation.
As well as other common functionalities for **Smart Application Development**.

## This application consists of:

*   Template pages using Angular 11 and TypeScript
*   RESTful API Backend using ASP.NET Core 5 MVC Web API
*   Database using Entity Framework Core
*   Authentication based on OpenID Connect
*   API Documentation using Swagger
*   Angular CLI for managing client-side libraries
*   Theming using Bootstrap 4

## You get the benefits of:

*   A complete backend and frontend project structure to build on, with login, user and permission-based role management already integrated
*   Data Access Layer built with the Repository and Unit of Work Pattern
*   Code First Database
*   A RESTful API Design
*   Angular Directives Quidance
*   Angular Pipes Quidance
*   Angular Animations Quidance
*   Angular Services
*   Dialog and Notification Services
*   Configuration Page and Configuration Service
*   Integrated Internationaliztion
*   Theming with SASS
*   Ready-to-use email API
*   Handling Access and Refresh Tokens with WebStorage (Bearer authentication) - No Cookies
*   Jquery Integration (Ability to use standard Jquery libraries)
*   CRUD APIs
*   Responsive Design
*   Etc.


## Installation

*   [OPTION 1] Clone the [Git Repository](https://github.com/girishgodage/SmartApp.git) and edit with your favorite editor. e.g. Visual Studio, Visual Studio Code
*   [OPTION 2] Install Project template from the [Visual Studio Gallery](https://marketplace.visualstudio.com/items?itemName=GirishGodage.SmartApp) and follow the usual File -> New Project -> Web -> SmartApp - to create a new Project from this template.
    Launch with `F5` or `Ctrl+F5` (The usual way)


## Installation Notes

*   When creating a new project please wait for all dependencies to be restored; "dotnet restore" for asp.net project & "npm install" for angular project.
    When using VisualStudio this is automatic, check the output window or status bar to know that the package/dependencies restore process is complete before launching your program for the first time.
*   If you get any errors, consider running manually the steps to build the project and note where the errors occur.
    Open command prompt and do the below steps:  
    1. run 'dotnet restore' from the two project folders - Restore nuget packages
	2. run 'npm install' from the project with package.json - Restore npm packages
	3. Try running the application again - Test to make sure it all works
*	When running the client(angular) project on a different address/domain from the backend, configure the baseUrl of the client to match that of the server.
	You do this from environment.ts in the ClientApp/Angular project.
	Example: baseUrl: "http://yourbackendserver.com" OR baseUrl: "http://localhost:5050"

## Login

LOGIN WITH USERNAME OR EMAIL ADDRESS
> * **Default Administrator Account**
>   * Username: admin
>   * Email:    admin@gmail.com
>   * Password: 123Pa$$word.
> * **Default Standard Account**
>   * Username: user
>   * Email:    user@gmail.com
>   * Password: 123Pa$$word.



## License

Released under the [MIT License](https://github.com/girishgodage/SmartApp/blob/main/LICENSE).
