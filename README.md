# Sales-Report-dashboard
📈 Sales Performance Dashboard:

An interactive Power BI dashboard designed to analyze total sales, sales trends, store-wise performance, and province-level revenue distribution.

Purpose:

The Sales Performance Dashboard helps users quickly understand how sales are performing across months, stores, and regions. It highlights key KPIs, seasonality patterns, and top-performing provinces so that managers can make informed business decisions.

Tech Stack

This dashboard was created using:

-Power BI Desktop – Main tool for data modelling and visualization

-Power Query – Used to clean, merge, and transform customer, sales, and product data

-DAX (Data Analysis Expressions) – For calculations like YoY%, YTD Sales, and KPI logic

-Data Modeling – Relationships were built between Sales, CustomerMaster, and other tables

Data Source:

The dashboard uses sales transaction data along with customer details.

Sales Data – Monthly sales amount, quantity sold, and item counts

CustomerMaster.xlsx – Contains customer and province information

Data includes: store types, regions, monthly sales amounts, quantities, YoY% changes, and YTD performance

These datasets were connected and transformed in Power BI to build clean, analysis-ready tables.

Features:
• Business Problem

Managers need a simple way to track sales performance, compare store types, and identify which regions contribute the most revenue. Raw data makes it difficult to see trends or understand where improvements are needed.

• Goal of the Dashboard

To provide a clear, interactive view of:

How sales and quantity change over months

Which store types generate the highest sales

Which provinces perform best

Year-over-year (YoY) and year-to-date (YTD) sales trends

Key business KPIs at a glance

• Walkthrough of Key Visuals
1. Sales KPIs (Top Right)

Total Items Sold: 843K

Total Quantity: 9M
These give a quick snapshot of business performance.

2. Monthly Sales Table (Center)

Shows:

Sum of Sales

YoY% Growth

Sales YTD
Useful for identifying months with strong or weak performance.

3. Store Type Sales (Top Left)

A bar chart comparing Supermarket, Gift Store, Computer Store, and Corporate.
This helps identify which store type brings in the highest revenue.

4. Quantity Trend by Month (Bottom Left)

A line chart showing quantity sold across months to reveal seasonality patterns.

5. Sales by Province (Bottom Right)

A descending bar graph ranking provinces by total sales.
Example: Texas, Pennsylvania, New York appear as top contributors, while states like Arizona and Massachusetts contribute the least.

6. Province Detail Tooltip

Hovering over provinces (e.g., Illinois) displays exact sales values, adding more detail without cluttering the dashboard.

• Business Impact & Insights

Better Regional Strategy: Provinces with low sales can be targeted for promotions or new campaigns.

Store-Type Optimization: Understanding which store formats drive the most revenue helps with planning future store openings.

Demand Forecasting: Monthly quantity trends help predict peak demand periods.

Performance Tracking: Managers can instantly see YoY growth and YTD totals for faster decision-making.

ScreenShot: ![Dashboard Preview](https://github.com/alexmathews03/Sales-Report-dashboard/blob/main/Screenshot%20of%20dashboard%20report.png)
