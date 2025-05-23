# Inventory, Pricing, and Customer Targeting
This project contains a collection of SQL queries aimed at solving key operational challenges in a retail business. The focus is on evaluating inventory levels, analyzing pricing strategies, and segmenting customers to support data-driven decision-making.

## 📊 Topics Covered
- Stock availability and warehouse completeness checks
- Identifying product categories with low variation
- Comparing product stock levels to category averages
- Exploring the relationship between product prices and purchase volume
- Tracking repeat purchases and purchase intervals
- Finding N-th most expensive products by category
- Simulating pricing strategies and profit projections
- Segmenting customers by company type or location
- Identifying customers eligible for promotions based on credit limits
- Highlighting top-paying customers for loyalty rewards

## 🛠️Tools and Techniques Used
This project utilizes several key SQL techniques to perform the analysis:
- **Filtering & Sorting:** Used to narrow down data based on specific conditions, such as finding the cheapest products or customers from particular cities.
- **Aggregation:** SUM(), COUNT(), and other aggregation functions are applied to calculate totals, averages, and other statistics from the database.
- **Grouping:** Data is grouped by relevant categories (e.g., product line, customer) to derive insights for each group.
- **Window Functions:** Advanced functions like `AVG()`, `LEAD()`, and `NTH_VALUE()` are used for more complex analysis, such as calculating averages per group, comparing purchases over time, and finding the N-th highest price in each product category.
- **Date and Time Analysis:** LEAD and LAG functions are used to analyze customer purchase behavior over time, identifying gaps between purchases.

## 💡Insights
The analysis in this project yields valuable business insights, including:
- **Stock Management:** By calculating total stock and comparing individual product quantities to average stock levels, it’s possible to identify understocked items that need restocking.
- **Product Profitability:** Through the simulation of sales at discounted prices, we identify which products will generate the most revenue and profit, helping the business prioritize stock.
- **Customer Segmentation:** The queries identify high-spending customers, those with available credit, and those from specific cities or countries, providing valuable data for targeted marketing or sales promotions.
- **Price Sensitivity:** By analyzing the relationship between product prices and quantities ordered, we gain insights into customer price sensitivity and can optimize pricing strategies.
- **Trends Over Time:** The use of window functions like LEAD allows tracking customer purchase behavior, revealing patterns in repeat purchases and helping to forecast future sales trends.

## 🏁Conclusion
This project provides a comprehensive view of the warehouse and customer data, offering actionable insights that can drive decision-making in inventory management, pricing strategies, and targeted customer outreach. The use of advanced SQL techniques such as window functions enhances the flexibility and depth of the analysis, enabling the business to make data-driven decisions with confidence.
