---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
- services: Batch
- platforms: dotnet
---

# Getting started on managing batch accounts in C# #

 Azure Batch sample for managing batch accounts -
  - Get subscription batch account quota for a particular location.
  - List all the batch accounts, look if quota allows you to create a new batch account at specified location by counting batch accounts in that particular location.
  - Create a batch account with new application and application package, along with new storage account.
  - Get the keys for batch account.
  - Regenerate keys for batch account
  - Regenerate the keys of storage accounts, sync with batch account.
  - Update application's display name.
  - Create another batch account using existing storage account.
  - List the batch account.
  - Delete the batch account.
      - Delete the application packages.
      - Delete applications.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/batch-dotnet-manage-batch-accounts.git

    cd batch-dotnet-manage-batch-accounts

    dotnet build

    bin\Debug\net452\ManageBatchAccount.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.