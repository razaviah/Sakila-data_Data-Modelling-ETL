# Data Modelling and ETL with Sakila Data

## Overview
This project focuses on creating a data model for a data warehouse and writing an ETL script to transform data from the Sakila database. The aim is to practice data modeling, DDL, and DML operations.

![Sakila Schema](https://user-images.githubusercontent.com/108837052/200136697-e5d0a68c-2373-4da1-b6b0-e6388240bb96.png)

## Business Requirements
The data model aims to answer the following business questions:
1. Daily total revenue per store.
2. Overall daily total revenue.
3. Top-performing store each week.
4. Top sales clerks daily/weekly/monthly.
5. Top-performing films weekly/monthly per store.
6. Top 10 customers monthly/yearly.
7. Stores with declining sales trends.

## Project Steps
1. **Load Data**: Load the Sakila dataset into a Snowflake data warehouse.
2. **Analyze Requirements**: Translate business requirements into technical specs.
3. **Data Grain**: Decide the granularity of the data.
4. **Dimension Tables**: Identify and create dimension tables.
5. **Fact Table**: Define and create the fact table.
6. **ETL**: Write the ETL script to populate the data model.

## Project Structure
- `data_creation/`: Contains scripts to create the original dataset and calendar tables.
- `scripts/`: Contains the ETL DDL and DML scripts.
- `data_model/`: Contains the data model and requirements translation process.

## How to Run
1. Use DBeaver to load the original data into Snowflake.
2. Run the ETL scripts to populate the data model.
