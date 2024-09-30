# Sales Data Analysis with SQL and Excel

## Project Overview

This project demonstrates how to analyze sales and product data using MySQL for database management and Excel for data visualization. The analysis focuses on querying and extracting meaningful insights from two databases: one for sales data and another for product data.

## The project consists of:

**MySQL:** Data storage, table creation, and querying.

**Excel:** Building a dashboard for visualizing key sales metrics.

## Table of Contents

- Project Overview
- Technologies Used
- Database Schema
- Key Queries
- Dashboard Overview
- How to Run the Project
- License

## Technologies Used
**MySQL:** Database Management System used to store and query the data.
**Excel:** For creating visualizations and a dashboard to display the results of the analysis.

## Database Schema

The project includes the following tables:
- production.categories: Stores product category details.
- production.brands: Stores brand details.
- production.products: Stores product details, including brand and category references.
- sales.customers: Stores customer information.
- sales.stores: Stores retail store details.
- sales.staffs: Stores staff and manager information.
- sales.orders: Stores order details.
- sales.order_items: Stores order items, including product and quantity.
- production.stocks: Tracks the inventory of products across stores.

## Key Queries
This project includes SQL query to extract key insights from the data.

## Dashboard Overview

![image](https://github.com/user-attachments/assets/f570d929-556b-4f46-bb51-c57e672e3ed4)


The Excel dashboard provides the following visualizations:

- **Total Revenue:** A chart ilustrating total revenue per year.
- **Revenue per Month:** Time-series chart ilustrating revenue changes over a year.
- **Revenue per State:** Map showing the the most proficient states.
- **Total Revenue by Category:** A chart showing total revenue for each product category.
- **Total Revenue by Brand:** A chart showing total revenue for each brand.
- **Sales by Store:** A breakdown of sales for each retail store.
- **Revenue per Sales Representative:** A table showcasing the top-sellers.
- **Top 10 Customers:** A table showing 10 top buyers.


## How to Run the Project

**Database Setup:**

Run the SQL scripts in MySQL to create the necessary tables and load data into them:
create_databases_and_tables.sql to create 2 databases: sales and products and tables.
mysql_sales_data_bikes.sql to load data into the tables.
querying_sales_data_bikes_mysql.sql to extract and analyze data.

**Excel Dashboard:**

SALES_DATA_FINAL_DASHBOARD_20240915.xslx

Open the SALES_DATA_FINAL_DASHBOARD_20240915.xslx file to view the dashboard with interactive charts and data.

## License

Apache


