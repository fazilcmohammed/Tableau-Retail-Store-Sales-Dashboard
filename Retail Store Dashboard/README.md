# Retail Store Dashboard
The Retail Store Sales Data Exploration and Dashboard project, aiming to provide a comprehensive analysis and visualization platform for understanding the business performance. The project utilized Excel data exploration techniques to extract insights and develop a Tableau dashboard. By offering stakeholders a user-friendly interface to explore key metrics such as regions generating highest and lowest revenue, monthly trend of revenue, and top customers and how much do they contribute to the total revenue,etc. The project aimed to empower informed decision-making and the major contributing factors are to the revenue so they can strategically plan for next year.

Access the live dashboard on Tableau Public: [Retail Store Dashboard](https://public.tableau.com/app/profile/mohammed.fazil.c/viz/RetailStoreSalesDashboard_17085384301970/Dashboard2?publish=yes)
## Project Overview
This document serves as documentation for the Retail Store Sale data exploration and dashboard project, which aimed to analyze and visualize sales related data. The project involved data exploration, data cleaning, data manipuation and the development of a comprehensive dashboard using Tableau.
### Project Scope
The project utilized Retail Store sales data, focusing on metrics such as monthly revenue generated, top countries by revenue, best customers, and regions generated high revenue. The data exploration phase involved clean, and transform the dataset for analysis. Subsequently, a Tableau dashboard was developed to visualize key insights and trends.
### Tools and Technologies:
The project utilized the following tools and technologies:
* Microsoft Excel: Tool used for data manipulation, exploration, and analysis.
* Tableau: For creating a variety of visualizations and interactive dashboards.
### Data Exploration
The Retail Store Sales dataset includes information on stock code, description, quantity, invoice date, unitprice, customerid, and country. The data exploration phase involved two main steps: cleaning and manipulation.
* Data Cleaning: Data cleaning is a crucial step in the data analysis process.
   - Contained negative values in quantity and unitprice columns.
   - Converted the negative quantities into 1 unit.
   - Converted the negative unit prices into $0.
   - Null values were present in the Description field and filled with NA.
* Data Manipulation: It is the process of adjusting data to make it organised and easier to read.
  - Date and time was there in a single cell and then splitted into two separate columns with the help of Text to Column feature in Excel.
  - A new field named Sales added to the dataset and filled with values by multiplying the UnitPriceand Quantity columns.
### Tableau Dashboard
#### Access the live dashboard on Tableau Public: [Retail Store Dashboard](https://public.tableau.com/app/profile/mohammed.fazil.c/viz/RetailStoreSalesDashboard_17085384301970/Dashboard2?publish=yes)
The Tableau dashboard was designed to visualize key insights and trends related to store sales, including monthly revenue, top countries, top 10 customers, and best regions. The dashboard includes KPIs, line graphs, column charts, side by side charts, and map chart to provide a comprehensive overview of the sales.
### Dashboard Components:
* Key Performance Indicators (KPIs):
   - Total Units Sold
   - Total Sales
   - Number of Customers
* Line Graph:
   - Revenue per Month
* Column Chart:
   - Top 10 Customers
* Side by Side Chart:
   - Top 10 Countries by Revenue & Units Sold
* Map Chart:
   - Units Sold by Country
### Project Conclusion
