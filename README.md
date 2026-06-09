# AdventureWorks Sales & Customer Revenue Analysis

## Project Overview

This project analyzes AdventureWorks' sales performance and customer purchasing behavior using Power BI. The objective was to identify key revenue drivers, evaluate product performance, understand customer purchasing patterns, and uncover opportunities to improve customer retention and revenue growth.

The analysis was performed using the AdventureWorks dataset and focuses on Sales Analytics, Product Performance, Repeat Customers, and Customer Revenue Analysis.

---

## Dashboard Preview



### Executive Dashboard

[<img width="614" height="329" alt="executive-dashboard" src="https://github.com/user-attachments/assets/af56712b-225d-410e-8d73-70959302532d" />
]

### Customer Revenue Dashboard

[<img width="622" height="328" alt="customer-analysis" src="https://github.com/user-attachments/assets/ee5bbf83-7af7-4706-96da-67c84eb209d3" />
]



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

### Sales Performance

* Revenue is concentrated within a small group of high-performing products.
* Certain territories consistently outperform others and contribute a significant share of total revenue.
* Online sales generate higher average order values compared to traditional sales channels.


### Customer Analysis

* A small percentage of customers generate a large proportion of total revenue, confirming the Pareto principle.
* Repeat customers contribute significantly more revenue than one-time buyers.
* Wholesale customers generate higher overall revenue, while retail customers contribute higher transaction volume.

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
