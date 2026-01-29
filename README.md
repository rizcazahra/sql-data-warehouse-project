# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project repository.**
This project showcases a data warehousing and analytics solution, covering the development of a data warehouse and the generation of meaningful insights. It is designed as a portfolio project to demonstrate industry best practices in data engineering and analytics.

🏘️ Data Architecture
The project’s data architecture is structured using the Medallion Architecture, with data organized across Bronze, Silver, and Gold layers:
<img width="851" height="624" alt="image" src="https://github.com/user-attachments/assets/dc80b595-1cf0-4413-9246-1d7129ba566e" />

1. **Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer:** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.

🧩 Project Requirements
This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
2. **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

## 🚀 Project Requirements
### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using Docker to consolidate sales data, enabling analyticalreporting and informed decison-making.

#### Spesifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provides as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### BI: Analytics & Reporting (Data Analysis)

#### Objective

Develop SQL-based analytics to deliver detailed insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.
