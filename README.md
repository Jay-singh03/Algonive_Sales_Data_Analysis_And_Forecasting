# Algonive_Sales_Data_Analysis_And_Forecasting

📌 Overview
This project contains an interactive Power BI Retail Sales Dashboard built using a dataset of 1,000 retail transactions.
The dashboard helps visualize sales performance, customer behavior, and product category insights in a clear and easy-to-understand format.


# The dashboard screenshot is included below:
Link: https://github.com/Jay-singh03/Algonive_Sales_Data_Analysis_And_Forecasting/blob/main/Retail_Sales_Dashboard_ScreensShot.png

📊 Dashboard Features
1. KPI Summary
- The top section displays key performance indicators:
* Total Revenue: 456K
* Total Quantity Sold: 2514
* Average Transaction Value: 456
* Unique Customers: 1000
These KPIs give a quick overall picture of business performance.


2. Sales Trend Over Time
- Line chart showing monthly revenue
- Helps identify peak months and seasonal patterns


3. Gender-Based Sales Analysis
- Pie chart comparing male vs. female purchases
- Shows distribution of total sales by gender


4. Product Category Performance
- Bar chart showing sales across categories:
* Beauty
* Clothing
* Electronics
Helps understand which categories generate more revenue.


5. Age Group vs. Spending
- Bar chart grouped by age ranges:
* 18–25
* 26–35
* 36–50
* 50+
Useful for identifying high-spending age segments.


6. Top 5 Customers
- Bar chart showing the top customers by revenue
- Helps identify loyal or high-value customers


🧮 DAX Measures Used
* Total Sales = SUM('Sales'[Total Amount])
* Average Transaction Value = AVERAGE('Sales'[Total Amount])
* Total Quantity Sold = SUM('Sales'[Quantity])
* Unique Customers = DISTINCTCOUNT('Sales'[Customer ID])


📂 Dataset Fields
- The dataset includes:
* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount


🎯 Purpose of This Project
- This Power BI dashboard is created to:
* Analyze sales patterns
* Understand customer demographics
* Compare product category performance
* Support data-driven decisions in retail
* Demonstrate Power BI visualization skills
