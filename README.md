# Sakila-data_Data-Modelling-and-ETL

## 1. Project Description

In the project, you are going:
Step 1: create a data model for a data warehouse.
Step 2: write the ETL script to transform the data from the original tables to the data model you create.

(Be aware that this dataset maybe not the best dataset for the requirements, but the main purpose of this project is to practice the idea of data modeling and create DDL and DML.)

## 2. About the data

The dataset is the Sakila database about online DVD store. The database relationship in the original database will be like this:


![sakila_os_diagram](https://user-images.githubusercontent.com/108837052/200136697-e5d0a68c-2373-4da1-b6b0-e6388240bb96.png)


This is a typical OLTP dataset for operational system. The dataset contains several tables, you first need to tell which tables can be used for dimension tables and which tables can be used for fact table.


## 3. Business Requirements

In this project, you need to make a data model to meet the following requirements from the managemental team:

    List the total revenue of each store everyday.
    List the total revenue of totally everyday.
    List the top store according to their weekly revenue every week.
    List top sales clerk who have the most sales each day/week/month.
    Which film is the top film each week/month in each store/totally?
    Who are our top 10 customers each month/year?
    Is there any store the sales is in a decline trend (within the recent 4 weeks the avg sales of each week is declining) 

Our target is to create a data model make end user can easily query simply with SELECT, GROUP BY, JOIN
