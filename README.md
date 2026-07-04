# 📊 Data Warehouse & Analytics Project

A complete **Data Warehouse and Analytics** solution built using **SQL Server** following the **Medallion Architecture (Bronze → Silver → Gold)**.

This project demonstrates industry-standard data engineering practices, including data ingestion, transformation, dimensional modeling, and SQL-based analytics for business intelligence.

---

# 🚀 Project Overview

This project covers the complete lifecycle of a modern data warehouse.

### ✅ Key Features

- Build a SQL Server Data Warehouse
- Design a Medallion Architecture
- Develop ETL Pipelines
- Clean and Transform Data
- Create Fact & Dimension Tables
- Generate Business Insights using SQL
- Follow Industry Best Practices

---

# 🏗️ Data Architecture

The project follows the **Medallion Architecture**, consisting of three layers.

![Data Architecture](docs/data_architecture.png)

### 🥉 Bronze Layer

- Stores raw data exactly as received
- Loads CSV files into SQL Server
- No transformations

### 🥈 Silver Layer

- Cleanses data
- Standardizes formats
- Removes duplicates
- Resolves data quality issues

### 🥇 Gold Layer

- Business-ready data
- Star Schema
- Optimized for reporting and analytics

---

# 📌 Project Objectives

## Data Engineering

Develop a modern SQL Server data warehouse that:

- Consolidates CRM and ERP datasets
- Cleans and transforms raw data
- Builds an analytical data model
- Supports scalable reporting

---

## Data Analytics

Generate SQL reports to analyze:

- 👥 Customer Behavior
- 📦 Product Performance
- 📈 Sales Trends
- 💰 Revenue Insights

---

# ⚙️ Tech Stack

| Category | Tools |
|----------|-------|
| Database | SQL Server Express |
| Query Tool | SQL Server Management Studio (SSMS) |
| Language | SQL |
| Data Sources | CSV Files |
| Documentation | Draw.io |
| Version Control | Git & GitHub |

---

# 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/
│   ├── crm/
│   └── erp/
│
├── docs/
│   ├── data_architecture.drawio
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── etl.drawio
│   ├── data_catalog.md
│   └── naming-conventions.md
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt
```

---

# 🔄 ETL Pipeline

```
CSV Files
      │
      ▼
Bronze Layer
      │
      ▼
Silver Layer
      │
      ▼
Gold Layer
      │
      ▼
Analytics & Reporting
```

---

# 📊 Data Sources

The project integrates data from two operational systems.

| Source | Description |
|---------|-------------|
| CRM | Customer Information |
| ERP | Product & Sales Information |

---

# 📈 Analytics

The Gold Layer enables analytical reporting on:

- Sales Performance
- Customer Segmentation
- Product Analysis
- Revenue Trends
- Business KPIs

---

# 📋 Project Requirements

## Data Warehouse

### Objective

Build a centralized SQL Server data warehouse for analytical reporting.

### Requirements

- Import CRM & ERP CSV datasets
- Clean inconsistent data
- Merge both systems
- Create analytical tables
- Document the data model

---

## Business Analytics

Create SQL queries to provide insights into:

- Customer Behavior
- Product Performance
- Sales Trends
- Revenue Growth

---

# 🛠️ Tools Used

- SQL Server Express
- SQL Server Management Studio (SSMS)
- Git
- GitHub
- Draw.io
- Notion

---

# 🎯 Skills Demonstrated

- SQL Development
- Data Warehousing
- ETL Pipeline Design
- Data Cleaning
- Data Modeling
- Star Schema Design
- Business Analytics
- Database Design

---

# 📚 Learning Outcomes

This project demonstrates practical experience in:

- Building a Modern Data Warehouse
- Implementing Medallion Architecture
- Writing SQL ETL Pipelines
- Creating Analytical Data Models
- Generating Business Insights

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
