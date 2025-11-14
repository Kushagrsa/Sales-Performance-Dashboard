 📊 Tableau Dashboard: Sales Performance Dashboard

This repository contains the Tableau workbook and supporting files for the Sales Performance dashboard.  
The interactive version is hosted on Tableau Public and can be viewed here:

👉 **Interactive Dashboard:** (https://public.tableau.com/views/SalesPerformanceDashboard_17631254109000/SalesDashboard?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


🧭 Overview

This project focuses on designing and developing an interactive Sales Performance Dashboard in Tableau. The primary objective is to enable stakeholders—including sales managers and executives—to monitor and analyze sales performance, identify trends, and make data-driven decisions.
The dashboard consolidates key sales metrics such as total sales, profit, and quantity sold, and presents them across various time periods, categories, and geographies.
The Sales Dashboard aims to present an overview of sales metrics and trends for analyzing year-over-year performance and understanding sales behavior patterns


🔍 Key Insights

- Provided visibility into top-performing months and products
- Helped identify seasonal sales patterns.
- Enabled stakeholders to track profitability alongside sales volume.
- Simplified analysis through interactivity and visual clarity.


🛠️ Files in This Repository

| File | Description |
|------|-------------|
| `Sales Performance Dashboard.twbx` | Packaged Tableau workbook (recommended for download) |
| `README.md` | Documentation for the project |


📁 Data Sources

1. Customers Dataset (Customers.csv)

Contains unique customer information.
Fields include: Customer ID, Customer Name
Purpose: Used to identify customers and segment sales by customer-level attributes.

2. Products Dataset (Products.csv)
   
Provides detailed information for each product sold.
Fields include: Product ID, Category, Sub-Category, Product Name
Purpose: Enables analysis of sales and profit across product categories and subcategories.

3. Location Dataset (Location.csv)

Includes geographic details of orders.
Fields include: Region, State, City, Postal Code
Purpose: Supports regional, state-level, and city-level performance analysis.

4. Orders Dataset (Orders.csv)

The core transactional dataset contains individual sales records.


🧪 Methodology

The Sales Performance Dashboard was developed using a structured and systematic approach to ensure accuracy, clarity, and usability. The workflow follows key principles of data analytics and business intelligence (BI), with Tableau as the primary tool. The methodology is organized into five interconnected phases:

1. Requirement Analysis

This phase focuses on understanding business needs and defining the metrics required for evaluating sales performance. Discussions around the problem statement help clarify objectives such as tracking total sales, profit, quantity sold, and year-over-year (YoY) trends. Scope, user expectations, and available data sources are also identified at this stage.

2. Data Collection and Preparation

Sales and product datasets are collected—typically in CSV or Excel format—and prepared for analysis. This includes cleaning, validating, and transforming the data to ensure accuracy and consistency. Key fields such as Order Date, Category, Sub-Category, Region, Sales, and Profit are verified before importing into Tableau.

Key Tasks:

-> Cleaning and structuring data in Excel/CSV
-> Importing datasets into Tableau
-> Assigning correct data types and building hierarchies
-> Creating calculated fields (Profit Ratio, YoY Growth, Weekly Averages, etc.)

3. Visualization Development

With the data model ready, individual visualizations (worksheets) are created in Tableau. Each component focuses on a specific analytical objective, contributing to a comprehensive view of sales performance.

4. Dashboard Design and Integration

All visual components are combined into an interactive dashboard. Visual layout, navigation, and interactivity are optimized to ensure an intuitive user experience. Filters, parameters, and action controls are implemented to support exploratory analysis.

5. Testing and Validation

The final phase ensures the dashboard is accurate, responsive, and user-friendly. Data calculations are cross-checked with original datasets, and the performance of filters, parameters, and navigation controls is validated.

🎨 Dashboard Features

- Region/category filters  
- Dynamic KPIs  
- Interactive drill-downs  
- Custom tooltips  
- Year, quarter, and month selectors  
- Actions (filter, highlight, URL action, etc.)


🚀 How to Use

If someone wants to open the workbook locally:

1. Download the `.twbx` file from this repository  
2. Open it with Tableau Desktop or Tableau Public (free)  
