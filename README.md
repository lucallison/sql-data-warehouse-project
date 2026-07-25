# Data Warehouse and Analytics Project

You are welcome to the **Data Warehouse and Analytics Project** repository.

This project showcases a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. It is designed as a portfolio project to demonstrate strong data engineering and data analytics capabilities.

#### 🎯Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

## 🚀Project Requirements
This project demonstrates the end-to-end design and implementation of a modern data warehouse, with a focus on scalable architecture, efficient data integration, and business intelligence. 
Key components include:
- **Data Architecture:** Designed a modern data warehouse using the Medallion Architecture, implementing Bronze, Silver, and Gold layers to organize and refine data through each stage of processing.
- **ETL Development:** Built ETL pipelines to extract data from source systems, transform it into a standardized format, and load it into the data warehouse.
- **Data Modeling:** Designed and implemented fact and dimension tables using dimensional modeling techniques to support high-performance analytical queries.
- **Analytics & Reporting:** Developed SQL-based reports and dashboards that deliver actionable insights and support data-driven decision-making.

### 🏗️Building the Data Warehouse
The **data architecture** for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
https://github.com/lucallison/sql-data-warehouse-project/blob/main/docs/data_architecture.png
- *Bronze Layer*: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
- *Silver Layer*: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
- *Gold Layer*: Houses business-ready data modeled into a star schema required for reporting and analytics.

#### 📋Specifications
- **Data Sources**: Import data from two different sources (ERP and CRM) provided as csv files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)
#### 🎯Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**
These insights empower stakeholders with key business metrics, enabling strategic decision-making.


---

## ⚖️License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🧑‍💻About Me

Hi there! I'm **Luc Alli**. I am an IT professional holding a Bachelor’s degree in Biomedical Engineering and a Master’s
degree in Information Technology with a concentration in Business Administration.
































 Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

