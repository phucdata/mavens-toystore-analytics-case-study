Maven Toys – Sales Data Analytics Dashboards
Overview
This case study showcases two interactive sales dashboards built with Microsoft Excel and Power BI to explore the sales performance of Maven Toys, a fictitious chain of toy stores in Mexico. The analysis covers product categories, store locations, and time periods (2022 transactions).
The project was completed as part of the SEO-V Momentum 2025 Mentorship Case.
Tools
•	Microsoft Excel
•	Microsoft Power BI
•	Data cleaning and data modeling
•	Data visualization and dashboard design
Dataset
The data comes from three related tables:
Table	Description
sales	Daily transactions: date, store ID, product ID, units sold
products	Product name, category, unit cost (USD), retail price (USD)
stores	Store name and store location type (Downtown, Commercial, Residential, Airport)
Revenue, cost, and profit were calculated by joining the three tables:
•	Revenue = Units × Product Price
•	Cost = Units × Product Cost
•	Profit = Revenue − Cost
Dashboard: 
•	Presents key performance indicators, including sales volume, total cost, revenue, and profit.
•	Visualizes revenue by product category (treemap), quantity by product category (column chart), and profit distribution by store location (pie chart).
•	Shows total cost, revenue, and profit by month in a stacked column chart.
•	Enables interactive exploration using Month and Location slicers.
•	Key Findings
•	Downtown stores generate the most profit: $239,523, about 59.5% of total profit. Commercial follows with $86,260 (21.4%), then Residential with $42,688 (10.6%) and Airport with $34,371 (8.5%).
•	Toys is the top revenue category at about $391K, followed by Art & Crafts ($316K), Games ($302K), Sports & Outdoors ($235K), and Electronics ($220K).
•	Toys also sells the most units (28,309), followed by Art & Crafts (24,588) and Games (21,790).
Business Questions
The dashboards were built to answer the questions from the case brief:
1.	What are the company's total revenue, cost, and profit in 2022?
2.	Which month is the most profitable?
3.	Which city and location has the highest number of selling stores in December 2022?
4.	Which product category has the biggest profit, and which has the biggest revenue?
5.	How can sales performance be monitored by month across location and product category?
6.	Are there any patterns in the data, such as seasonal trends, top-selling locations, or top-selling categories?
Repository Structure
maven-toystore-analytics-case-study/
├── README.md
├── data      # Source dataset (.xlsx file)
└── dashboard   # Dashboard screenshots
Key Learning Outcomes
•	Building business-focused dashboards.
•	Cleaning, joining, and organizing data from multiple tables.
•	Organizing and presenting performance metrics.
•	Exploring sales patterns across multiple dimensions.
Data Disclaimer
The dataset is a fictitious dataset published by Maven Analytics and was provided for the SEO-V Momentum 2025 Mentorship Case; it is used here with permission. It does not represent a real company, and the findings should be read as a practice analysis, not as real business results.

