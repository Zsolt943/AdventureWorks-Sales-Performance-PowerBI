# AdventureWorks – Sales Performance Analysis

## Project Overview

This project focuses on analyzing sales performance using the **AdventureWorks2022** database and presenting key business insights through an interactive **Power BI dashboard**.

The goal is to explore sales trends, evaluate product performance, analyze regional results, and provide meaningful insights through data visualization and business intelligence techniques.

## Technologies & Tools

- **Microsoft Power BI** – Data visualization and interactive dashboards
- **DAX (Data Analysis Expressions)** – Calculated measures and business metrics
- **SQL Server** – Source database (AdventureWorks2022)
- **Star Schema** – Data modeling approach

## Data Model

The project uses a **Star Schema** data model.

- **Fact Table:** SalesOrderDetail
- **Dimension Tables:**
  - Product
  - ProductSubcategory
  - ProductCategory
  - Customer
  - SalesTerritory
  - DateTable

This structure supports efficient analysis across different business dimensions, including products, customers, dates, and sales territories.

## Key DAX Measures

The following DAX measures were created to support the analysis:

| Measure | Description |
|---|---|
| Total Sales | Calculates total sales revenue. |
| Total Orders | Calculates the total number of unique orders. |
| Total Quantity Sold | Calculates the total quantity of products sold. |
| Average Order Value | Calculates the average value per order. |
| Previous Month Sales | Calculates sales from the previous month. |
| Monthly Sales Growth | Calculates the difference between current and previous month sales. |
| Monthly Sales Growth % | Calculates the percentage increase or decrease compared to the previous month. |

## Dashboard Pages

The Power BI report consists of four main analytical pages.

### 1. Executive Summary

Provides an overview of overall sales performance through:
- Key Performance Indicators (KPIs)
- Sales trends
- Top 10 products
- Sales by territory

### 2. Sales Trends

Focuses on sales evolution and monthly performance:
- Monthly sales trends
- Monthly sales growth
- Monthly sales growth percentage
- Current vs. previous month sales comparison

### 3. Product Performance

Analyzes product and category performance:
- Sales by product category
- Sales by product subcategory
- Sales vs. quantity analysis
- Product and category filtering

### 4. Regional Performance

Evaluates sales performance across different geographical areas:
- Sales by territory
- Quantity sold by territory
- Regional sales distribution
- Territory-based filtering

## Interactivity & Analysis

The report includes interactive filters and visualizations that allow users to explore the data from different perspectives.

Users can analyze sales performance by:
- Product category
- Individual products
- Sales territories
- Time periods

The interactive elements make it easier to identify trends, compare performance, and explore business results.

## Project Files

- `Project Kovacs Zsolt.pbix` – Power BI report containing the data model, DAX measures, and interactive dashboards.
- `README.md` – Project documentation.

## Author

**Zsolt Kovács**

Business Informatics Graduate | Database Master's Student

Interested in Data Analytics, Business Intelligence, SQL, Python, and Data Visualization.
