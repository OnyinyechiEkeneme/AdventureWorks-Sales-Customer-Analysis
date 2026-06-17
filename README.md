# AdventureWorks Sales & Customer Revenue Analysis

## Project Overview

This project analyzes AdventureWorks' sales performance and customer purchasing behavior using Power BI. The objective was to identify key revenue drivers, evaluate product performance, understand customer purchasing patterns, and uncover opportunities to improve customer retention and revenue growth.

The analysis was performed using the AdventureWorks dataset and focuses on Sales Analytics, Product Performance, Repeat Customers, and Customer Revenue Analysis.

---

## Dashboard Preview



### Executive Dashboard

<img width="614" height="329" alt="executive-dashboard" src="https://github.com/user-attachments/assets/af56712b-225d-410e-8d73-70959302532d" />


### Customer Revenue Dashboard

<img width="622" height="328" alt="customer-analysis" src="https://github.com/user-attachments/assets/ee5bbf83-7af7-4706-96da-67c84eb209d3" />




## Business Problem

AdventureWorks operates across multiple territories and product categories. Management requires visibility into:

* Which products generate the most revenue.
* Which customers contribute the highest value.
* Customer retention and repeat purchase behavior.
* Revenue trends across time and territories.
* Opportunities to increase customer lifetime value and profitability.

The goal of this analysis is to provide actionable insights that support strategic decision-making and business growth.

---

## Dataset Overview

The analysis was built using AdventureWorks sales and customer data, including:

### Fact Table

* FactSales

### Dimension Tables

* DimDate
* DimProduct
* DimCustomer
* DimTerritory

### Key Fields Used

* Order Date
* Product Category
* Product Name
* Customer Name
* Customer Segment
* Territory
* Quantity Sold
* Unit Price
* Revenue (LineTotal)

---

## Data Modeling

A star schema data model was implemented to improve performance and enable efficient analysis.

### Fact Table

* FactSales

### Dimension Tables

* DimDate
* DimProduct
* DimCustomer
* DimTerritory

Relationships were configured using one-to-many relationships between dimensions and the sales fact table.

---

## Methodology

The following calculations and metrics were developed using DAX:

### Sales Metrics

* Total Revenue
* Total Orders
* Total Quantity Sold
* Average Order Value (AOV)
* Revenue Growth %
* Revenue YTD

### Customer Metrics

* Repeat Customers
* Customer Retention Rate
* Customer Revenue
* Customer Revenue Contribution
* Pareto Analysis (80/20 Rule)

### Product Metrics

* Revenue by Product
* Revenue by Category
* Top-Selling Products

---

## Dashboard Pages

### Executive Sales Overview

Provides a high-level view of business performance through:

* Total Revenue
* Revenue Growth %
* Total Orders
* Average Order Value
* Monthly Revenue Trends
* Revenue by Territory


### Customer Revenue Analysis

Examines:

* Revenue by Customer Segment
* Repeat Customers
* Customer Retention Rate
* Top Customers
* Customer Pareto Analysis

---

## Key Insights

* Analyzed sales performance across 31K orders, generating $109.85M in revenue from 20K customers and 275K units sold.
* Developed an executive sales dashboard that identified the United States as the top-performing market, contributing $48.18M (64.08%) of total revenue.
* Evaluated customer purchasing behavior and found an 86.83% retention rate, with approximately 17K returning customers driving repeat revenue growth.
* Discovered that wholesale customers generated $80.49M (73.27%) of total revenue, significantly outperforming retail customers, who contributed $29.36M (26.73%).
* Identified top-performing products, with the leading product generating $4.4M in revenue, supporting product prioritization and inventory planning.
* Analyzed purchase frequency patterns across customer segments, revealing that retail customers accounted for 27,659 transactions (88%), while wholesale customers generated higher revenue per customer despite lower transaction volume.
* Calculated an Average Order Value (AOV) of $3.49K, providing insight into customer spending behavior and revenue optimization opportunities.

---

## Recommendations

### 1. Strengthen Customer Retention

Develop loyalty and retention programs targeted at high-value customers to increase customer lifetime value.

### 2. Increase Cross-Selling Opportunities

Bundle accessories with bicycle purchases to improve average order value and revenue per customer.

### 3. Expand Digital Sales Initiatives

Invest in digital marketing and online sales channels to capitalize on higher online customer spending behavior.

### 4. Optimize Inventory Planning

Maintain sufficient inventory levels for top-performing products to prevent stockouts and lost sales opportunities.

### 5. Target High-Growth Territories

Allocate marketing resources toward territories showing strong growth potential and customer demand.

---

## Tools Used

* Power BI
* Power Query
* DAX
* Data Modeling
* Microsoft Excel




## Author

**Onyinyechi Cynthia Ekeneme**

Data Analytics Project | AdventureWorks Business Analysis
