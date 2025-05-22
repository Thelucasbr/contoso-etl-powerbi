Python + Power BI Contoso Sales Analysis (2025)

This project analyzes retail sales data from the fictional Contoso company using Python for ETL and Power BI for data modeling and visualization. The focus is on generating key insights into product performance, revenue, and brand contribution.

Objective:

To clean, transform, and visualize sales data (~3.5 million rows) using Python and Power BI, delivering a dashboard that supports strategic business decisions.

Highlights:

Cleaned and merged sales data using Python

Created calculated columns:

TotalCostCalc = UnitCost * SalesQuantity

GrossProfit = SalesAmount - TotalCostCalc


Built key DAX measures in Power BI:

Total Sales

Total Cost

Gross Profit

Sales Quantity

Avg Ticket (Total Sales / Sales Quantity)


Designed an interactive dashboard with slicers by Month, Class, and Brand


Key Insights:

Deluxe products represent 25% of units sold, but generate 45% of total revenue, showing strong pricing power.

Contoso is the clear leader in both sales volume and revenue, demonstrating strong brand dominance.

Sales are significantly higher on weekdays, suggesting potential for growth with weekend promotions.

A significant portion of revenue comes from the "Others" category, signaling a data governance issue that requires correction.


![Picsart_25-05-22_13-06-24-788](https://github.com/user-attachments/assets/53b47420-df1b-45ea-8ab7-af9860d666cd)





Dashboard Visuals:

Total Sales and Avg Ticket by Product Class

Units Sold by Workday vs. Weekend

Sales Quantity by Brand

Total Sales by Day and Month

KPI cards: Total Sales, Units Sold, Unique Products


Technologies Used:

Python (Pandas + Google Colab)

Power BI (DAX + Power Query)


Files:

PowerBI_Sales_Analysis.pbix– Clean dataset ready for Power BI

powerbi_dashboard.png

