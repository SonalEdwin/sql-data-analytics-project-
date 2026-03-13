# 📊 SQL Data Analytics Project

## 🧠 Overview

This project demonstrates comprehensive data exploration and analytical reporting using SQL on a retail-style transactional database. It transforms raw sales data into meaningful business insights through structured queries, aggregations, segmentation, and performance analysis.



---

## 🎯 Objectives

* Explore and validate relational datasets
* Generate key business metrics and KPIs
* Analyse sales trends over time
* Evaluate product and customer performance
* Perform segmentation and contribution analysis
* Build reusable analytical views for reporting

---

## 🗂️ Repository Structure

```
sql-data-analytics-project/
│
├── datasets/
│   └── csv-files/
│       ├── gold.dim_customers.csv
│       ├── gold.dim_products.csv
│       └── gold.fact_sales.csv
│       └── gold.fact_sales.csv
│       └── gold.report_customers.csv
│       └── gold.report_products.csv
│
├── scripts/
│   ├── database_exploration.sql
│   ├── dimension_exploration.sql
│   ├── data_range_exploration.sql
│   ├── measures_exploration.sql
│   ├── magintude_analysis.sql
│   └── ranking_analysis.sql
│   ├── change_over_time_analysis.sql
│   ├── cumulative_analysis.sql
│   ├── performance_analysis.sql
│   ├── data_segmentation.sql
│   └── report_customers.sql
│   └── report_products.sql
│
└── README.md
```

---

## 📈 Key Analyses Performed

### 🔍 Database Exploration

* Schema inspection
* Dimension and fact table exploration
* Data range validation
* Measures and summary statistics

### ⏳ Time-Based Analysis

* Monthly and yearly trends
* Seasonal patterns
* Growth analysis

### 🔄 Cumulative Analytics

* Running totals
* Moving averages
* Performance tracking over time

### 🏆 Performance Analysis

* Product sales performance over time
* Year-over-Year comparisons
* Deviation from average performance

### 🧩 Segmentation

Product Segmentation
Products grouped into cost ranges:
* Below 100
* 100–500
* 500–1000
* Above 1000
  
Customer Segmentation
Customers classified based on spending and activity:
* VIP — Long history & high spending
* Regular — Long history & lower spending
* New — Short purchase history

### 📑 Reporting Views

Customer Report
Aggregates customer-level insights including:
* Total orders
* Total spending
* Quantity purchased
* Products purchased
* Customer lifespan
* Recency
* Age and age group
* Customer segment (VIP / Regular / New)
* Average order value
* Average monthly spend

Product Report
Summarizes product performance metrics:
* Total orders and sales
* Quantity sold
* Unique customers
* Product lifespan
* Recency
* Average selling price
* Revenue-based product segmentation
* Average order revenue
* Average monthly revenue
---

## 🛠️ Tools & Technologies

* **SQL**
* Relational Database Concepts
* Analytical Query Techniques
* Window Functions & Aggregations

---

## 🚀 How to Use

1. Import the CSV datasets into your SQL database
2. Rename tables if needed to match script references
3. Execute scripts in sequence:
   * Exploration scripts
   * Analytical scripts
   * Segmentation analysis
   * Reporting view creation
4. Modify queries as needed for your database system

---

## 💡 Skills Demonstrated

* Data exploration & cleaning
* Business analytics using SQL
* Advanced aggregations
* Time-series analysis
* Window functions
* KPI development
* Analytical thinking
* Query optimization concepts

---

## ⭐ Project Purpose

This project is part of my portfolio to demonstrate practical SQL skills for Data Analyst, BI, and Data Science roles.

---

