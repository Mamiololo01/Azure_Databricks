# Azure_Databricks
A guide to designing and implementing ETL on Azure with Medallion architecture, using Azure Databricks, Azure Data Factory, PySpark, Spark Streaming, Delta Live tables, SCD, and dimensional data modelling.

## Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems in Azure Databricks using PySpark and Azure Data Factory(ADF).
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights on Azure Synapses connected to Azure Databricks.
5. **Governance & ACID compliance**: Implementing Unity catalog and Delta Lake on Azure Databricks.


## Architecture

The architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](images/Azure_databricks.png)



## Resources
1. **Free Azure Account**: https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account
2. **Azure Resource Group**: https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal
3. **Azure Data Factory**: https://azure.microsoft.com/en-us/products/data-factory#Resources-6
4. **Delta live table**: https://www.databricks.com/discover/pages/getting-started-with-delta-live-tables
5. **Slowly changing dimensions**: https://learn.microsoft.com/en-us/fabric/data-factory/slowly-changing-dimension-type-one
6. **Unity Catalog**: https://learn.microsoft.com/en-us/azure/databricks/data-governance/unity-catalog/
7. **Azure Data Lake Storage**: https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-best-practices
8. **Azure Databricks**: https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account?icid=databricks


## Workflow

The end to end workflow from data ingestion to all layers **Bronze**, **Silver**, and **Gold** is depicted below:

![Workflow](images/E2E_pipeline_workflow.png)

