---
author: DavidCBerry13
ms.author: daberry
ms.topic: include
ms.date: 03/31/2022
---
In this method, a developer must be signed in to Azure from either the Azure Tools extension for Visual Studio Code, the Azure CLI, or Azure PowerShell on their local workstation. The application then can access the developer's credentials from the credential store and use those credentials to access Azure resources from the app.<br>
<br>
This method has the advantage of easier setup because a developer only needs to sign in to their Azure account from Visual Studio Code or the Azure CLI. The disadvantage of this approach is that the developer's account likely has more permissions than required by the application. As a result, the application doesn't accurately replicate the permissions it will run with in production.<br>
<br>
> [!div class="nextstepaction"]
> [Learn about auth from Azure-hosted apps](../authentication-local-development-dev-accounts.md)