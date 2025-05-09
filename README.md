# 🚀 End-to-End Data Engineering Pipeline on Azure

This project demonstrates an end-to-end data engineering pipeline using Azure services — from ingesting raw data to transforming and visualizing it in Power BI.

---

## 🧱 Architecture Overview

![Architecture Diagram](images/architecture-diagram.png)

---

## 🔧 Tools & Technologies Used

- Azure Data Factory (ADF)
- Azure Blob Storage (Bronze, Silver, Gold layers)
- Azure Databricks
- Azure Synapse Analytics (Serverless SQL)
- Power BI

---

## 📂 Data Flow

1. **🔗 Data Source**: Raw data is fetched from a GitHub repo using HTTPS.
2. **📥 Bronze Layer**: ADF ingests and stores data into Azure Blob (bronze container).
3. **⚙️ Data Transformation**: Azure Databricks cleans and transforms the data.
4. **📤 Silver Layer**: Transformed data is stored in the silver container.
5. **🧠 Semantic Layer**: Azure Synapse creates SQL views and runs queries.
6. **📊 Visualization**: Power BI connects to Synapse and visualizes the data.

---


