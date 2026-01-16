# Data Warehouse and Analytics Project


Welcome to the **Data Warehouse and Analytics Project repository!** 🚀

This project showcases an end-to-end data warehousing and analytics solution, from warehouse development to actionable insight generation.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

![Data Architecture](docs/data_architecture.png)

1.  **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2.  **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3.  **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a modern data warehouse using the Medallion Architecture with Bronze, Silver, and Gold layers.
2. **ETL Pipelines**: Building automated pipelines to extract, transform, and load data from source systems into the warehouse.
3. **Data Modeling**: Creating optimized fact and dimension tables to support high-performance analytical queries.
4. **Analytics & Reporting**: Developing SQL-driven reports and dashboards to deliver actionable business insights.

---
## 🚀 Project Requirements
### Building the Data Warehouse
#### Objective
Build a modern SQL Server data warehouse to centralize sales data and support advanced analytics and data-driven decision-making.
#### Specifications
- **Data Sources**: Import data from ERP and CRM systems provided as CSV files.
- **Data Quality**: Perform data cleansing and resolve quality issues to ensure accurate analysis.
- **Integration**: Merge both sources into a unified, analytics-ready data model.
- **Scope**: Analyze only the most recent dataset; historical data tracking was not included.
- **Documentation**: Create clear and accessible documentation of the data model for business stakeholders and analytics teams.
