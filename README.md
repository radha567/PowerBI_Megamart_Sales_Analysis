📊 Megamart Sales Performance Analysis – Power BI Dashboard
📌 Project Overview

This project presents a Power BI Dashboard designed to analyze and visualize Megamart's sales performance across multiple dimensions. It highlights key KPIs and trends to support data-driven decision-making.

🔹 Key Features

KPIs: Total Sales, Total Profit, Profit Margin %, Average Order Value (AOV), Customer Count.

Trend Analysis: Total Sales and Profit by Month.

Regional Insights: Sales and Profit distribution by region.

Product Insights: Sales and Profit by product category.

Customer Segments: Analysis across Corporate, Wholesale, and Retail customers.

Order Status & Payment Method: Track completed, pending, and canceled orders.

🛠 DAX Measures Used

Total Sales = SUM('Sheet1'[Total Sales])

Total Profit = SUM('Sheet1'[Profit Amount])

Profit Margin % = DIVIDE(SUM('Sheet1'[Profit Amount]), SUM('Sheet1'[Total Sales]), 0)

Average Order Value = DIVIDE(SUM('Sheet1'[Total Sales]), DISTINCTCOUNT('Sheet1'[Order ID]), 0)

Customer Count = DISTINCTCOUNT('Sheet1'[Customer ID])

📊 Insights

Corporate customers contribute the highest sales revenue.

Regional sales show balanced contributions across East, West, North, and South.

Payment methods like PayPal and Credit Card dominate but cancellation rates vary.

Average Order Value stands at 1.31K, with a 17% Profit Margin.

🚀 Skills Demonstrated

Data Cleaning & Transformation in Power BI.

DAX Calculations for KPI measures.

Interactive dashboard design.

Data storytelling & visualization.

📂 Project Structure
├── Megamart_Sales_Performance_Dataset.xlsx   # Dataset used
├── Screenshot.png                            # Dashboard image
└── README.md                                 # Project documentation
💡 Conclusion

This dashboard provides actionable insights into sales trends, customer behavior, and profitability drivers, enabling better business strategies and decision-making.

If you find this project insightful, feel free to ⭐ the repo and connect with me on LinkedIn!
