# Swiggy_Data_analysis
"Swiggy Sales Analysis project using MS SQL Server with star schema (fact &amp; dimension tables). Includes SQL queries for sales insights, customer behavior, and performance trends."
# Swiggy Sales Analysis – SQL Project

## Overview
This project focuses on analyzing Swiggy sales data using **MS SQL Server**.  
A **star schema** was designed with fact and dimension tables, and SQL queries were written to generate meaningful business insights.  
The detailed business requirements are documented in the attached **Business_Requirements.pdf** file.

## Objectives
- Design a star schema with fact and dimension tables  
- Write SQL queries to answer business questions  
- Generate insights on customer behavior, product categories, and revenue trends  
- Showcase SQL skills for academic and portfolio purposes  

## Tools & Technologies
- MS SQL Server  
- SQL (DDL, DML, Joins, Aggregations)  
- Star Schema (Fact & Dimension tables)  

## Database Design
**Fact Table**  
- `FactSales` → OrderID, CustomerID, ProductID, DateID, RestaurantID, Amount, Quantity  

**Dimension Tables**  
- `DimCustomer` → CustomerID, Name, Age, Gender, Location  
- `DimProduct` → ProductID, Category, SubCategory, Price  
- `DimDate` → DateID, Day, Month, Year, Quarter  
- `DimRestaurant` → RestaurantID, Name, Zone, City  

## Analysis Queries
All business questions and their corresponding SQL queries are included inside the file:  
**`Swiggy_Sales_Analysis.sql`**  

Please refer to that file to see the exact queries and solutions implemented for this project.

## How to Run
1. Open **MS SQL Server**.  
2. Run `Swiggy_Sales_Analysis.sql` to create schema, insert data, and execute queries.  
3. Review query outputs for insights.  
4. Refer to `Business_Requirements.pdf` for detailed objectives.  

---

👨‍💻 **Author:** Naman Shah  
📅 **Project Type:** Academic / Portfolio Showcase
