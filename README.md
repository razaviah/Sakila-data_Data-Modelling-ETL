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
