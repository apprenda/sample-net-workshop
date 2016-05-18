# .NET Workshop Application
Sample .NET Application for use during the Workshop

This application is to be used during the Apprenda workshop to learn how to deploy a .NET application on the platform. 
The application uses standard modern libraries like MVC, Entity Framework and Log4NET. Additionally, there is a SQL Script for DBaaS deployment through the platform. 

The application leverages the Log4NET appender bootstrapper to automatically redirect logs to the Apprenda platform.

# Deployment Instructions
1. Download the code for the application
2. Use Visual Studio to build the solution
3. You can use the Apprenda Visual Studio Extension or Archive Builder to build an Apprenda Archive
4. Log in to the Developer Portal and Deploy!

#Notes
If you want logs to show up in your Developer Portal, your environment needs to have the Log4NET bootstrapper deployed as well. 
