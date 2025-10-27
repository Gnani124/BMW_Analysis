# BMW_Analysis

🚗 BMW Sales Analytics Dashboard – Power BI
📌 Project Overview

This project presents a comprehensive BMW Sales Analytics Dashboard built in Power BI to visualize global sales performance across regions, models, fuel types, and years.
The dashboard provides key insights into Electric Vehicle (EV) adoption, regional sales trends, and model-wise revenue performance, helping stakeholders make informed, data-driven decisions.

🎯 Objective

To analyze BMW’s global sales data and identify patterns in:

Regional performance

EV share and fuel type distribution

Year-over-year sales growth

Pricing trends by model and transmission

📊 Key Insights

🌍 Asia leads as the top-performing sales region.

⚡ EV Share: 50.67% of total units sold, reflecting BMW’s move toward electrification.

🚘 Total Units Sold: 42.97M

💵 Total Revenue: $639M

💰 Average Price (USD): 75.55K

📈 Stable growth in sales volume and price across years.

🧮 Power BI Measures Used
Total Units Sold = SUM(Sales_Volume)
Total Revenue (USD) = SUM(Price_USD)
Average Price (USD) = AVERAGE(Price_USD)
EV Share (%) = DIVIDE(EV_Sales, Total_Sales) * 100
Sales by Region = SUMMARIZE(Region, "TotalSales", SUM(Sales_Volume))
Yearly Trend = SUMMARIZE(Year, "SalesVolume", SUM(Sales_Volume), "Revenue", SUM(Price_USD))

📈 Dashboard Features

Sales Overview by Year

Model-wise and Region-wise Sales Distribution

Fuel Type and Transmission Comparison

EV vs. Non-EV Performance Analysis

Interactive visuals with filters for detailed exploration

🛠️ Tools & Technologies

Power BI – for data visualization

Excel / CSV – data source

DAX – for creating measures and calculated fields

💡 Outcome

This dashboard delivers a clear and interactive view of BMW’s global performance, enabling quick insights into EV growth, fuel type trends, and model profitability. It serves as a foundation for business strategy and performance optimization.
