# 🚀 Azure Data Pipeline Demo

This demo illustrates a simplified Azure Data Factory (ADF) pipeline used to ingest and transform data from external systems like Salesforce and EDI partners.

## 🧩 Use Case

A daily pipeline that:
- Pulls EDI and Salesforce data from FTP/API sources
- Stores raw files in Azure Data Lake (ADLS Gen2)
- Triggers Databricks notebooks for data cleansing and transformation
- Final output written to curated zone for Power BI reporting

## ⚙️ Tech Stack

- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2 (ADLS)
- Azure Databricks
- CI/CD via Azure DevOps

## 📁 Structure
