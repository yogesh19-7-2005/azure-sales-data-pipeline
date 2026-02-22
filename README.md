# Azure Sales Data Pipeline using Azure SQL, Data Factory and Blob Storage

## 📌 Project Overview

This project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline using Microsoft Azure services. The pipeline extracts sales data from Azure SQL Database, stores raw data in Azure Blob Storage, performs data transformation using Azure Data Factory, and stores the processed data back in Blob Storage.

The project shows how cloud-based data pipelines are built for real-world data engineering tasks.

---

## 🏗️ Architecture

Azure SQL Database  
↓  
Azure Data Factory (Copy Activity)  
↓  
Azure Blob Storage (Raw Data - Input Container)  

Azure SQL Database  
↓  
Azure Data Factory (Data Flow: Filter and Sort)  
↓  
Azure Blob Storage (Processed Data - Output Container)

---

## 🛠️ Technologies Used

- Azure SQL Database
- Azure Data Factory
- Azure Blob Storage
- Azure Storage Account
- ETL Pipeline

---

## 📂 Dataset Information

Table Name: `sales_data`

Columns:

- product_id
- product_name
- category
- price
- quantity
- sales_date

---

## ⚙️ Steps Performed

### Step 1: Created Azure SQL Database

- Created Azure SQL Server and Database
- Created sales_data table
- Inserted sample sales records

---

### Step 2: Created Azure Storage Account

- Created Storage Account
- Created two containers:
  - input (Raw Data)
  - output (Processed Data)

---

### Step 3: Created Copy Pipeline

- Created pipeline in Azure Data Factory
- Copied data from Azure SQL Database
- Stored raw data in input container

---

### Step 4: Created Data Flow for Transformation

Applied following transformations:

- Filter Condition: price > 10000
- Sort: sales_date in descending order

---

### Step 5: Stored Processed Data

- Stored transformed data in output container
- Processed data available for analytics and reporting

---

## 📊 Project Result

- Successfully extracted data from Azure SQL Database
- Successfully stored raw data in Blob Storage
- Successfully transformed data using Data Flow
- Successfully stored processed data in Blob Storage
- End-to-end ETL pipeline completed

---

## 📁 Project Structure

---

## 🚀 Key Learnings

- Built end-to-end ETL pipeline
- Learned Azure Data Factory
- Learned Data Flow transformation
- Learned Azure Blob Storage integration
- Learned real-world data engineering workflow

---

## 👨‍💻 Author

Yogesh Sharma




