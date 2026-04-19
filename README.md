
# Tractor Parts Sales Dashboard






## 1.Project Heading
Tractor Parts Sales Dashboard — A Business Intelligence Solution for Agricultural Equipment Retailers






## 2.  Short Description
This Power BI dashboard provides a comprehensive view of tractor parts sales performance across multiple villages and customers.

It enables stakeholders to monitor monthly revenue trends, compare sales across different tractor companies, evaluate payment behaviour, and identify top-performing geographical locations — all from a single interactive report page.






## 3.  Tech Stack

•BI Tool	Microsoft Power BI Desktop (v2.152.856.0, Release 2026.03)

•Data Source Layer	Microsoft Excel / CSV (Sheet1)

•Data Modelling	Power Query (ETL), DAX measures

•Visualisation Engine	Power BI Report Canvas — Column, Line, 

•Pie, Donut, Funnel, Map, Card

•File Format	.pbix (Power BI Desktop file)

•Map Visual	Power BI built-in ArcGIS / Bing Maps integration

## 4.Data Source

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Data | ![#0a192f](https://dummyimage.com/10/0a192f/white?text=+)Date	Transaction date (used for month-level hierarchy).|
|Tractor company | ![#f8f8f8](https://dummyimage.com/10/f8f8f8/white?text=+)Tractor Company	Brand/company of the tractor. (e.g. Mahindra, John Deere, etc.)  |
| Village | ![#00b48a](https://dummyimage.com/10/00b48a/white?text=+)Village	Geographic location of the buyer.
| Payment Mode | ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Mode of payment (e.g. Cash, UPI, Cheque, Credit) | Data | ![#0a192f](https://dummyimage.com/10/0a192f/white?text=+)Date	Transaction date (used for month-level hierarchy).|
| Diesel Filter | ![#f8f8f8](https://dummyimage.com/10/f8f8f8/white?text=+)Diesel Filter	Units / amount sold for Diesel Filter parts  |
| Mobile Filter | ![#00b48a](https://dummyimage.com/10/00b48a/white?text=+)Units / amount sold for Mobile Filter parts.
| Mobile Oil| ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Units / amount sold for Mobile Oil parts. 
| Hydrolic Pump | ![#0a192f](https://dummyimage.com/10/0a192f/white?text=+)Units / amount sold for Hydraulic Pump parts.|
| Bearing | ![#f8f8f8](https://dummyimage.com/10/f8f8f8/white?text=+)Units / amount sold for Bearing parts .
| Total amount | ![#00b48a](https://dummyimage.com/10/00b48a/white?text=+)Aggregate sales value per transaction.
| Profit | ![#00d1a0](https://dummyimage.com/10/00d1a0/white?text=+)Net profit derived from each transaction.
## 5.  Business Problem
Agricultural equipment retailers selling tractor spare parts face several operational challenges:

•No centralised visibility into which spare parts sell the most    month-on-month.

•Difficulty identifying which tractor brands drive the highest revenue.

•Lack of insight into which villages or regions generate the most business.

•Inability to track payment mode preferences, which impacts cash-flow planning.

•Manual Excel reports are static, time-consuming to update, and hard to share.

These gaps lead to poor inventory decisions, missed sales opportunities, and weak financial planning.


## 6.Goal Of The Dashboard

•	Provide a single-page, real-time overview of all tractor parts sales metrics.

•	Enable management to track total sales and profit at a glance using KPI cards.

•	Identify seasonal trends by visualising monthly sales patterns.

•	Compare performance across tractor companies, villages, and payment methods.

•	Support data-driven decisions on stock procurement, credit policies, and regional expansion.

•	Empower non-technical users with interactive slicers for self-service analysis.

## 7.Key Visuals


| 📊  Clustered Column Chart — Sales of Tractor Parts 
| :-------- | 
| Compares monthly sales of five part types: Diesel Filter, Hydraulic Pump, Mobile Filter, Mobile Oil, and Bearing. Grouped by month for side-by-side comparison. | |



| 🥧  Pie Chart — Sales by Tractor Company
| :-------- | 
| Breaks down total sales by tractor brand, showing which company's parts contribute most to revenue. | |

|  📉  Funnel Chart — Sales by Village
| :-------- | 
| Ranks villages from highest to lowest total sales, making it easy to spot top and under-performing markets.| |

|  🔢  Card Visual — Total Profit
| :-------- | 
| Displays the aggregate profit as a single large KPI number for immediate executive-level awareness.| |

|  📈  Line Chart — Sales by Month
| :-------- | 
| Plots total sales amount over each month to reveal seasonality, growth trends, and dips in revenue.| |

|  🍩  Donut Chart — Payment Mode
| :-------- | 
| Visualises the distribution of transactions by payment mode (Cash, UPI, Cheque, etc.), helping plan credit and liquidity strategies.| |

|  🗺️  Map Visual — Village Locations
| :-------- | 
| Plots each village on a geographical map to provide spatial context for regional sales distribution.| |

|  🗓️  List Slicer — Month Filter
| :-------- | 
| Allows users to filter all visuals simultaneously by selecting one or more months, enabling targeted period analysis.| |

## 8.Key Questions the Dashboard Answers

•	Which tractor spare parts generated the highest sales in a given month?

•	How does total revenue trend across months — is the business growing?

•	Which tractor company (brand) drives the most parts sales?

•	Which villages are the largest buyers of tractor parts?

•	How do customers prefer to pay — cash, digital, or credit?

•	What is the total profit earned in a selected period?

•	Are there seasonal peaks in demand for specific parts like hydraulic pumps or filters?

•	Which regions on the map show geographic concentration of sales?




## 9.Conclusion
•This Power BI dashboard converts raw tractor parts sales data into clear, actionable insights. It helps the business track revenue, monitor part-wise performance, identify top villages, and understand payment trends — all in one place.

•With interactive visuals and a month slicer, decision-makers can quickly analyse any time period without technical knowledge, leading to smarter inventory and sales decisions.

## 10.ScreenShot
<img width="1333" height="735" alt="Screenshot 2026-04-19 151724" src="https://github.com/user-attachments/assets/a747b68f-3fde-4684-88f8-770e6f854972" />
