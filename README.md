# 🧠 Data Warehouse and Analytics Project

Welcome to my **Data Warehouse and Analytics Project**! 🚀  
This repository showcases a complete data engineering and analytics solution—taking raw data from source files, transforming it through structured ETL pipelines, and delivering business-ready insights via a modern, scalable data warehouse.  

Built as a personal portfolio project, this work reflects my practical skills in designing data pipelines, modeling data for analytics, and generating insights that drive informed decisions.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** approach, organizing data into three key layers:

![data_architecture](https://github.com/user-attachments/assets/06be6a68-ebeb-478a-b10e-5f1c125c106d)

1. **Bronze Layer**: Ingests raw CSV data into a SQL Server database—preserving source fidelity.  
2. **Silver Layer**: Cleans, normalizes, and transforms data—readying it for analytics.  
3. **Gold Layer**: Models business-friendly data using a star schema—optimized for reporting and analysis.

---

## 📖 Project Overview

This project includes:

- **Data Architecture**: Implementing Medallion-style warehousing with Bronze, Silver, and Gold layers  
- **ETL Pipelines**: Building structured SQL-based pipelines for extraction, transformation, and loading  
- **Data Modeling**: Designing fact and dimension tables using star schema best practices  
- **Analytics & Reporting**: Writing analytical queries to deliver real insights on sales, customers, and products

---

### 🔍 Why This Project Matters

This repository reflects my hands-on experience and passion for working with data. It highlights my strengths in:

- SQL Development  
- Data Architecture & Modeling  
- Data Engineering & ETL Pipelines  
- Analytical Thinking & Insight Generation  

Whether you're a fellow data enthusiast, a recruiter, or just exploring, I hope this project gives you a sense of my capabilities and approach to solving real-world data challenges.

---

## 🚀 Project Requirements

### 🏗️ Data Engineering

**Goal**: Build a modern SQL Server data warehouse to consolidate ERP and CRM data for analysis.

**Key Specs**:

- **Data Sources**: CSV files from ERP and CRM systems  
- **Data Quality**: Clean and normalize the data to resolve inconsistencies  
- **Integration**: Merge the systems into one analytical model  
- **Scope**: Work with the most recent data only (no historical tracking)  
- **Documentation**: Provide detailed documentation for business and analytics teams

---

### 📊 Analytics & Reporting

**Goal**: Generate SQL-based insights to support business decisions.

**Focus Areas**:

- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights help translate data into strategy for decision-makers.

---

## 📂 Repository Structure
data-warehouse-project/
│
├── datasets/ # Raw ERP and CRM CSV files
│
├── docs/ # Documentation and architecture diagrams
│ ├── data_architecture.png # Overall project architecture
│ ├── data_catalog.md # Field definitions and metadata
│ ├── data_flow.png # Data movement diagram
│ ├── data_models.png # Star schema visualizations
│ ├── naming-conventions.md # Standards for consistency
│
├── scripts/ # SQL scripts for each layer
│ ├── bronze/ # Raw data loading
│ ├── silver/ # Cleaning and standardizing
│ ├── gold/ # Star schema creation
│
├── tests/ # Data validation and quality checks
│
├── README.md # Project overview and instructions
