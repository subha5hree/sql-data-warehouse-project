# SQL Data Warehouse

A modern SQL-based data warehouse project designed to integrate, transform, and organize data from multiple sources for analytics and reporting.

## 📌 Overview

This project demonstrates the end-to-end process of building a data warehouse using SQL, from loading raw data to transforming it into clean, structured, and analytics-ready datasets.

The warehouse follows a layered architecture to improve data quality, maintainability, and reporting performance.

## 🏗️ Architecture

![data_architecture](docs)

## 🎯 Objectives

- Build a centralized SQL data warehouse
- Integrate data from multiple source systems
- Clean and transform raw data
- Implement ETL/ELT processes
- Apply dimensional data modeling
- Create fact and dimension tables
- Improve data quality and consistency
- Enable analytics and reporting

## 🛠️ Technologies

- SQL
- ETL / ELT
- Data Modeling

## 📂 Project Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_architecture               # png file shows the project's architecture
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── LICENSE                             # License information for the repository
├── README.md                           # Project overview and instructions
```

## 🔄 Data Pipeline

### 1. Bronze Layer

The Bronze layer stores raw data as received from the source systems.

Responsibilities:

- Store raw data
- Preserve the original source data
- Perform minimal transformations
- Provide a reliable landing layer

### 2. Silver Layer

The Silver layer cleans and transforms the raw data.

Responsibilities:

- Remove duplicates
- Handle missing values
- Standardize data formats
- Validate data
- Apply data transformations
- Improve data quality

### 3. Gold Layer

The Gold layer contains business-ready datasets optimized for analytics and reporting.

Responsibilities:

- Create fact tables
- Create dimension tables
- Apply business logic
- Create analytical views
- Prepare data for reporting


## 🧹 Data Quality

The project includes data-quality checks such as:

- Duplicate detection
- NULL value validation
- Data type validation
- Referential integrity checks
- Invalid value detection
- Uniqueness checks

## 📈 Analytics

The data warehouse can be used to answer business questions such as:

- What are the top-selling products?
- Which customers generate the most revenue?
- What are the monthly sales trends?
- Which regions perform best?
- What is the average order value?
- Which products are growing or declining?
- What are the key business performance metrics?


## 📚 Key Concepts Demonstrated

- Data Warehouse Architecture
- ETL / ELT Pipelines
- SQL Data Transformation
- Data Cleaning
- Dimensional Modeling
- Star Schema
- Fact Tables
- Dimension Tables
- Data Quality Testing
- Analytical SQL
