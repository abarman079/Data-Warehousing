# SMP Retail Data Warehouse and Power BI Analytics

## Project Overview

This project presents a retail data warehouse and business intelligence solution built using the Online Retail II dataset. The goal of the project is to clean, transform, model, and analyze retail transaction data in order to generate useful business insights through a Power BI dashboard.

The project includes data cleaning, dimensional modeling, fact and dimension table design, Power BI data modeling, and interactive dashboard development for sales performance analysis.

## Objectives

The main objectives of this project are:

* To clean and transform raw retail transaction data.
* To design a data warehouse model suitable for reporting and analysis.
* To create fact and dimension tables for sales analytics.
* To build a Power BI dashboard for business decision-making.
* To analyze sales performance by product, country, customer, and time period.

## Tools and Technologies

* Microsoft SQL Server
* SQL Server Management Studio
* Microsoft Power BI
* Power Query
* DAX
* CSV dataset
* Dimensional data modeling

## Dataset

The project uses the `online_retail_II.csv` dataset, which contains retail transaction records including invoice information, product details, quantity, price, customer information, country, and date/time fields.

## Data Warehouse Design

The data model follows a dimensional modeling approach. The main sales transaction data is stored in a fact table, while descriptive information is separated into dimension tables.

The model includes tables such as:

* Fact Sales table
* Date dimension
* Time dimension
* Customer dimension
* Product dimension
* Product category dimension
* Invoice dimension
* Country dimension

This structure supports flexible analysis of sales revenue, quantity sold, customer activity, product performance, and country-level sales trends.

## Data Cleaning and Transformation

The raw dataset was cleaned and transformed using Power Query. The cleaning process included:

* Promoting headers
* Changing data types
* Renaming columns
* Creating calculated/custom columns
* Filtering invalid or unwanted rows
* Removing duplicate transaction records
* Preparing the cleaned fact table for Power BI analysis

## Power BI Dashboard

The Power BI dashboard provides an interactive view of retail sales performance. It includes key performance indicators and visualizations such as:

* Total sales
* Total invoices
* Total customers
* Average basket value
* Monthly sales trend
* Sales revenue by country
* Top products by sales revenue
* Top products by quantity sold
* Product sales detail table

## Key Insights

The dashboard helps identify:

* The highest revenue-generating products
* Countries contributing the most sales
* Monthly sales patterns
* Product-level sales and quantity performance
* Customer and invoice-level business performance

## Repository Structure

```text
docs/report/          Final project report
docs/figures/         ERD, snowflake model, and transformation figures
data/raw/             Raw dataset
data/sample/          Sample dataset for quick preview
powerbi/              Main Power BI report file
reports/screenshots/  Power BI dashboard screenshots
sql/                  SQL scripts for database and warehouse tables
powerquery/           Power Query cleaning documentation
dax/                  DAX measures used in Power BI
```

## How to Use This Project

1. Download or clone the repository.
2. Open the Power BI `.pbix` file from the `powerbi` folder.
3. Update the dataset path if Power BI asks for the local CSV file location.
4. Review the report screenshots in the `reports/screenshots` folder.
5. Review the final report in the `docs/report` folder.
6. Review the ERD and data model diagrams in the `docs/figures` folder.

## Project Status

This project is completed as a data warehousing and business intelligence project. Future improvements may include adding automated ETL scripts, publishing the dashboard to Power BI Service, and adding more advanced DAX measures for profitability and customer segmentation analysis.

## Author

Abarman079
