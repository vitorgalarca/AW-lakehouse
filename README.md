# Adventure Works Cycles | Lakehouse | End to End Azure Data Engineering Project

This an end-to-end data engineering project on the Azure cloud. Where I did data ingestion from a Azure SQL Database to Azure Data Lake using Data Factory to transformation using Databricks and Spark, loading to Synapse, and reporting using PowerBI. Also, I used Azure Entra ID (Active Directory) and Azure Key Vault for the data monitoring and governance purpose.

# Architecture

![arquitetura](https://github.com/vitorgalarca/AW-lakehouse/assets/151578825/0b970465-1927-45df-83a4-335b8c05e3da)

 
# Tools and Architecture

List and explanation of Azure resources used:

- Azure Data Factory (ADF)
- Azure Synapse Analytics
- Azure Databricks
- Azure Data Lake Gen 2
- Azure Active Directory
- Azure Key Vault
- Power BI

Introduction to "Lakehouse architecture" with bronze, silver, and gold data layers

# 🎯 Project Goals

- Ingest tables into the Azure Data Lake.
- Apply data cleaning and transformation using Azure Databricks.
- Utilize Azure Synapse Analytics for loading clean data.
- Create interactive data visualizations and reports with Microsoft Power BI.
- Implement Azure Active Directory (AAD) and Azure Key Vault for monitoring and governance.

# Data Ingestion

Using ADF to connect to Azure SQL Database and copy data tables
- Storing data in Azure Data Lake Gen 2

 
# Data Transformation
 
## Azure Databricks for data transformation tasks

- Bronze layer: Raw data copy
- Silver layer: Basic transformations (data types, etc.)
- Gold layer: Final curated data

 
# Data Loading and Reporting

- Loading gold layer data into Azure Synapse Analytics
- Using Power BI to create reports and visualizations on Synapse Analytics data

# Dashboard
