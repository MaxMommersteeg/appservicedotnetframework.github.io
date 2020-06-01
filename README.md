# .NET Framework 4.8 is coming to App Service
We are making an update to App Service to support .NET Framework 4.8. The update is coming to App Service starting deployment in July 14, 2020 and ending by September 15, 2020.  In preparation for your application to be updated to .NET Framework 4.8 we recommend that you test your applications locally in advance to prepare.

[What are the main benefits for App Service customers coming in this change?]
1. 
2.

## Preparing your site 
#### Testing your applications locally
[General Updates](https://devblogs.microsoft.com/dotnet/announcing-the-net-framework-4-8/) <br/>
[Release Notes](https://github.com/microsoft/dotnet/blob/master/releases/net48/README.md)

1. Download .NET Framework 4.8
2. Update your application
3. Run it on local browsers

What will be affected? What to test for?

#### Confirming the update on your application
To see if your apps have been updated after we begin the platform update, check which .NET Framework version is in use by using the *Console* feature under *Development Tools* in the App Service blade of your Azure Portal.

ADD_SCREENSHOT_OF_INTERFACE_ACTIONS

1. Run the following command: cd "\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework" .  

2. Run the dir command to list out the installed versions of .NET Framework.  

3. If .NET Framework 4.8 is installed, it will be located at D:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8 
