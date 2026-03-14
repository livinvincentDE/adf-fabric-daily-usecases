# 🚀 Azure Data Factory (ADF) Use Cases

This repository documents **real-world Azure Data Factory (ADF) use cases** designed to practice and demonstrate **production-grade data engineering pipeline patterns**.

The use cases are categorized into **Intermediate** and **Advanced** levels to help progressively build expertise in **data ingestion, transformation, orchestration, and pipeline optimization**.

---

# 🧠 Intermediate Use Cases

| #  | Use Case                              | Description                                                |
| -- | ------------------------------------- | ---------------------------------------------------------- |
| 1  | 🔁 Incremental Data Load              | Load only new records using watermark columns              |
| 2  | 🧩 Metadata Driven Pipeline           | Use a control table to drive dynamic data ingestion        |
| 3  | 🔄 ForEach Loop Pipeline              | Process multiple files or tables dynamically               |
| 4  | 🌐 REST API Data Ingestion            | Extract data from REST APIs into Data Lake                 |
| 5  | 📦 JSON to SQL Pipeline               | Transform semi-structured JSON data into relational tables |
| 6  | ⚠️ Retry & Error Handling             | Configure retry policies and pipeline failure handling     |
| 7  | 🔧 Data Transformation with Data Flow | Perform joins, filters, and aggregations                   |
| 8  | 🔗 Multi Source Data Integration      | Combine data from SQL, CSV files, and APIs                 |
| 9  | 📁 Dynamic Folder Processing          | Ingest data from partitioned folders like year/month/day   |
| 10 | 📊 Pipeline Execution Logging         | Store pipeline execution details for monitoring            |

---

# ⚙️ Advanced Use Cases

| #  | Use Case                                  | Description                                            |
| -- | ----------------------------------------- | ------------------------------------------------------ |
| 11 | 🥇 Medallion Architecture Pipeline        | Implement Bronze → Silver → Gold data layers           |
| 12 | 🏗 Dynamic Table Creation                 | Automatically create tables when they do not exist     |
| 13 | ✅ Data Quality Framework                  | Validate null values, duplicates, and invalid data     |
| 14 | 🕒 Slowly Changing Dimension (SCD Type 2) | Maintain historical changes in dimension tables        |
| 15 | 🔍 Change Data Capture Pipeline           | Process only changed records from source systems       |
| 16 | ⚡ Parallel Data Loading                   | Run pipelines in parallel for performance optimization |
| 17 | 📂 File Archiving Pipeline                | Move processed files into archive storage              |
| 18 | 🔐 Secure Pipelines with Key Vault        | Manage credentials using Azure Key Vault               |
| 19 | 📈 Large File Processing Strategy         | Process large datasets using partitioned ingestion     |
| 20 | 🏁 End-to-End Data Warehouse Pipeline     | Build a full ETL pipeline from ingestion to analytics  |

---

# ⚙️ Technologies Used

* Azure Data Factory ⚙️
* Azure Data Lake Storage 🗄
* Azure SQL Database 🛢
* REST APIs 🌐
* Azure Key Vault 🔐

---

# 🎯 Objective

This repository is created to:

* Practice **real-world ADF pipeline scenarios**
* Build reusable **data engineering pipeline patterns**
* Develop a **public data engineering portfolio**

---

# 👨‍💻 Author

**Livin Vincent**

Data Engineering | Databricks | Microsoft Fabric | PySpark

---

⭐ If you found this repository helpful, consider **starring it**.
