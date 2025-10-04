E-Commerce Sales & Profitability Insights Dashboard

Project Overview
This project presents an interactive Power BI dashboard developed for a U.S.-based e-commerce company, designed to analyze Year-to-Date (YTD) sales and profitability data and extract actionable business insights.

Problem Statement
The goal of this project was to:
•	Build a comprehensive sales dashboard using Power BI.
•	Enable stakeholders to monitor KPIs, track YoY (Year-on-Year) performance, and identify trends across customer categories, products, and regions.
•	Provide a data-driven decision-making tool for business strategy and operations.

Key Features & Insights
The dashboard includes the following analytical components:
1. KPI Overview
•	Displays YTD (Year-to-Date) Sales ($11.53M), YTD Profit ($1.34M), YTD Quantity (107.2K), and YTD Profit Margin (11.58%).
•	Shows YoY (Year-over-Year) percentage changes with up/down trend indicators.
•	Adds sparklines to visualize monthly performance trends.
2. Category Performance
•	Compares YTD (Year-to-Date) vs. PYTD (Previous Year-to-Date) sales across product categories such as Office Supplies, Furniture, and Technology.
•	Displays YoY (Year-over-Year) growth trends using visual indicators for quick performance assessment.
3. Product Performance
•	Highlights the Top 5 and Bottom 5 products by YTD Sales.
•	Helps identify both high-performing and underperforming SKUs.
4. Regional & State-Level Analysis
•	Visualizes sales distribution by region (West, East, Central, South).
•	Provides a state-level map showing each region’s contribution to total YTD sales.
5. Shipping Mode Analysis
•	Breaks down YTD sales by Standard, Second Class, and First Class shipping modes.
•	Reveals the percentage contribution of each mode (e.g., Standard Shipping ≈ 60.5%).

Project Workflow
1.	Problem Definition – Identified key business objectives and metrics.
2.	Data Import – Loaded raw data into MS SQL Server.
3.	Data Connection – Connected Power BI to the SQL database.
4.	Data Cleaning – Used Power Query for cleaning and transformation.
5.	Data Processing – Prepared structured tables for modeling.
6.	Data Modeling – Built relationships across 3 tables (Sales, Products, Customers).
7.	Date Table Creation – Added a custom Date Table for time intelligence calculations.
8.	Visualization – Designed KPIs, charts, and maps with clear formatting and consistent color schemes.
9.	Dashboard Assembly – Integrated visuals into a cohesive, interactive Power BI report.
10.	Insight Generation – Interpreted results to deliver meaningful, actionable business insights.
    
 Tools & Technologies
Category	Tools / Techniques
BI Tool	Microsoft Power BI
Database	MS SQL Server
Data Handling	Power Query
Modelling	Star Schema, Relationships
DAX Functions	CALCULATE, SUM, SUMX, FILTER, VALUES, SELECTEDVALUE, RETURN, CONCATENATE, DIVIDE, VAR
Time Intelligence	TOTALYTD, SAMEPERIODLASTYEAR
Visualization	Dynamic KPIs, Conditional Formatting, Icons, Sparklines
Key Insights
•	Office Supplies is the top-performing category (~$6.9M YTD Sales).
•	West Region leads overall sales performance (~32% share).
•	Standard Shipping dominates order fulfillment (~60% of total sales).
•	Certain products show declining YoY (Year-over-Year) performance, indicating areas for potential improvement.

Outcome
This Power BI dashboard empowers the business to:
•	Monitor real-time performance across sales and profitability metrics.
•	Identify growth opportunities and underperforming areas.
•	Support data-driven decision-making through clear, interactive visualizations.

How to Use / Open the Dashboard
1.	Download the .pbix file from this repository.
2.	Open it using Microsoft Power BI Desktop (latest version recommended).
3.	Navigate through the interactive visuals using the slicers, filters, and region/category selectors.
4.	Refresh the data connection if connected to an external database (optional).

Conclusion
This project demonstrates practical use of Power BI, SQL, and data modelling to transform raw e-commerce data into meaningful business insights improving transparency, performance tracking, and decision-making efficiency.

