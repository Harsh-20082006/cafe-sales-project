☕ Dirty Cafe Sales Dashboard (Power BI)
📊 Project Overview

This project focuses on analyzing cafe sales data using data visualization techniques in Microsoft Power BI.
The goal is to extract meaningful insights about sales trends, customer behavior, and product performance.

🎯 Objectives
Analyze overall sales performance
Identify top-selling products
Understand customer preferences
Discover peak sales time (day & time slot)
Perform advanced distribution analysis
🌾 Dataset Grain

The dataset follows a transaction-level grain, where each row represents a single cafe order.

📁 Dataset
Name: Dirty Cafe Sales Dataset
Contains:
Date
Item
Quantity
Total Sales
Payment Method
Time Slot
Day Name
🧩 Data Model (Star Schema)
Fact Table: Sales Data
Dimension Table: Calendar Table

Relationship:

Sales[Date] → Calendar[Date] (Many-to-One)
📊 Dashboards Created
1️⃣ Overview Dashboard
KPI Cards → Total Sales, Orders, Quantity
Line Chart → Monthly Sales Trend
Bar Chart → Top Products
Donut Chart → Payment Method
2️⃣ Product Analysis Dashboard
Bar Chart → Sales by Item
Treemap → Product Contribution
Pareto Chart → Top 80% Products
3️⃣ Time Analysis Dashboard ⭐
Heatmap → Day vs Time Slot
Line Chart → Monthly Trend
Area Chart → Sales Trend
Running Total / Moving Average
4️⃣ Sales Distribution Dashboard (Advanced)
Histogram → Sales Distribution
Scatter Plot → Quantity vs Sales
Box Plot → Outliers & Spread
📈 Key Insights
Evening time slots generate the highest sales
Weekends show increased customer activity
Few products contribute majority of revenue (Pareto principle)
Positive relationship between quantity and sales
Presence of outliers in high-value transactions
🛠 Tools & Technologies
Microsoft Power BI
DAX (Data Analysis Expressions)
Data Cleaning & Transformation
🎨 Dashboard Features
Interactive slicers (Month, Item, Time Slot)
Clean coffee-themed UI
Time intelligence (MTD, YTD, Growth %)
Advanced visuals (Heatmap, Pareto, Box Plot)
