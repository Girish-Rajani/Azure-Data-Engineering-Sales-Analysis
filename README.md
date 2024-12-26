# Azure-Data-Engineering-Sales-Analysis
The use case for this project is building an end-to-end solution by ingesting the tables from the on-premise SQL Server database using Azure Data Factory and then storing the data in Azure Data Lake. Azure Databricks is used to transform the RAW data into the cleanest form of data. Then I used Azure Synapse Analytics to load the clean data and finally used Microsoft Power BI to integrate with Azure Synapse Analytics to build an interactive dashboard. Also, used Azure Active Directory (AAD) and Azure Key Vault for monitoring and governance purposes. This workflow is illustrated in the below diagram.

![Screenshot 2024-12-26 120938](https://github.com/user-attachments/assets/1898ebb3-732c-4e67-89de-b91727d35828)

The tools that are covered in this project are,

Azure Data Factory
Azure Data Lake Storage Gen2
Azure Databricks
Azure Synapse Analytics
Azure Key vault
Azure Active Directory (AAD) and
Microsoft Power BI

![Screenshot 2024-12-26 121632](https://github.com/user-attachments/assets/6eeb9370-e9db-460e-9add-42033b543cb2)

Azure Data Factory was used to create a data pipeline to copy the data from an On-prem SQL Server Database and store it in Azure Data Lake as shown above. 

Using Azure Databricks, the first layer of transformation was done by transforming all date datatypes is all tables to a uniform suitable format (bronze to silver transformation). The second layer of transformation converted all column names from camel case to snake case with underscores (silver to gold transformation).


![Screenshot 2024-12-26 124457](https://github.com/user-attachments/assets/a3cf1575-ae11-44d9-9c81-1a02b8b0619a)


Used Azure Synapse Analytics to perform extensive Sales Analysis on the cleaned data and derive insights. Created an interactive dashboard in PowerBI to retrieve further insights in real time.









