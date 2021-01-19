# Data Engineering on MS Azure

We present a simple solution of a typical ETL copy procedure with the Azure tool set. We start by creating resources and pre-processing data by setting up the approriate resources in Azure and manage their access to each other. Build pipelines in Data Factory that can read data from Azure SQL server, transform and write data. We setup this using classic Northwind database sample data from Microsoft. 

This is the high-level overview of this ETL copy setup: 
<insert Azure arch diagram>
  
For those who want to deploy this ETL straight to Azure can download our ARM templates for setting up all the appropriate resources. However you'd still need to manually create additional Azure resources on the portal:

1. Resource Group
2. Azure SQL Server and its database
3. Storage account (Azure Data Lake Storage Gen 2)
4. Key Vault


