 📊 Super Store Sales Dashboard
A dynamic and interactive Power BI dashboard designed to track, analyze, and visualize key sales performance metrics for a retail business, enabling data-driven decision-making across regions and customer segments.

🎯 Project Purpose
The primary objective of this dashboard is to provide comprehensive insights into retail sales data across different regions, customer segments, and time frames. It helps stakeholders:
Monitor overall sales performance (Sales, Quantity, Profit, and Delivery efficiency).
Analyze Year-over-Year (YoY) growth trends for sales and profitability.
Understand consumer buying behavior based on payment modes, segments, and shipping categories.

 🛠️ Tech Stack
The dashboard was built using the following tools and technologies:
Power BI Desktop – Main data visualization platform used for report creation and canvas designing.
Power Query – Data transformation and cleaning layer for reshaping and preparing the raw sales data.
DAX (Data Analysis Expressions) – Used for calculating advanced metrics such as Year-over-Year (YoY) Sales, Average Delivery Days, and conditional formatting logic.
Data Modeling – Star schema design establishing relationships between fact sales tables and dimension tables (Region, Time/Date, Product)

 📈 Key Metrics & Features Covered
1. High-Level KPIs
Sum of Sales: $2M total sales revenue.
Sum of Quantity: 22K total items sold.
Sum of Profit: $175K total net profit generated.
Average of AvgDelivery: 4 days average delivery performance.

 2. Deep-Dive Visualizations
Sales by Region: West region leads with 33%, followed by East (29%) and Central (22%).
Sales by Segment: Consumer segment accounts for the highest share at 48%, followed by Corporate (33%) and Home Office (19%).
Sales by Payment Mode: Cash on Delivery (COD) is the most preferred method (43%), followed by Online (35%) and Cards (22%).
YoY Trends (2019 vs 2020): Monthly line graph comparison highlighting seasonality, peaks, and performance growth for both Monthly Sales and Monthly Profit.
Product Category Analysis: Highlighting top-performing sectors like Office Supplies ($0.64M), Technology ($0.47M), and Furniture ($0.45M).

 🚀 How to Use & Interact
1. Use the Region Slicer (Central, East, South, West) at the top right to filter the entire dashboard view.
2. Hover over the Monthly Sales/Profit YoY charts to see specific point-in-time tooltip comparison details for 2019 and 2020.
3. Click on individual visual blocks (e.g., specific Segment or Payment Mode) to cross-filter the other visuals dynamically.

 📂 Project Structure inside Repo
Dataset : Contains the raw data files used (CSV/Excel).
Report : The .pbix Power BI file containing the data model and visual layout. 
Screenshots : High-resolution images of the active dashboard view. 

📊 Dashboard Visuals Explained

1. KPI Cards
Purpose:Displays the overall business performance at a glance.

Metrics:
Total Sales
Total Profit
Total Quantity Sold
Average Delivery Days
Business Use:Helps management quickly monitor key business indicators.

2. Sales by Region (Donut Chart)

Purpose:Shows the percentage contribution of each region to total sales.
Insights:
West Region – 33%
East Region – 29%
Central Region – 22%
South Region – 16%
Business Use:Identifies the highest and lowest performing sales regions.

3. Sales by Segment (Donut Chart)

Purpose: Displays sales distribution among different customer segments.
Segments:
Consumer
Corporate
Home Office
Business Use:Helps understand which customer segment generates the highest revenue.

4. Sales by Payment Mode (Donut Chart)
Purpose:Analyzes customers' preferred payment methods.
Payment Modes:
Cash on Delivery (COD)
Online Payment
Card Payment
Business Use:Supports payment strategy and customer convenience improvements.

5. Monthly Sales YoY (Line Chart)
Purpose:Compares monthly sales performance between 2019 and 2020.
Business Use:
Identifies seasonal trends, sales growth, and months with declining performance.

6. Monthly Profit YoY (Line Chart)
Purpose:Shows monthly profit comparison across different years.
Business Use:Measures profitability trends and identifies high-profit and low-profit periods.

7. Sales by Ship Mode (Bar Chart)
Purpose:Displays sales generated through different shipping methods.
Ship Modes:
Standard Class
Second Class
First Class
Same Day
Business Use:Evaluates the performance of shipping options and customer delivery preferences.

8. Sales by Category (Bar Chart)
Purpose:Compares sales across different product categories.
Categories:
Office Supplies
Technology
Furniture
Business Use:Identifies the best-selling product category and supports inventory planning.

9. Sales by Sub-Category (Bar Chart)
Purpose:Shows sales performance of individual product sub-categories.
Business Use:Helps identify top-selling and low-performing products.

10. Region Filter (Slicer)
Purpose:Allows users to filter the dashboard by region.
Options:
Central
East
South
West
Business Use:Enables interactive analysis for specific geographical regions.


Screenshot of Dashboard :https://github.com/Aka361/Sales-Dashboard/blob/main/Screenshot%202026-07-19%20230754.png
