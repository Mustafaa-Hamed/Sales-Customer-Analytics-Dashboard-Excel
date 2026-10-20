Sales & Customer Analytics Dashboard – Excel
📌 Project Overview

--
<img width="1855" height="630" alt="Excel_Project " src="https://github.com/user-attachments/assets/f9ab94de-5b11-403a-a77e-73860e22e4e9" />
---
<img width="1852" height="616" alt="2" src="https://github.com/user-attachments/assets/44bc9c6b-76bb-45de-95f4-27ca731ad606" />
---
<img width="1851" height="632" alt="3" src="https://github.com/user-attachments/assets/ce4aa57a-845b-44f0-b4d6-5cb25b4d010f" />
---
Objective

Turn raw sales data into an interactive business dashboard that helps answer:

How are sales and profit trending over time?
Which regions, segments, categories, and ship modes drive the business?
Who are the top customers, and where are customers concentrated?
Dashboard Pages
Page	What it shows
Overview	Headline KPIs, sales by region, profit by month, sales and profit by ship mode, sales by category
Sales	Sales by month, region (radar), and quarter, plus the top 10 customers by sales
Customers	Customers by region, state, year, and product sub-category
Key KPIs

Total Orders · Total Sales · Total Profit · Total Customers · Number of Products

Interactivity
Slicers for Year and Quarter, connected across all charts on each page.
Sidebar navigation to move between Overview, Sales, and Customers.
Clear All Filters button to reset the dashboard in one click.
Tools & Techniques
Area	Tools
Data cleaning & transformation	Power Query
Data modeling	Power Pivot (Data Model with a Date table)
Calculations	DAX measures and KPIs
Analysis & visuals	PivotTables, PivotCharts
Interaction	Slicers, shapes as navigation buttons, VBA macro (confirm and edit)
Key Insights (from the dashboard data)
West is the top region by sales (about 725K), followed by East (about 679K). South is the lowest (about 392K).
Q4 is the strongest quarter (about 705K) and Q2 the weakest (about 458K), across all years combined.
Standard Class accounts for roughly 59% of sales and 57% of profit.
Technology leads categories with about 36% of sales.
Overall profit margin is around 12.5%.
Repository Structure
.
├── README.md
├── Dashboard.xlsm
├── images/
│   ├── overview.png
│   ├── sales.png
│   └── customers.png
└── docs/
    └── data_dictionary.md   (optional)
How to Use
Download Dashboard.xlsm and open it in Microsoft Excel (desktop version).
Click Enable Content when prompted. The file contains a small macro used for the filter-reset button.
Use the sidebar to switch pages and the Year/Quarter slicers to filter.
To refresh the data, go to Data → Refresh All. If Power Query cannot find the source file, update its path in Data → Queries & Connections.
Author

Mostafa Hamed | Data Analyst LinkedIn | mostafa.hamed1499@gmail.com

#Excel #DataAnalytics #PowerQuery #PowerPivot #DAX #Dashboard #SalesAnalytics #DataVisualization #BusinessIntelligence
