# Powerbi_portfolio
### 1)📝 **Project Title:**

**Coffee Shop Sales Insights Dashboard**

---

### 🎯 **Objective:**

To analyze and monitor coffee shop sales performance, product-wise sales contribution, peak sales hours, and regional store performance to support business decisions through data visualization.

---

### 🔑 **Key Features:**

* Interactive date filtering for **monthly sales analysis**
* Weekday vs Weekend sales breakdown
* Product category and item-level performance tracking
* Store-wise performance comparison with growth trends
* Hourly sales distribution across days
* Dynamic KPIs and trend analysis

---

### 📊 **Visualizations Used:**

* **KPI Cards** for Total Sales, Orders, Quantity Sold
* **Line and Bar Combo Charts** for Sales Trends
* **Donut Chart** for Weekday vs Weekend Analysis
* **Stacked Bar Charts** for Hourly Sales by Day
* **Horizontal Bar Charts** for Store and Product-level Sales

---

### 📐 **DAX Measures Used:**

* `Total Sales = SUM(Sales[Sales Amount])`
* `Total Orders = SUM(Sales[Order Quantity])`
* `Total Quantity Sold = SUM(Sales[Quantity])`
* `Sales Growth vs LM = DIVIDE([Current Month Sales] - [Last Month Sales], [Last Month Sales])`
* `Average Sales Per Day = AVERAGEX(VALUES('Calendar'[Date]), [Total Sales])`
* `Weekday/Weekend Sales Split using SWITCH and WEEKDAY logic`

---

### 📌 **KPIs Used:**

* **Total Sales**
* **Total Orders**
* **Total Quantity Sold**
* **% Growth vs Last Month**
* **Average Daily Sales**
  
---

Dasboard Link : https://app.powerbi.com/view?r=eyJrIjoiNTBhYWE4NDgtNmFlNC00MzNlLWE4YzEtNDVlNDc0NjA0YWUwIiwidCI6IjhhMzhkNWM5LWZmMmYtNDc5ZS04NjM3LWQ3M2Y2MjQxYTRmMCIsImMiOjEwfQ%3D%3D

DASHBOARD IMAGES:![COFFEE SHOP DASHBOARD](https://github.com/user-attachments/assets/2b65293b-2cf1-4ce8-87be-a26598c65d17)



**2) 📊 Finance Power BI Dashboard**

This interactive Finance Dashboard was developed to provide an overview of financial performance, enabling strategic decision-making with dynamic filters and user-friendly visuals.

---

**✅ Objectives:**
- Monitor financial KPIs and cash flow trends.
- Identify performance gaps across financial categories and time periods.
- Drill-down into expenses and revenues for deeper insights.

---

**📌 Key Features:**
- **Dynamic Date Filters** for custom date ranges.
- **Category Breakdown** of income and expenses.
- **Visuals** like bar charts, line graphs, Treemaps, and KPI cards.

---

**📊 Visualizations Used:**
- **KPI Cards** for Total Income, Expenses, and Profit Margin.
- **Line & Column Charts** for monthly trends and category breakdowns.
- **Treemaps** for quick visual of spending proportions.

---

**🧮 DAX Measures:**
- **Monthly Average:** `AVERAGEX` over months.
- **Cumulative Totals:** `TOTALYTD` for running sums.
- **Profit Margin:** `(Total Income - Total Expenses) / Total Income`.
- **Variance Analysis:** Comparison of current vs. previous periods.

---

**📈 KPIs Included:**
- **Total Income & Expenses**
- **Net Profit** (Income - Expenses)
- **Profit Margin (%):** Measures profitability.
- **Cumulative Totals** to track growth over time.
- **Highest Expense Category** to assist in cost control.

---

**⚙️ Tools & Technologies Used:**
- [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
- [DAX](https://docs.microsoft.com/en-us/dax/)
- [Power Query Editor](https://docs.microsoft.com/en-us/power-query/)

---



Dashboard Url: https://app.powerbi.com/view?r=eyJrIjoiNTg3NWJkNzktNzQxNy00NDNkLTllNTAtYTY2ZDEzYmQ0ZTI3IiwidCI6IjhhMzhkNWM5LWZmMmYtNDc5ZS04NjM3LWQ3M2Y2MjQxYTRmMCIsImMiOjEwfQ%3D%3D

**DASHBOARD IMAGES:**

![6078100278801974883 (2)](https://github.com/user-attachments/assets/37488f32-3795-4cc1-8bdf-579c8dec5f52)
![6078100278801974056 (2)](https://github.com/user-attachments/assets/d5f382e0-fa30-4dbf-b2a4-8c877de535f8)




---

3) # Blinkit Sales Performance Dashboard

---

### 📌 Objective:
- To provide a comprehensive view of Blinkit's sales performance across different outlet types, outlet sizes, and item categories.
- To help stakeholders monitor key sales trends, product category contributions, and outlet growth over time.
- To deliver actionable insights that support business expansion, operational improvements, and product optimization.

---

### 📈 KPIs Included:
- **Total Sales**: $1.20M
- **Average Sales per Item**: $141
- **Average Customer Rating**: 4
- **Total Number of Items Sold**: 9K

---

### 🚀 Key Features:
- **Dynamic Filter Panel**: Allows filtering based on Outlet Location Type, Outlet Size, and Item Type.
- **Sales Distribution**: View sales split by fat content (Low Fat vs. Regular) and across item categories (Fruits, Snacks, Household, etc.).
- **Outlet Establishment Trend**: Line chart visualizing outlet openings and performance from 2012 to 2022.
- **Outlet Size Analysis**: Sales breakdown by small, medium, and high-sized outlets using donut charts.
- **Outlet Location Insights**: Comparison of sales in Tier 1, Tier 2, and Tier 3 cities.
- **Outlet Type Metrics**: Tabular view showing total sales, number of items, average sales, ratings, and visibility for each outlet type.
- **Interactive and Clean Layout**: Ensures easy navigation and dynamic analysis for users.

---

### 🧠 Key Factors:
- Strong **Data Modeling** to manage complex relationships between outlets, sales, and product categories.
- Extensive use of **DAX** for calculated measures and KPIs.
- **Power Query** for data transformation and ETL processes.
- **Advanced Visual Design**: Focused on clarity, performance, and business relevance.

---

### ⚙️ Tools & Technologies Used:
- Power BI
- DAX (Data Analysis Expressions)
- Power Query (M Language)
- Data Modeling and ETL
- Visualization and UX Design

---

DaASHBOARD IMAGE: 
![6082508650414457962 (1)](https://github.com/user-attachments/assets/6d291d24-0809-4549-b80e-1a7323eaccf2)


Great! Based on your uploaded Power BI dashboard visuals and PBIX file (`GoldProductionAnalysis.pbix`), here’s a well-structured GitHub project description with the required sections:

---

### 4)💼 **Gold Production and Sales Analysis Dashboard**

This Power BI dashboard provides an end-to-end analytical view of gold production performance, sales trends, and production timelines across multiple regions and groups. It helps stakeholders like production managers, sales teams, and executives track key KPIs and drive data-informed decisions.

---

### ✅ **Objectives:**

* Monitor total gold production and sales volumes across months and regions.
* Analyze production timelines and evaluate on-time delivery performance.
* Identify late and early production trends grouped by production unit.
* Track top-selling gold items and compare sales vs production.
* Enable data slicing by **Quarter** and **Region** for dynamic analysis.

---

### 📌 **Key Features:**

* **Production Overview**: Monthly production trends, group-wise breakdown, and production-sales gap.
* **Production Time Management**: Tracks early/late production counts, lead times, and on-time delivery percentage.
* **Sales Analysis**: Insights into sales performance, month-on-month (MoM) sales growth, top-selling items, and sales by group.

---

### 📊 **Visualizations Used:**

* KPI Cards (Total Production, Sales, Production-Sales Diff, On-Time %)
* Line Charts (Production by Month, Sales Trend by Group)
* Column & Bar Charts (Production vs Sales, Lead Time, Production Counts)
* Donut Chart (Production Share by Group)
* Table (Item-wise and Region-wise Sales)
* Gauge Chart (On-Time Production Rate)

---

### 🧮 **DAX Measures:**

* `Total Production`
* `Total Sales`
* `Production Sales Difference`
* `On-Time Production Rate %`
* `Late Production Count`
* `Early Production Count`
* `Month-on-Month Sales Growth %`
* `Sales Percentage`
* `Best Month Sales`, `Least Month Sales`

---

### 📈 **KPIs Included:**

* Total Production
* Total Sales
* Production vs Sales Difference
* On-Time Production Delivery Rate
* Early vs Late Production Counts
* Best and Worst Performing Months by Sales
* Sales Percentage and MoM Growth

---

### ⚙️ **Tools & Technologies Used:**

* **Power BI Desktop** – for dashboard development
* **DAX (Data Analysis Expressions)** – for custom calculations
* **Power Query** – for data transformation and cleaning
* **Excel / SQL** – as data sources (assumed from standard practices)
* **Slicers** – for Region and Quarter-level filtering

  
Dashbord Report URL: https://app.powerbi.com/view?r=eyJrIjoiNjMyYWUyZTAtOTQxYy00NjI1LThkZWQtNWQ2NGIzNTllM2E5IiwidCI6IjhhMzhkNWM5LWZmMmYtNDc5ZS04NjM3LWQ3M2Y2MjQxYTRmMCIsImMiOjEwfQ%3D%3D

DaASHBOARD IMAGE:![gold3](https://github.com/user-attachments/assets/913cfffc-58a6-43ba-a042-365e0018ff39)
![Gold2](https://github.com/user-attachments/assets/03ef9754-8365-45c5-aab3-437e46cd21af)
![Gold1](https://github.com/user-attachments/assets/9a3b5473-66ae-4d21-8a9c-423ccd300a15)



---

### 5)🎧 **Call Center Trends Analysis Dashboard – Power BI**

This Power BI dashboard provides a detailed analysis of call center performance by tracking total calls, agent performance, response times, and customer satisfaction. It enables call center managers to make data-driven decisions for improving service efficiency and customer experience.

---

### ✅ **Objectives:**

* Monitor total, answered, and abandoned calls across months.
* Evaluate agent performance based on key metrics like handle time, satisfaction rating, and call volume.
* Track average customer satisfaction and compare it against the target.
* Analyze call volume trends by hour and topic to optimize workforce planning.

---

### 📌 **Key Features:**

* Agent-wise breakdown of total calls, handle time, and satisfaction rating.
* Visualization of abandoned vs answered calls over time.
* Analysis of call distribution by hour of the day.
* Topic-wise comparison of total calls.
* Gauge chart to monitor satisfaction rating vs. target.

---

### 📊 **Visualizations Used:**

* KPI Cards (Total Calls, Answered Calls, Abandoned Calls, Avg Handle Time, Satisfaction Rating, Avg Speed Answer)
* Gauge Chart (Target vs Avg Satisfaction Rating)
* Donut Chart (Satisfaction Rating by Agent)
* Clustered Column Chart (Answered Calls by Month)
* Bar Chart (Call Count by Hour, Calls by Topic)
* Matrix Table (Agent-level performance summary)

---

### 🧮 **DAX Measures:**

* `Total Calls`
* `Answered Calls`
* `Abandoned Calls`
* `Avg Handle Time`
* `Avg Speed to Answer`
* `Avg Satisfaction Rating`
* `Satisfaction Rating Target Comparison`
* `Calls by Topic`
* `Call Count by Hour`

---

### 📈 **KPIs Included:**

* Total Calls
* Answered Calls
* Abandoned Calls
* Avg Handle Time
* Avg Satisfaction Rating
* Avg Speed to Answer
* Target vs Actual Satisfaction

---

### ⚙️ **Tools & Technologies Used:**

* **Power BI Desktop** – Dashboard development
* **Power Query** – Data preparation and transformation
* **DAX** – Advanced analytics and measures
* **Interactive Filters** – For Agent and Topic selection

---
Dahsboard Link : https://app.powerbi.com/view?r=eyJrIjoiZmI0MjA5ZmYtODcyMS00ZGVlLWFlMjEtNTdiMmY1MjljYjM5IiwidCI6IjhhMzhkNWM5LWZmMmYtNDc5ZS04NjM3LWQ3M2Y2MjQxYTRmMCIsImMiOjEwfQ%3D%3D

DASHBOARD IMAGE: ![Call center](https://github.com/user-attachments/assets/9d1ec1de-2aad-4346-addb-05d5cc8803f5)






