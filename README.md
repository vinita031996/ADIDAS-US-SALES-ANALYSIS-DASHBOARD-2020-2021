ADIDAS US Sales Dashboard 2020/2021
Overview
This project is an Excel-based interactive dashboard for analyzing ADIDAS US Sales data from 2020 and 2021. The data was sourced from Kaggle and analyzed using pivot tables to provide insights into the sales performance across different dimensions. The dashboard enables users to explore trends, profitability, and sales patterns through various charts and slicers.

Objectives
The primary objectives of this project are:

To analyze the sales performance of ADIDAS products in the US market for 2020 and 2021.
To create an interactive dashboard for visualizing key metrics like total sales, total profit, and total quantity sold.
To provide insights into regional sales trends, sales methods, and product performance.
To enable data-driven decision-making by visualizing data in a user-friendly manner through Excel pivot tables and charts.
To clean, validate, and ensure the accuracy of data for reliable analysis.
Data Source
Data Collected From: Kaggle
Data Analysis Method: The sales data was analyzed using pivot tables for efficient data summarization and visualization.
Data Preparation
The dataset was processed to ensure its accuracy and reliability:

Reliability Check: Verified the consistency and authenticity of data records.
Duplicate Removal: Identified and removed any duplicate records to maintain data integrity.
Empty Cells Handling: Managed missing data by either removing or filling in empty cells as appropriate.
Data Validation: Checked for accurate data types and formats to ensure consistency across the dataset.
Dashboard Features
Charts
Total Sales, Total Profit, and Total Quantity by Months

Line chart that visualizes monthly trends for total sales, total profit, and quantity sold during 2020 and 2021.
Highlights seasonal patterns and identifies months with peak sales or profitability.
Total Sales and Total Profit by Region

Bar chart displaying sales and profit figures for each region in the US.
Helps in understanding which regions are the top performers in terms of revenue and profitability.
Total Sales by Sales Method

Pie chart that illustrates the share of total sales across different sales channels, including online and retail.
Provides insights into the effectiveness of various sales methods.
Total Sales and Operating Profits by Products

Bar chart that shows total sales and operating profit margins for different product categories.
Helps identify the most profitable product lines and those with potential for growth.
Total Sales by State

Map chart that visualizes the distribution of sales across US states.
Highlights states with the highest and lowest sales figures.
Slicers
The dashboard includes several slicers for interactive data filtering:

Year: Filter data to view insights for either 2020 or 2021.
Region: Focus on specific regions like East, West, North, or South.
Product: Analyze data by selecting specific product categories.
Sales Method: Filter by sales methods such as online or retail.
Retailer: Focus on sales data by specific retailers.
Date: Select custom date ranges to drill down into time-specific analysis.
Key Metrics
Total Sales: Overall revenue generated from all product sales.
Total Profit: Net profit calculated by subtracting the cost of goods sold from total revenue.
Total Quantity: Total number of units sold across all products.
Additional Analysis
Profit Margin Calculation: Added a new column, Sum of Profit Margin, in the pivot table using the Field Items and Sets feature. This column is calculated using the formula:
mathematica
Copy code
(Total Profit / Total Sales) * 100
It provides insights into the profitability of different regions, products, and sales methods.
Data Manipulation and Cleaning
The data preparation process included:

Using pivot tables for summarizing and analyzing large volumes of sales data.
Data Cleaning: Removed duplicates, handled missing values, and corrected data inconsistencies.
Data Manipulation: Created custom fields, including profit margin, for in-depth analysis.
Data Visualization: Developed dynamic charts and slicers for easy exploration and understanding of the data.
How to Use the Dashboard
Download the Excel File:
Clone this repository or download the Excel file directly from the repository link.
Open the Excel Dashboard:
Use Microsoft Excel 2016 or a newer version to open the file.
Use the Slicers:
Interact with the slicers (Year, Region, Product, Sales Method, Retailer, Date) to filter the data and view specific insights.
Analyze the Charts:
Explore the charts to identify sales trends, profitable regions, and product performance.
Insights
The analysis of ADIDAS' sales data for 2020 and 2021 reveals:

Significant sales peaks during holiday seasons, indicating seasonal trends.
Certain regions contribute more to total sales, with some showing higher profitability.
Online sales channels have shown considerable growth over time.
High-profit margins are seen in specific product categories, suggesting areas for further investment.
