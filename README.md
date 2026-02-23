# Power-bi-sales-dashboard
Data analysis project using Power BI to visualize business performance and generate actionable insights.
# 📌 Project Summary

Developed an interactive Power BI dashboard to analyze sales and operational performance data for Blinkit (quick-commerce retail model).

The dashboard transforms raw transactional data into actionable business insights using data modeling, DAX calculations, and interactive visualizations.

This project demonstrates real-world Data Analyst skills including data cleaning, KPI development, business analysis, and dashboard storytelling.

# 🎯 Business Problem

Retail businesses need to:

Monitor overall sales performance

Identify high and low-performing outlets

Understand product category contributions

Optimize revenue across different locations

This dashboard enables stakeholders to make data-driven decisions by visualizing key metrics and trends.

# 📊 Key KPIs Built

💰 Total Sales

📦 Total Number of Items

⭐ Average Rating

📈 Average Sales per Outlet

# 📈 Analysis Performed
🔹 Sales Performance

Sales by Outlet Type

Sales by Outlet Size

Sales by Location Tier

🔹 Product Analysis

Sales by Item Type

Low Fat vs Regular Product Comparison

Category-wise Revenue Contribution

🔹 Trend Analysis

Outlet Establishment Year Trends

Tier-based Revenue Distribution

High vs Low Performing Stores

# 🛠 Technical Skills Demonstrated

✔ Data Cleaning using Power Query

✔ Data Modeling (Relationships & Star Schema)

✔ DAX Measures & Calculated Columns

✔ KPI Development

✔ Interactive Dashboard Design

✔ Business Insight Generation

✔ Data Storytelling

# 🧠 Sample DAX Measures

Total Sales = SUM(Sales[Total_Sales])

Average Sales = AVERAGE(Sales[Total_Sales])

Total Items = COUNT(Sales[Item_Identifier])

Sales Contribution % = DIVIDE([Total Sales], CALCULATE([Total Sales], ALL(Sales)))
