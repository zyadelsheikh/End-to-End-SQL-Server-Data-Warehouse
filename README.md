# SQL Data Warehouse Project

Welcome to my **SQL Data Warehouse Project** repository.

In this project, I built a simple data warehouse using **SQL Server** to practice core data engineering concepts such as data ingestion, transformation, and data modeling.

The goal of this project is to take raw data from different source systems and organize it into a structured warehouse that can be used for analysis and reporting.

---

# 🏗️ Data Architecture

The project follows a simple **Medallion Architecture** with three layers:

**Bronze Layer**

This layer stores the raw data exactly as it comes from the source systems.
The data is loaded from CSV files into SQL Server without major changes.

**Silver Layer**

In this stage, the data is cleaned and standardized.
Basic transformations are applied to fix formatting issues and improve data quality.

**Gold Layer**

This layer contains business-ready tables designed for analytics and reporting.
The data is structured using fact and dimension tables.

---

# 📖 Project Overview

This project includes several main steps:

**Data Architecture**

Designing the structure of the data warehouse using the Bronze, Silver, and Gold layers.

**ETL Pipelines**

Loading the data from source files, transforming it, and storing it inside the warehouse.

**Data Modeling**

Creating fact and dimension tables that support analytical queries.

**Analytics & Reporting**

Running SQL queries to analyze the data and extract useful business insights.

---

# 🚀 Project Requirements

## Building the Data Warehouse (Data Engineering)

### Objective

Build a SQL Server data warehouse that integrates sales data from multiple systems and prepares it for analysis.

### Specifications

**Data Sources**

Data is loaded from two systems (ERP and CRM) provided as CSV files.

**Data Quality**

Data is cleaned by handling missing values and fixing inconsistencies.

**Integration**

Data from both sources is combined into one structured model.

**Scope**

The project focuses on the latest dataset and does not include historical tracking.

**Documentation**

Basic documentation is provided to explain the data model and the relationships between tables.

---

# 📊 BI: Analytics & Reporting

## Objective

Use SQL queries to analyze the data stored in the warehouse and generate useful insights.

## Analytics Focus

The analysis focuses mainly on:

* Customer behavior
* Product performance
* Sales trends

These insights help understand business performance and support decision-making.

---

# 📂 Repository Structure

```
sql-datawarehouse-project
│
├── datasets        # Source CSV files (ERP & CRM data)
│
├── docs            # Diagrams and project documentation
│
├── scripts         # SQL scripts used to build the warehouse
│   ├── bronze
│   ├── silver
│   └── gold
│
├── tests           # Data quality checks
│
├── README.md
└── LICENSE
```

---

# 🛠️ Tools Used

The main tools used in this project:

* SQL Server
* SQL Server Management Studio (SSMS)
* Draw.io (for diagrams)
* Git & GitHub

---

# 🛡️ License

This project is licensed under the **MIT License**.

---

# 👨‍💻 About Me

Hi, I'm **Zyad Elsheikh**.

I'm currently learning **Data Engineering** and building projects to practice SQL, data warehousing, and data modeling concepts.

This project is part of my learning journey to better understand how modern data warehouses are designed and implemented.
