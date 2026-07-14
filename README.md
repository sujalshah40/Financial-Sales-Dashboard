# Financial-Sales-Dashboard


---

# Project Title

**Financial Sales Dashboard**

---

# Short Purpose

The Financial Sales Dashboard is an interactive Power BI dashboard designed to analyze sales, profit, product performance, and regional business trends.

The dashboard helps business users monitor key financial KPIs, compare country-wise sales performance, analyze monthly sales and profit trends, identify top-selling products, and evaluate the impact of discount bands on overall sales.

---

# Tech Stack

The dashboard was built using the following tools and technologies:

* **Power BI Desktop** — Main data visualization platform used for report creation.
* **Power Query** — Used for data cleaning, transformation, and data preparation.
* **DAX (Data Analysis Expressions)** — Used for calculated measures, KPIs, and business calculations.
* **Data Modeling** — Relationships created between Sales, Product, Date, and Country tables.
* **Excel / CSV Files** — Source data files used for analysis.
* **Slicers & Filters** — Used for interactive filtering by Country, Year, and Segment.

---

# Data Source

Source data used in the dashboard:

* Financial Sales dataset
* Product data
* Country data
* Sales transaction data
* Date table
* Discount Band information

Dataset includes business data from:

* United States
* Canada
* France
* Germany
* Mexico

---

# Data Cleaning & Transformation

Performed using **Power Query**:

* Removed null values
* Corrected data types
* Renamed columns
* Removed duplicate records
* Created calculated columns
* Standardized category values
* Prepared data for analysis

Examples:

* Profit Margin
* Discount Band
* Sales Amount
* Total Units Sold
* Monthly Sales
* Monthly Profit

---

# Data Modeling

Created a relational data model using:

* One-to-many relationships
* Star schema structure
* Shared lookup tables
* Date table for time intelligence

Tables connected:

* Sales
* Products
* Date
* Country

---

# DAX Measures Created

Important DAX measures used in the dashboard:

| Measure Name        | Purpose                                     |
| ------------------- | ------------------------------------------- |
| Total Sales         | Calculates total sales revenue              |
| Total Profit        | Calculates total business profit            |
| Profit Margin %     | Calculates profit percentage                |
| Total Units Sold    | Calculates total units sold                 |
| Monthly Sales       | Tracks monthly sales trend                  |
| Monthly Profit      | Tracks monthly profit trend                 |
| Sales by Country    | Calculates country-wise sales               |
| Product Sales       | Calculates sales by product                 |
| Discount Band Sales | Calculates sales based on discount category |

---

# Dashboard Features

### KPI Cards

* Total Profit
* Total Sales
* Profit Margin %
* Total Units Sold

### Interactive Visuals

* Sales vs Profit Trend
* Sales by Country Map
* Country-wise Sales Bar Chart
* Product-wise Sales Treemap
* Discount Band Sales Pie Chart

### Filters / Slicers

* Country
* Year
* Segment

---

# Business Insights

Some key insights identified from the dashboard:

* Total Sales reached **118.73M**.
* Total Profit generated was **17M**.
* Overall Profit Margin is **14%**.
* More than **1.13M units** were sold.
* United States generated the highest sales revenue.
* **Paseo** and **VTT** are the top-performing products.
* Medium Discount Band contributed the largest share of total sales.
* Monthly sales and profit increased significantly during the last quarter of the year.

---

# Conclusion

The Financial Sales Dashboard provides a complete overview of business performance through interactive reports and financial KPIs. It helps stakeholders analyze sales trends, monitor profitability, compare regional performance, and identify top-performing products for better business decision-making.

The project demonstrates skills in:

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX Calculations
* KPI Development
* Power BI Dashboard Design
* Financial Analysis
* Business Intelligence
* Interactive Data Visualization
