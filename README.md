# 📊 AdventureWorks Sales Dashboard using Microsoft Excel

An interactive executive sales dashboard built using **Microsoft Excel, Power Query, and Power Pivot** to analyze four years of AdventureWorks sales data. The project focuses on profitability analysis across **time, products, customers, pricing, and geography**, providing business stakeholders with actionable insights through an intuitive two-page dashboard.

---

## 📌 Project Overview

The objective of this project is to transform raw transactional sales data into an interactive Business Intelligence dashboard that enables management to monitor business performance and identify key profit drivers.

The solution follows a complete BI workflow:

Raw Data → Power Query → Data Model (Power Pivot) → Analysis Layer → Interactive Dashboard

---

## 🎯 Business Problem

The client wanted to analyze four years of transactional sales data with a primary focus on **profitability**.

The dashboard should answer questions such as:

- How has profit changed over time?
- Which products generate the highest profit?
- Which customers contribute the most?
- Which countries are the most profitable?
- How do weekdays, months and quarters influence profit?
- What percentage of total profit comes from the top-performing products and customers?

---

# 🛠 Tools & Technologies

- Microsoft Excel
- Power Query
- Power Pivot
- Pivot Tables
- Pivot Charts
- Slicers & Timelines
- Data Model (Star Schema)

---

# 🏗 Data Model

The project uses a **Star Schema** built inside Power Pivot.

### Fact Table
- FactInternetSales

### Dimension Tables
- DimDate
- DimCustomer
- DimProduct
- DimSalesTerritory
- DimGeography

The relationships enable multidimensional analysis across time, products, customers and geography.


---

# ⚙ Data Preparation

Data preparation was performed using **Power Query**.

### Transformations performed

### FactInternetSales
- Removed unnecessary columns
- Created:
  - Total Revenue
  - COGS
  - Total Profit

### DimProduct
- Removed unused attributes
- Standardized missing product colors

### DimCustomer
- Removed unnecessary columns
- Combined First Name & Last Name

### DimDate
Created custom calendar attributes:

- Year
- Month Number
- Month Name
- Quarter
- Day Name
- Week Type (Weekday / Weekend)

### DimGeography
- Removed unnecessary columns

---

# 📈 Dashboard Overview

The solution contains **two interactive dashboard pages**.

---

# 📊 Dashboard 1 – Time Series Analysis

Focuses on business performance over time.

### Features

- Executive KPI Cards
- Revenue
- Profit
- COGS
- Profit Margin
- Transactions
- Quantity Sold

### Time Intelligence

- Year-over-Year comparison
- Monthly Profit Trend
- Quarterly Profit Analysis
- Weekday vs Weekend Analysis
- Profit by Weekday

### Interactive Filters

- Year
- Month
- Country
- KPI Selection


---

# 📊 Dashboard 2 – Product & Customer Analysis

Focuses on identifying profit contributors.

### Product Analysis

- Top 5 Products
- Product Contribution %
- Product Pricing Analysis
- Product Color Analysis
- Sold vs Unsold Products

### Customer Analysis

- Top 5 Customers
- Customer Contribution %
- Gender-wise Profit
- Age Group Analysis
- Average Customer Age

### Geographic Analysis

- Country-wise Profit Distribution
- Interactive Country Selection


---

# 📂 Backend Analysis Sheets

To keep the dashboard responsive and organized, all business calculations were separated into helper sheets.

### 1_analysis1

Contains

- KPI calculations
- Previous Year comparison
- Yearly summaries
- Executive measures

### 1_analysis2

Contains

- Monthly calculations
- Weekday analysis
- Quarter calculations
- Dynamic chart data

### 2_Product Analysis

Contains

- Product KPIs
- Top Products
- Pricing analysis
- Product Color calculations

### 2_Customer Analysis

Contains

- Customer KPIs
- Top Customers
- Age Groups
- Gender Analysis
- Geographic calculations

---

# 💡 Key Business Insights

- Top 5 products contribute nearly one-fourth of total profit.
- Only a small percentage of available products generate sales, highlighting opportunities for inventory optimization.
- Weekday sales contribute significantly more profit than weekends.
- Profit is concentrated within specific quarters and months.
- Geographic analysis highlights countries contributing the largest share of overall profit.

---


---

# 🚀 How to Use

1. Download the repository.
2. Open `AdventureWorks_Sales_Dashboard.xlsm`.
3. Enable Macros (if prompted).
4. Use the interactive filters and slicers to explore the dashboard.

---

# 📚 Dataset

AdventureWorks sample dataset provided by Microsoft for educational and analytical purposes.

---


