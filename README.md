# .NET Framework 4.8 is coming to App Service
We are making an update to App Service to support .NET Framework 4.8. You will soon be able to take advantage of the .NET Framework updated toolset, bug fixes and key improvements in accessibility and runtime.  For the full list of updates and changes see the [anouncement](https://devblogs.microsoft.com/dotnet/announcing-the-net-framework-4-8/) and [release notes](https://github.com/microsoft/dotnet/blob/master/releases/net48/README.md).  The update is coming to App Service starting deployment in *July 14, 2020* and completing by *September 15, 2020*.  In preparation for your application update to .NET Framework 4.8 we recommend that you test your applications locally in advance to prepare.

To track progress during the deployment, we will be posting periodic updates [here](https://github.com/Azure/app-service-announcements/issues/249).

### Testing your applications locally
Test your application locally by downloading the framework, understanding the changes linked below, and running your application accordingly.  

1. Download .NET Framework 4.8 for your appropriate scenario [here](https://devblogs.microsoft.com/dotnet/announcing-the-net-framework-4-8/).
2. See the [Migration guide](https://docs.microsoft.com/en-us/dotnet/framework/migration-guide/) for an overview of resources to review 
3. See the [Runtime changes](https://docs.microsoft.com/en-us/dotnet/framework/migration-guide/runtime/4.7.2-4.8) and [Retargeting guide](https://docs.microsoft.com/en-us/dotnet/framework/migration-guide/retargeting/4.7.2-4.8) to check for application compatibility issues that may affect your application.
4. Run your application on your local browser.

If you have issues with your application, feedback can be given on [github](https://github.com/Microsoft/dotnet/issues/).

### Confirming the update on App Service
To see if your apps have been updated after we begin the platform update, check which .NET Framework version is in use by using the **Console** feature under **Development Tools** in the App Service blade of your Azure Portal.

![Console](images/console.png)

1. Run the following command: *cd "\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework"* .  

2. Run the *dir* command to list out the installed versions of .NET Framework.  
![Console2](images/console2.png)

3. If .NET Framework 4.8 is installed, it will be located at *D:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8*



