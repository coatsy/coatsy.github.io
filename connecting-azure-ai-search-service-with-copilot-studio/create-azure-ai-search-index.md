# Create an Index in Azure AI Search

Detailed instructions are available in the [Microsoft Documentation](https://learn.microsoft.com/en-us/azure/search/search-get-started-portal-import-vectors)

In summary, to create an index in Azure Open AI Search, follow these steps:

1. Go to the Azure portal at [https://portal.azure.com/](https://portal.azure.com/).
1. Click on the Azure Open AI Search service that you created earlier.
1. Click on the "Import and vectorize data" tab.
1. Choose one of the available data sources. These instructions assume you choose "Azure Data Lake Storage Gen 2".
1. Choose the storage account and blob container that hold your documents.
1. Click on the "Next" button.
1. Choose the name of the Azure OpenAI service you created earlier.
1. Choose the embedding model you deployed earlier (e.g. `text-embedding-ada-002`).
1. Ensure the Authentication type is set to "API key".
1. Check the box to acknowledge the cost warning.
1. Click on the "Next" button.
1. Click on the "Next" button.
1. Under Index fields, choose "Preview and edit".
1. Click on the "Add new" button.
1. In the new field under Source column, choose `metadata_storage_path`.
1. Click the "Save" button.
1. Click the "Next" button.
1. Click the "Create" button.
1. Close the "Create succeeded" dialog.
