# Netflix_DataEngineering_Project

Overview

This project is a real-time, end-to-end Azure Data Engineering solution built using the latest tools and technologies. It covers data ingestion, transformation, validation, and orchestration to create a production-grade pipeline leveraging the Medallion Architecture (Bronze, Silver, and Gold layers)

Features

Dynamic, parameterized data pipelines in Azure Data Factory (ADF)

Incremental data ingestion using Databricks Autoloader

Delta Live Tables for efficient ETL workflows

Orchestrated workflows in Databricks

Data validation and monitoring using ADF & Azure Monitoring

Seamless data integration with Azure Synapse Analytics & Power BI

Architecture

Technologies Used:

Azure Data Factory (ADF) – for data ingestion from GitHub & Azure Data Lake

Azure Data Lake Storage (ADLS Gen2) – for scalable cloud storage

Azure Databricks – for data transformation, ETL, and orchestration

Azure Synapse Analytics – for data warehousing and reporting

Power BI – for data visualization

Workflow

Data Source: Netflix data is stored in GitHub and Azure Data Lake.

Data Ingestion: ADF copies data dynamically into ADLS (Bronze Layer).

Incremental Loading: Databricks Autoloader reads new data and stores it in the Silver Layer.

Transformation: Databricks processes data using Delta Live Tables, applying business logic and aggregations.

Gold Layer: Refined data is stored in the Gold Layer (Delta Lake) for analysis.

Data Consumption: The final dataset is available for Azure Synapse Analytics & Power BI.

Project Setup

Prerequisites

Azure Account (with free credits)

Databricks Workspace (created in Azure Portal)

Azure Data Lake Storage (ADLS Gen2)

Azure Data Factory (ADF)

GitHub Repository Access (for Netflix dataset)

Data Sources

Netflix Movies & TV Shows Dataset (CSV format)

Source: https://www.kaggle.com/datasets/shivamb/netflix-shows

Key Learnings

Building Enterprise-Grade Data Pipelines

Implementing Medallion Architecture

Working with Azure Data Engineering Tools

Handling Real-World Data Scenarios

Optimizing Performance using Delta Live Tables
