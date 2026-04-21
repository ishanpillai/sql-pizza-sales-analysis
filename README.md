SQL Pizza Sales Analysis Project


📊 Project Overview

This project analyzes pizza store sales data using SQL to extract meaningful business insights related to customer behavior, revenue performance, product demand, and operational trends.
The objective is to simulate a real-world analytics scenario by answering business questions using structured SQL queries across multiple relational tables.


🎯 Project Objectives

The SQL Pizza Sales Analysis project focuses on:

Identifying top-selling pizzas
Analyzing revenue trends
Detecting peak ordering hours
Evaluating category-level performance
Measuring daily operational demand
Supporting inventory and staffing decisions


🗂 Dataset Description

The dataset consists of 4 relational tables:

Table Name	Description
orders	Contains order ID, date, and time
order_details	Contains quantity of pizzas per order
pizzas	Contains pizza size and price
pizza_types	Contains pizza category and name
Table Relationships
orders → order_details → pizzas → pizza_types


🛠 Tools & Technologies Used
MySQL
MySQL Workbench
SQL (Joins, Aggregations, Window Functions)
GitHub (Project Documentation)


📈 Business Questions Answered

This project answers key business questions such as:

How many total orders were placed?
What is the total revenue generated?
Which pizzas generate the highest revenue?
What are the peak ordering hours?
Which category performs best?
What is the average number of pizzas sold per day?
Which pizzas contribute most to revenue within each category?


🔍 Key Business Insights
Total orders processed: 21,350
Total revenue generated: ₹817,860
Most frequently ordered pizza size: Large
Peak ordering hours: 12 PM – 1 PM and 5 PM – 7 PM
Best-performing category: Classic
Highest revenue-generating pizza: Thai Chicken Pizza
Average pizzas sold per day: 138.5
Revenue increased steadily across the year, indicating consistent demand


📊 Category-Level Insights
Category	Quantity Sold
Classic	14,888
Supreme	11,987
Veggie	11,649
Chicken	11,050

Observation: Classic pizzas are the most preferred category among customers.


💰 Top Revenue-Contributing Pizzas
Pizza	Revenue Contribution
Thai Chicken Pizza	5.31%
Barbecue Chicken Pizza	High
California Chicken Pizza	High

These premium pizzas significantly influence overall store revenue.


⏰ Peak Ordering Behavior

Customer ordering peaks during:

Lunch hours (12 PM – 1 PM)
Evening hours (5 PM – 7 PM)

Recommendation: Increase staffing and ingredient preparation during peak hours.


📉 Operational Performance Insights
Average pizzas sold daily: 138.5
Revenue growth remained steady across the year
No significant seasonal drop observed
Demand patterns support predictable inventory planning


🧠 SQL Concepts Used

This project demonstrates:

INNER JOIN
GROUP BY
ORDER BY
Aggregate functions (SUM, COUNT, AVG)
Subqueries
Window functions (RANK())
Date/time extraction
Multi-table relational analysis


📌 Business Recommendations

Based on the analysis:

Promote high-revenue pizzas like Thai Chicken Pizza
Expand Chicken category variety
Optimize staffing during lunch & evening peaks
Maintain inventory priority for Classic category pizzas
Introduce combo offers for Large-size pizzas


🚀 Future Improvements

Potential extensions of this project:

Build Power BI dashboard
Add sales forecasting model
Perform customer segmentation
Analyze weekday vs weekend trends
Add monthly revenue trend visualization


👤 Author

Ishan Pillai

SQL Data Analysis Project using MySQL
Focused on extracting business insights from structured transactional datasets
