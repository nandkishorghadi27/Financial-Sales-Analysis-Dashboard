# Financial-Sales-Analysis-Dashboard

## Project Overview
This project demonstrates an end-to-end data analytics workflow using Excel, PostgreSQL (pgAdmin), and Power BI. The goal of the project is to analyze financial sales data to identify business insights such as top-performing countries, profitable products, and sales trends.

## Tools & Technologies
Microsoft Excel – Data cleaning and preprocessing
PostgreSQL – Database storage and SQL analysis
pgAdmin – PostgreSQL database management
Microsoft Power BI – Data visualization and dashboard creation
GitHub – Version control and project hosting

## Project Workflow
1. Raw Dataset Collection (Financials-org.csv)
2. Data Cleaning in Excel
3. Data Import into PostgreSQL using pgAdmin
4. SQL Data Analysis
5. Data Visualization using Power BI Dashboard

## Database Table Structure
Columns used in the dataset include:
Segment, Country, Product, Discount Band, Units Sold, Manufacturing Price, Sale Price, Gross Sales, Discounts, Sales, COGS, Profit, Date, Month Number, Month Name, Year.

## Sample SQL Queries

Total Sales by Country:<br>
SELECT country, SUM(sales) AS total_sales<br>
FROM financial_sales<br>
GROUP BY country<br>
ORDER BY total_sales DESC;<br>
<br>
Profit by Product:<br>
SELECT product, SUM(profit) AS total_profit<br>
FROM financial_sales<br>
GROUP BY product<br>
ORDER BY total_profit DESC;

## Power BI Dashboard Features
Total Sales KPI<br>
Total Profit KPI<br>
Sales by Country<br>
Profit by Product<br>
Sales by Segment<br>
Monthly Sales Trend

## Business Insights
Identify top-performing countries<br>
Understand which products generate the most profit<br>
Analyze sales trends over time<br>
Compare sales performance across market segments<br>

## Skills Demonstrated
Data Cleaning<br>
SQL Querying<br>
Database Management<br>
Data Visualization<br>
Business Intelligence Analysis

## Business Questions Solved
This project answers several important business questions:<br>
Which country generates the highest sales revenue?<br>
Which products contribute the most profit?<br>
Which customer segment performs best?<br>
How do discounts impact overall profitability?<br>
What are the monthly sales trends?<br>
Which products have the highest sales volume?

## Conclusion
This project highlights how raw financial sales data can be transformed into meaningful business insights using modern data analytics tools.<br>
By integrating Excel, SQL, and Power BI, the project demonstrates a practical workflow used by real-world data analysts to:<br>
clean and prepare datasets<br>
store and query data efficiently<br>
visualize key metrics<br>
support strategic decision making<br>
The project showcases the importance of data-driven analysis in improving business performance.

## Interview-Ready Summary
This project is an end-to-end data analytics solution that analyzes financial sales data to identify business trends and performance insights.<br>
<br>
The workflow includes:<br>
Data cleaning using Excel<br>
Data storage and SQL analysis using PostgreSQL<br>
Database management with pgAdmin<br>
Interactive dashboard creation using Power BI<br>
<br>
Through this project, I demonstrated skills in:<br>
Data cleaning and preprocessing<br>
SQL querying and database management<br>
Data visualization and dashboard design<br>
Extracting actionable business insights from financial datasets<br>
This project reflects my ability to convert raw business data into meaningful insights that support strategic decision making.
