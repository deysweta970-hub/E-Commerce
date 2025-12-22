# E-Commerce
🔹 Project Overvie
This project showcases a portfolio-ready E-Commerce Sales Dashboard built using Power BI, designed to analyze sales performance, profitability, order status, and customer trends from 2023 to 2025.
The dashboard uses realistic business data and advanced DAX calculations, making it suitable for Data Analyst / Business Intelligence roles.
#
<a href="https://github.com/deysweta970-hub/E-Commerce/commit/883ea486604fa8b97923d8d709fb5f25b1a9de4a">E-Commerce</a>

# Project Overview

This project analyzes E-commerce sales performance using transactional data to help business stakeholders understand sales, profit, cost, quantity trends, and customer behavior.
The dashboard provides YTD performance, growth comparison, and identifies top and bottom contributors to support data-driven decision making.

# Business Objective

• The main objectives of this analysis were:

• Track Year-to-Date (YTD) Sales, Profit, Quantity, and Cost

• Compare current year performance with previous year growth

• Identify top customers, profitable categories, and loss-making products

• Analyze order status distribution and regional performance

# Dataset Details

• Domain: E-Commerce

• Time Period: 2023 – 2025

• Records: 5,000+ rows

• Key Fields:

• Order Date, Ship Date

• Product Category

• Sales, Profit, Cost, Quantity

• Customer Name

• State / Region

• Order Status

# Tools & Technologies Used

• Excel – Data cleaning & preprocessing

• SQL – Data validation and aggregations

• Power BI – Data modeling, DAX measures, and dashboard visualization
# Dax Formula 
•  YTD Sales = TOTALYTD (
    [Total Sales],
    'Date'[Date] )

  
•     YTD Profit = TOTALYTD (
    [Total Profit],
    'Date'[Date] )

•  YTD Cost = TOTALYTD (
    [Total Cost],
    'Date'[Date] )

•  YTD Qty = TOTALYTD (
    [Total Qty],
    'Date'[Date] )

  •  YoY Sales Growth % = DIVIDE (
    [YTD Sales] - [PY Sales],
    [PY Sales] )


  •   YoY Profit Growth % = DIVIDE (
    [YTD Profit] - [PY Profit],
    [PY Profit]
)

 • Sales Growth Icon = SWITCH (
    TRUE(),
    [YoY Sales Growth %] > 0, "▲",
    [YoY Sales Growth %] < 0, "▼",
    "=")
# Key KPIs (YTD – 2025)

• YTD Sales: $17.23M (↑ 1.76%)

• YTD Profit: $4M (↑ 2.22%)

• YTD Quantity Sold: 5,119 (↑ 2.56%)

• YTD Cost: $13.23M (↑ 1.62%)

•These KPIs help stakeholders quickly evaluate overall business health.

#  Dashboard Insights
1 Sales by Product Category

• Electronics and Fashion are the highest revenue-generating categories

• Home & Kitchen shows relatively lower growth compared to others

• Category-wise YoY growth helps identify expansion opportunities

2 Top 5 Customers by Sales

• A small group of customers contributes a significant portion of total revenue

• Helps the business focus on high-value customer retention strategies

3 Order Status Analysis

• Majority of orders are Delivered, indicating operational efficiency

• Cancelled and Returned orders highlight areas for logistics and quality improvement

4 Geographic Sales Distribution

• Strong sales concentration across major Indian states

• Regional insights support location-based marketing and supply planning

5 Profit Trend by Month

• Profit shows a steady upward trend toward year-end

• Seasonal peaks observed during festive months

6  Bottom 5 Products by Profit

• Identifies loss-making products

• Enables decisions on pricing, supplier renegotiation, or product discontinuation

# Key Business Takeaways

• Sales and profit are growing steadily YoY

• Few customers and categories drive most revenue

• Some products consistently reduce profitability

• Data can help optimize pricing, inventory, and customer strategy


# Dashboard
![E  COMMERCE (1433)](https://github.com/user-attachments/assets/137425dd-8dd4-4df5-9e14-9567c1a645c7)

