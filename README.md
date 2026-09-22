# Azure Data Factory Product Pipeline
ADF Pipeline that loads .csv into Azure SQL tables using appropriate data types.

## Project Overview

This project demonstrates an Azure data factory pipeline that moves CSV Product data from Azure Blob Storage into Azure SQL database using appropriate SQL data types.

## Pipeline Architecture

P03_Products.csv, -> Azure Blob Storage, -> Azure Data Factory, -> Azure SQL Database.

## Technologies used

* Azure Data Factory
* Azure Blob Storage
* Azure SQL Database 
* GitHub

## Screenshots

## 1. Azure resources

![P03 Azure Resources](01-P03-Azure-Resources.png)

![P03 Azure Resources](02-P03-ADF-Pipeline-Source.png)

![P03 Azure Resources](03-P03-ADF-Pipeline-Sink.png)

![P03 Azure Resources](04-P03-AzureSQL-ProductData.png)



## What I learned

* How to connect Blob Storage to ADF and use a copy activity.
* Schema and mapping basics for CSV to SQL.
* Importance of exact file naming in documentation.
* Mapping to proper SQL data types.
* Using a primary key to prevent duplicates.
* Troubleshooting primary key errors, and using truncate to clear test data.
* Validate, debug, and publish.

## Project files

* [P03_Products.csv](P03_Products.csv)



