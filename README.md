🚜  Tractor Parts Sales Dashboard

1.  Project Heading
   
Tractor Parts Sales Dashboard — A Business Intelligence Solution for Agricultural Equipment Retailers

2.  Short Description
   
This Power BI dashboard provides a comprehensive view of tractor parts sales performance across multiple villages and customers.

It enables stakeholders to monitor monthly revenue trends, compare sales across different tractor companies, evaluate payment behaviour, and identify top-performing geographical locations — all from a single interactive report page.

3.  Tech Stack
BI Tool	Microsoft Power BI Desktop (v2.152.856.0, Release 2026.03)

Data Source Layer	Microsoft Excel / CSV 

Data Modelling	Power Query (ETL), DAX measures

Visualisation Engine	Power BI Report Canvas — Column, Line, Pie, Donut, Funnel, Map, Card

File Format	.pbix (Power BI Desktop file)

Map Visual	Power BI built-in ArcGIS / Bing Maps integration

4.  Data Source

The dataset is a single flat table named Sheet1, imported from an Excel workbook.

It contains transactional records of tractor parts sold to farmers across different villages. The key fields identified in the report are:

Date	Transaction date (used for month-level hierarchy)

Tractor Company	Brand/company of the tractor (e.g. Mahindra, John Deere, etc.)

Village	Geographic location of the buyer

Payment Mode	Mode of payment (e.g. Cash, UPI, Cheque, Credit)

Diesel Filter	Units / amount sold for Diesel Filter parts

Hydraulic Pump	Units / amount sold for Hydraulic Pump parts

Mobile Filter	Units / amount sold for Mobile Filter parts

Mobile Oil	Units / amount sold for Mobile Oil parts

Bearing	Units / amount sold for Bearing parts

Total Amount	Aggregate sales value per transaction

Profit	Net profit derived from each transaction

5.  Business Problem

Agricultural equipment retailers selling tractor spare parts face several operational challenges:

•	No centralised visibility into which spare parts sell the most month-on-month.

•	Difficulty identifying which tractor brands drive the highest revenue.

•	Lack of insight into which villages or regions generate the most business.

•	Inability to track payment mode preferences, which impacts cash-flow planning.

•	Manual Excel reports are static, time-consuming to update, and hard to share.

These gaps lead to poor inventory decisions, missed sales opportunities, and weak financial planning.

6.  Goal of the Dashboard
The primary goals of this dashboard are:

•	Provide a single-page, real-time overview of all tractor parts sales metrics.

•	Enable management to track total sales and profit at a glance using KPI cards.

•	Identify seasonal trends by visualising monthly sales patterns.

•	Compare performance across tractor companies, villages, and payment methods.

•	Support data-driven decisions on stock procurement, credit policies, and regional expansion.

•	Empower non-technical users with interactive slicers for self-service analysis.

The dashboard contains 8 interactive visual components:

📊  Clustered Column Chart — Sales of Tractor Parts
Compares monthly sales of five part types: Diesel Filter, Hydraulic Pump, Mobile Filter, Mobile Oil, and Bearing. Grouped by month for side-by-side comparison.

📈  Line Chart — Sales by Month
Plots total sales amount over each month to reveal seasonality, growth trends, and dips in revenue.

🥧  Pie Chart — Sales by Tractor Company Breaks down total sales by tractor brand, showing which company's parts contribute most to revenue.	

🍩  Donut Chart — Payment Mode Visualises the distribution of transactions by payment mode (Cash, UPI, Cheque, etc.), helping plan credit and liquidity strategies.

📉  Funnel Chart — Sales by Village Ranks villages from highest to lowest total sales, making it easy to spot top and under-performing markets.

🗺️  Map Visual — Village Locations Plots each village on a geographical map to provide spatial context for regional sales distribution.

🔢  Card Visual — Total Profit Displays the aggregate profit as a single large KPI number for immediate executive-level awareness.	

🗓️  List Slicer — Month Filter Allows users to filter all visuals simultaneously by selecting one or more months, enabling targeted period analysis.

8.  Key Questions the Dashboard Answers

•	Which tractor spare parts generated the highest sales in a given month?

•	How does total revenue trend across months — is the business growing?

•	Which tractor company (brand) drives the most parts sales?

•	Which villages are the largest buyers of tractor parts?

•	How do customers prefer to pay — cash, digital, or credit?

•	What is the total profit earned in a selected period?

•	Are there seasonal peaks in demand for specific parts like hydraulic pumps or filters?

•	Which regions on the map show geographic concentration of sales?

9.  Conclusion

The Tractor Parts Sales Dashboard successfully transforms raw transactional data from a spreadsheet into a rich, interactive, and actionable business intelligence report. By bringing together eight carefully chosen visuals — spanning column charts, line charts, pie charts, funnel charts, map visuals, and KPI cards — the dashboard provides a 360-degree view of sales performance.

This dashboard lays a strong foundation for scaling the analytics capability of the business and can be extended in future iterations with additional KPIs such as customer segmentation, return rates, or year-over-year comparisons.

<img width="1333" height="735" alt="Screenshot 2026-04-19 151724" src="https://github.com/user-attachments/assets/0340b5d7-df80-42b6-acc2-bfbe029d6475" />
