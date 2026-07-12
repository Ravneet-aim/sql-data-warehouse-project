# 🚀 Project Requirements

## Building the Data Warehouse (Data Engineering)

### Objective

Develop a modern SQL Server Data Warehouse to consolidate sales data from multiple source systems, enabling efficient reporting, analytics, and data-driven decision-making.

### Specifications

- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Clean and resolve data quality issues before loading data into the warehouse.
- **Integration:** Combine both sources into a unified data model designed for analytical reporting.
- **Scope:** Focus only on the latest dataset; historical data loading is not required.
- **Documentation:** Provide clear documentation of the data model and ETL process to support developers and business stakeholders.

---

# 📊 BI: Analytics & Reporting (Data Analytics)

## Objective

Develop SQL-based analytical models and reporting views to generate business insights into:

- Customer Behavior
- Product Performance
- Sales Trends
- Revenue Analysis
- Regional Performance

# 🏗️ Data Architecture

The project follows the **Medallion Architecture**, consisting of Bronze, Silver, and Gold layers.

![Data Architecture]("C:\Users\Friends\Downloads\data_architecture.drawio (1).png")

### Bronze Layer

Stores raw data exactly as received from the source systems.

- Load ERP and CRM CSV files
- No transformations
- Raw data storage
- Batch processing
- Truncate & Load strategy

### Silver Layer

Transforms raw data into clean, standardized datasets.

- Data Cleaning
- Standardization
- Duplicate Removal
- Null Handling
- Data Validation
- Data Enrichment

### Gold Layer

Provides business-ready data for reporting and analytics.

- Star Schema
- Fact Tables
- Dimension Tables
- Aggregated Views
- Business Metrics

Data from this layer is consumed by:

- Power BI
- Tableau
- SQL Queries
- Machine Learning Models

---

# 📁 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                         # Raw datasets (ERP & CRM)
│
├── docs/                             # Documentation
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
|   ├── data_integration_model.drawio
│   ├── data_model.drawio
│   ├── naming_conventions.md
│  
│
├── scripts/
│   ├── bronze/                       # Raw data loading scripts
│   ├── silver/                       # Data cleansing & transformation
│   └── gold/                         # Analytical models
│
├── tests/                            # Testing scripts
│
├── README.md
├── LICENSE

```

---

# 🛡️ License

This project is licensed under the **MIT License**.

You are free to use, modify, distribute, and share this project with proper attribution.

---

# 👨‍💻 About Me

Hi! I'm **Ravneet Kaur**, an aspiring **Data Engineer** and **Data Analyst** passionate about designing scalable data pipelines, building data warehouses, and creating meaningful business insights through analytics.

I enjoy working with:

- SQL Server
- Python
- Power BI
- ETL Pipelines
- Data Warehousing
- Data Modeling
- Business Intelligence

I'm continuously learning and building real-world projects to strengthen my skills in Data Engineering and Analytics.

---

# 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/jobs/search-results/?currentJobId=4411407609&eBP=CwEAAAGfVww1lExccRFcJQ4-vXaH6W-eUaMu_okyvjZzWWU-UuebKjvAqGAsNuBPElcnmVsEYyv7N4inoJOFxcnoQIjjyB5JQTHGavX7PTYA9dlJuPZ9oV5DkbQlI6dvXnaP7WK-_2uDRLL5Ujmqs9HRYSZGQ2YEru7klpd0AsiUl7QyAm4WEoiu4qLTYHC0YU6DHq4EjSJd99tT65g7oqpsVTu6A8W0aSZVVjYAJKI1YAoUxqG2k4bOF8WajgAEunTadeHpgXoybmLB_8Dq59oPjgDazm3Re7_4xjIvSE3dubkSmL1dfpHwB42-z40_KVQ7GvzbOmhE9HUOH5WK9_fHkTCrG_CSs0wWljq_usDhF-9XuRS2aXx1zJrM1K25z1moXf1RbQszGghIsTUCqa2pmwxuDluwXjTYV0ygvX4vA3_i9tfT-mrOzDuQBTOsF9fLXcnw4o0M6fnvHxhkFsIOemaD2rmI9EW1k3cwdoF5suIfeTq9sbhfVwbnUvCtqNAOaYsEl7GE&refId=ceo9VxdAvXNhvnr1vlVTZw%3D%3D&trackingId=adOY9VklmJd609gwf2DOjg%3D%3D&keywords=Data%20Analyst%20intern&origin=JOBS_HOME_KEYWORD_HISTORY&geoId=103644278&distance=0.0)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ravneet-aim)


