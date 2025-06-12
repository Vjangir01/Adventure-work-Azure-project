# Azure End-to-End Data Engineering Project – AdventureWorks

![Architecture](./037698aa-e0e4-4def-b26e-f5fa1f54c9d4.png)

## 📌 Project Overview

This project demonstrates a complete **end-to-end data engineering pipeline** on **Azure**, using the **AdventureWorks** dataset. The solution simulates a real-world architecture that handles data ingestion, transformation, storage, and reporting, leveraging Azure-native services.

## 🧱 Architecture Components

### 1. 🔗 Data Source
- **Type**: HTTP (simulated using AdventureWorks data)
- **Format**: CSV files

### 2. 📥 Data Ingestion
- **Tool**: Azure Data Factory
- **Task**: Ingest raw AdventureWorks data into Azure Data Lake Gen2 (Bronze layer)

### 3. 🪵 Raw Data Store (Bronze Layer)
- **Storage**: Azure Data Lake Gen2
- **Purpose**: Store unprocessed/raw data

### 4. 🔄 Data Transformation (Silver Layer)
- **Tool**: Azure Databricks
- **Languages**: PySpark / Python
- **Task**: Cleanse, validate, and transform data

### 5. 📦 Transformed Data Store (Silver Layer)
- **Storage**: Azure Data Lake Gen2
- **Purpose**: Store cleansed and enriched data

### 6. 🧠 Serving Layer (Gold)
- **Tool**: Azure Synapse Analytics
- **Task**: Build curated tables and enable data modeling

### 7. 📊 Reporting
- **Tool**: Power BI
- **Task**: Create interactive dashboards and business insights

---

## 📁 Folder Structure

