1. Setup the set up your development environment. This process includes installing the Service Fabric SDK and Visual Studio 2017 or 2015.
https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started
---Installed VS 2019 preview
---Installed Service Fabric SDK
---Installed dotnet core sdk 2.2
2. Install Docker for windows.
3. Create dotnet application and deploy
https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-tutorial-create-dotnet-app
4. Stateless Web app invoking Stateful Service, and deployed on azure.

5. Powershell command to get clinet certificate from .pfx in azure devops
 [System.Convert]::ToBase64String([System.IO.File]::ReadAllBytes("C:\Cloud\Azure\AzureDevOps\serv
ice-fabric-dotnet-quickstart\mytestcert.pfx"))
