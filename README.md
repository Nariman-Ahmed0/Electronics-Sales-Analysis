# Electronics-Sales-Analysis

Sales analysis of an electronics retailer dataset: exploring sales by customer, gender, store, and category to find key business insights.

## Objective

Analyze electronics retailer sales data to understand how sales are distributed across countries, stores, categories, sub-categories, genders, and years, and to identify what drives sales and what needs further analysis.

## Dataset

The dataset contains five files: Sales, Customers, Products, Stores, and a Data Dictionary. It includes 62,884 order lines (26,326 orders) from January 2016 to February 2021, with sales values plus customer, store, and product details. The analysis focuses on sales only.

## Tools Used

* Excel Power Query
* Excel Data Model with DAX (Total Sales measure, Sales Year column)
* PivotTables and PivotCharts
* Data modeling (fact and dimension tables)

## Key Insights

Note: Country refers to the customer's country, except in the Store insight below.

* Total: $55,755,479.59 in sales across 26,326 orders, with an average order value of $2,117.89.
* Country: The United States leads with $29,871,631.17 (53.58% of total sales). The United States and the United Kingdom together make up 66.29%, while France is the lowest at 2.72%.
* Store: US stores generate $23,764,425.86 (42.62%). The online store is second with $11,404,324.63 (20.45%).
* Category: Computers lead with $19,301,595.46 (34.62%). Computers and Home Appliances ($10,795,478.59, 19.36%) together make up 53.98%, while Games and Toys is the lowest at 1.30%.
* Sub-Category: Desktops lead with $9,906,356.50 (17.77%), followed by Televisions ($4,308,719.19, 7.73%). The top 10 of 32 sub-categories account for 70.35% of sales.
* Gender: Sales are almost balanced, with Male at $28,334,854.60 (50.82%) and Female at $27,420,624.99 (49.18%).
* Year: Sales grew 72.32% from $7,421,422.27 in 2017 to $12,788,960.66 in 2018, and peaked in 2019 at $18,264,382.48. In 2020 sales fell 49.11% to $9,294,632.14.
* Seasonality: Across 2016-2020, December is the strongest month at 13.70% of sales, followed by February at 13.37%.

## Data Limitations

The dataset includes orders only up to February 20, 2021, so 2021 ($1,039,288.48) cannot be compared with full years. The 2020 sales decline is visible in the data but its cause is not, so it needs further analysis. This project focuses on sales only; although the Products table includes Unit Cost, profit, margin, and discount effects were not analyzed.
