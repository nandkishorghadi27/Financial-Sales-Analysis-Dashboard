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
