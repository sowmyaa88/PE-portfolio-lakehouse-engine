# 📊 PE Portfolio Lakehouse Engine (Databricks & PySpark)

> **Enterprise Business Case:** A unified Medallion Lakehouse built on Databricks to ingest, cleanse, and consolidate fragmented operational and financial data across multi-entity Private Equity (PE) portfolio holdings.

---

## 📌 Business & Architectural Overview

Private Equity sponsors and portfolio management teams frequently face fragmented data ecosystems across acquired operating companies. This project addresses the challenge of multi-source data ingestion by building a scalable, multi-tenant **Medallion Lakehouse Architecture** powered by **Databricks**, **PySpark**, and **Delta Lake**.

---

## 🏗️ Architecture

This project follows the **Medallion Architecture**:

### 🥉 Bronze Layer
- Raw data ingestion  
- Schema inference and storage as Delta tables  

### 🥈 Silver Layer
- Data cleaning and standardization  
- Type casting and validation  

### 🥇 Gold Layer
- Dimensional Data Model (Business Transformation)
- Ready for BI and analysis  

---

## 🛠️ Technologies Used

- Databricks  
- Apache Spark  
- PySpark  
- Spark SQL  
- Delta Lake  
- Unity Catalog  


---


## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.




