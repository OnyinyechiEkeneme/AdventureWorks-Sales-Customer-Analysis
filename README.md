# AdventureWorks Sales & Customer Revenue Analysis

## Executive Summary

AdventureWorks demonstrates strong financial performance with $109.85M revenue, supported by high customer retention (86.83%) and strong wholesale demand (73.27% of revenue). However, the business has opportunities to reduce dependency on major customers, diversify geographic revenue, and improve digital sales growth

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

## Business Recommendations

### Customer Retention

* Maintain and strengthen loyalty programs to preserve the strong 86.83% retention rate.
* Implement personalized marketing campaigns targeting high-value returning customers, who account for the majority of revenue.

### Revenue Diversification

* Reduce dependence on the U.S. market by increasing sales and marketing investments in Canada and Australia.
* Explore expansion into additional geographic markets to mitigate regional revenue concentration risk.

### Product Strategy

* Increase inventory allocation and marketing support for top-performing Mountain-200 products.
* Analyze low-performing products for potential discontinuation or repositioning.

### Sales Channel Optimization

* Expand digital sales initiatives to increase online revenue contribution beyond the current 27% share.
* Improve customer experience within online channels through personalized recommendations and targeted promotions.

### Customer Segment Growth

* Continue nurturing wholesale relationships since they contribute over 73% of total revenue.
* Develop targeted campaigns to increase retail customer lifetime value and average order size.
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
