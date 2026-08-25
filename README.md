# MegaMart Supermarket Data Engineering & BI Project

## 📌 Project Overview

MegaMart is an end-to-end data engineering and business intelligence project developed using Databricks, Python, SQL, and Power BI.

The project simulates a supermarket chain and demonstrates the complete data pipeline from data generation and ingestion to data validation, transformation, analytical processing, and business dashboard development.

The final solution provides insights into:

- Retail store performance
- Sales trends and product performance
- Inventory levels and turnover
- Supplier delivery performance
- Procurement and reorder requirements

---

## 🏗️ Project Architecture

```text
Sample / Raw Data
       ↓
Databricks
       ↓
Data Generation & Ingestion
       ↓
Data Validation
       ↓
Data Cleaning & Transformation
       ↓
Analytical Tables
       ↓
Business Analysis
       ↓
Power BI
       ↓
Interactive Dashboards
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Databricks | Data engineering and analytics |
| Python | Data generation and transformation |
| PySpark | Data processing |
| SQL | Analytical queries and transformations |
| Delta / Databricks Tables | Data storage |
| Power BI | Business intelligence and visualization |
| GitHub | Version control and project management |

---

## 📂 Project Structure

```text
megamart-data-engineering/
│
├── notebooks/
│   ├── 00_setup.ipynb
│   ├── 01_generate_data.ipynb
│   ├── 02_data_ingestion.ipynb
│   ├── 03_data_validation.ipynb
│   ├── 04_sales_analysis.ipynb
│   ├── 05_inventory_analysis.ipynb
│   ├── 06_inventory_optimizer.ipynb
│   └── 07_store_kpis.ipynb
│
├── powerbi/
│   └── MegaMart_Dashboard.pbix
│
├── report/
│   └── MegaMart_Project_Report.docx
│
├── screenshots/
│   ├── retail_store_analysis.png
│   ├── sales_analysis.png
│   ├── inventory_supply_chain.png
│   └── MegaMart_Dashboard_Screenshots.pdf
│
├── generate_sample_data.py
│
└── README.md
```

---

# 📊 Dashboard Preview

## 🏪 Retail Store Analysis

The Retail Store Analysis dashboard provides an overview of store-level business performance.

### Dashboard

![Retail Store Analysis](screenshots/retail_store_analysis.png)

### Key Metrics

- Total Revenue
- Total Transactions
- Average Transaction Value
- Unique Products Sold
- Revenue by Store
- Market Share by Store
- Store Performance Overview

---

## 📈 Sales Analysis

The Sales Analysis dashboard focuses on sales trends and product performance.

### Dashboard

![Sales Analysis](screenshots/sales_analysis.png)

### Key Insights

- Monthly Revenue Trend
- Revenue by Product Category
- Top 5 Products by Quantity Sold
- Product Revenue Performance

---

## 📦 Inventory & Supply Chain

The Inventory & Supply Chain dashboard focuses on inventory health, procurement, and supplier performance.

### Dashboard

![Inventory & Supply Chain](screenshots/inventory_supply_chain.png)

### Key Metrics

- Out of Stock Products
- Low Stock Products
- Reorder Required
- Inventory Turnover by Store
- Supplier On-Time Delivery Rate
- Supplier Average Delivery Time
- Procurement Status

---

# 🔄 Data Engineering Workflow

## 1. Data Generation

Sample supermarket data is generated for products, stores, suppliers, sales transactions, and inventory.

The project includes a Python data-generation script and a dedicated Databricks notebook for generating the project data.

---

## 2. Data Ingestion

The generated data is loaded into Databricks for further processing and analysis.

The ingestion process prepares the raw datasets for downstream analytical workflows.

---

## 3. Data Validation

The project performs data validation checks to identify potential data quality issues.

Validation includes checks for:

- Missing values
- Duplicate records
- Invalid values
- Schema consistency
- Data completeness

---

## 4. Data Transformation

The validated datasets are transformed into analytical datasets suitable for business analysis.

These transformations prepare the data for sales, inventory, supplier, and store-level analysis.

---

## 5. Sales Analysis

Sales data is analyzed to understand:

- Revenue trends
- Transaction volumes
- Product categories
- Top-selling products
- Store-level revenue

---

## 6. Inventory Analysis

Inventory data is analyzed to identify:

- Out-of-stock products
- Low-stock products
- Inventory turnover
- Reorder requirements

---

## 7. Inventory Optimization

The inventory optimization workflow evaluates stock levels and helps identify products that may require:

- Reordering
- Urgent reordering
- No action

This provides a practical approach to inventory and procurement decision-making.

---

## 8. Store KPI Analysis

Store-level KPIs are calculated to evaluate the performance of individual MegaMart stores.

The analysis includes metrics such as:

- Revenue
- Transactions
- Average transaction value
- Unique products
- Market share
- Store ranking

---

## 9. Business Intelligence

The analytical datasets created in Databricks are connected to Power BI.

Power BI is used to create interactive dashboards that allow business users to understand sales, store performance, inventory, and supply-chain metrics.

---

# 📊 Power BI Dashboards

The project contains three major dashboard pages.

### 1. Retail Store Analysis

Focuses on overall store performance and includes:

- Total Revenue
- Total Transactions
- Average Transaction Value
- Unique Products Sold
- Revenue by Store
- Market Share by Store
- Store Performance Overview

### 2. Sales Analysis

Focuses on sales and product performance and includes:

- Monthly Revenue Trend
- Revenue by Product Category
- Top 5 Products by Quantity Sold
- Product Revenue Performance

### 3. Inventory & Supply Chain

Focuses on inventory management and supplier performance and includes:

- Out of Stock Products
- Low Stock Products
- Reorder Required
- Inventory Turnover by Store
- Supplier On-Time Delivery Rate
- Supplier Average Delivery Time
- Procurement Status

---

# 📈 Key Business Insights

The dashboards provide management with visibility into:

- Store revenue performance
- Market share distribution across stores
- Monthly sales trends
- High-performing product categories
- Best-selling products
- Inventory turnover
- Stock availability
- Reorder requirements
- Supplier delivery performance

These insights can support better operational and inventory-related decision-making.

---

# 🎯 Business Objectives

The primary objective of the project is to demonstrate how a retail organization can use a modern data engineering and business intelligence workflow to transform raw operational data into actionable business insights.

The solution helps decision-makers answer questions such as:

- Which stores generate the most revenue?
- Which stores have the highest market share?
- What are the monthly revenue trends?
- Which product categories perform best?
- Which products sell the most?
- Which products require reordering?
- Which stores have better inventory turnover?
- Which suppliers have better delivery performance?

---

# 💡 Project Highlights

### End-to-End Data Pipeline

The project covers the complete workflow from data generation to business visualization.

### Data Quality

Data validation is incorporated before analytical processing.

### Retail Analytics

Store, sales, product, inventory, and supplier data are analyzed together to provide a broader view of supermarket operations.

### Inventory Optimization

The project identifies stock conditions and generates procurement recommendations.

### Business Intelligence

Power BI dashboards transform analytical results into interactive visual insights.

### Version Control

The project is maintained in GitHub, making the development workflow reproducible and portfolio-ready.

---

# 📁 Project Documentation

The repository includes supporting project documentation and dashboard resources.

### Detailed Project Report

`report/MegaMart_Project_Report.docx`

The report contains detailed information about the project, methodology, implementation, analysis, and results.

### Dashboard Screenshots

`screenshots/MegaMart_Dashboard_Screenshots.pdf`

The PDF contains screenshots of the completed Power BI dashboards.

### Power BI Dashboard

`powerbi/MegaMart_Dashboard.pbix`

The Power BI project file contains the interactive dashboard implementation.

---

# 🚀 Project Outcome

The MegaMart project demonstrates an end-to-end retail analytics solution using modern data engineering and business intelligence tools.

The final workflow can be summarized as:

```text
Data Generation
      ↓
Data Ingestion
      ↓
Data Validation
      ↓
Data Transformation
      ↓
Sales & Inventory Analysis
      ↓
KPI & Optimization Analysis
      ↓
Power BI Dashboards
      ↓
Business Insights
```

The project provides a foundation for using data-driven approaches to improve retail store performance, sales analysis, inventory management, procurement planning, and supplier evaluation.

---

# 👩‍💻 Author

**Ishika Srivastava**

**Data Engineer – I**

---

## 🔗 Project Repository

The complete project source code, Databricks notebooks, Power BI dashboard, documentation, and dashboard screenshots are available in this repository.
