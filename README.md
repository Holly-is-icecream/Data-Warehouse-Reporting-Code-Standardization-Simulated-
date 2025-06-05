# Data Warehouse Reporting Code Standardization (Simulated)

## Project Overview

This project simulates a real-world reporting pipeline for a data warehouse environment. It includes a standardized SQL reporting structure, technical requirement documentation (TRD), and optional Python-based data visualizations.

The goal is to showcase my ability to:
- Design and execute analytical queries with clean and maintainable SQL code
- Document business logic in a Technical Requirement Document (TRD)
- Apply reporting best practices, such as consistent naming conventions and field definitions
- Communicate insights visually through Python

---

## Dataset Description

The dataset used in this project simulates a simplified e-commerce system and includes the following four tables:

| Table Name      | Description              |
|-----------------|--------------------------|
| `customers`     | Customer demographic info |
| `orders`        | Order header with dates   |
| `order_items`   | Order line items          |
| `products`      | Product catalog           |

---

## Report Focus: Monthly Sales Summary

This report shows:
- Total revenue per month
- Total number of unique orders per month

The SQL query was written with standardized naming conventions and inline comments to ensure maintainability and clarity.

---

## Files Included

```bash
📂 data_warehouse_reporting_standardization/
├── 📁 data/
│   └── *.csv                        # Raw data files
├── 📁 sql/
│   └── monthly_sales_summary.sql   # Standardized SQL query
├── 📁 docs/
│   └── monthly_sales_summary_TRD.md  # Technical Requirement Document
├── 📁 notebooks/
│   └── monthly_sales_summary_analysis.ipynb  # (Optional) Python visualization
└── README.md
