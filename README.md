# SQL Data Warehouse and Analytics Project

This repository contains an end-to-end SQL data warehouse project built from scratch.  
The objective is to design, implement, and query a modern data warehouse that supports analytical reporting and business insights.

The project follows industry-standard data engineering practices, including layered architecture, ETL pipelines, and dimensional modeling.

---

## Data Architecture

The data warehouse is designed using the **Medallion Architecture**, consisting of three logical layers.

<img src="docs/images/data_architecture.png" alt="Data Architecture" width="900">

- **Bronze Layer**
  - Stores raw data ingested from source systems
  - Data is loaded as-is from CSV files
  - No transformations applied

- **Silver Layer**
  - Cleaned and standardized data
  - Handles duplicates, missing values, and inconsistent formats
  - Prepares data for analytical modeling

- **Gold Layer**
  - Business-ready data for reporting and analytics
  - Star schema with fact and dimension tables
  - Optimized for analytical queries

---

## Project Overview

This project covers the full lifecycle of building a data warehouse:

- **Data Architecture Design**
  - Designing a scalable warehouse using Bronze, Silver, and Gold layers

- **ETL Development**
  - Extracting data from source files
  - Transforming data through multiple layers
  - Loading data into analytical tables using SQL

- **Data Modeling**
  - Creating fact and dimension tables
  - Supporting efficient querying and reporting

- **Analytics and Reporting**
  - Writing SQL queries to analyze business data
  - Generating insights on customers, products, and sales

This repository demonstrates practical skills in:
- SQL development
- Data warehousing concepts
- ETL pipeline design
- Dimensional data modeling
- Analytical querying

---

## Tools and Technologies

- **SQL Server** – Data warehouse database engine
- **Azure Data Studio / SSMS** – Database management and querying
- **CSV Files** – Source data inputs
- **Draw.io** – Architecture, data flow, and data model diagrams
- **Git & GitHub** – Version control and collaboration

---

## Project Requirements

### Data Engineering Objective

Build a modern SQL-based data warehouse that consolidates data from multiple source systems and supports analytical reporting.

### Specifications

- **Data Sources**
  - Two source systems (e.g., ERP and CRM) provided as CSV files

- **Data Quality**
  - Data is validated, cleaned, and standardized before analysis

- **Integration**
  - Data from all sources is integrated into a unified analytical model

- **Scope**
  - Focus on the latest dataset only
  - Historical tracking is out of scope

- **Documentation**
  - Clear documentation of architecture, data flow, and data models

---

## Analytics Objectives

Using the Gold layer data model, the project enables analysis of:

- Customer behavior
- Product performance
- Sales trends

All analytics are performed using SQL queries designed for reporting and decision support.

---
