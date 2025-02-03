# **SQL Retail Sales Analysis**  

📊 **Retail Sales Data Analysis using SQL**  

## **Overview**  
This project focuses on **data cleaning, exploration, and analysis** of retail sales transactions using SQL. It involves various SQL queries to extract meaningful business insights from transactional data.  

## **Built With**  
- **Database:** PostgreSQL  
- **Query Language:** SQL  
- **Tools Used:** Any SQL client like MySQL Workbench, pgAdmin, or DBeaver  

## **Key Features**  
✅ Data Cleaning: Handling missing values and inconsistencies  
✅ Data Exploration: Analyzing sales performance, customer demographics, and product categories  
✅ Business Insights: Finding top customers, best-selling months, and sales trends  

## **Dataset Structure**  
The dataset consists of a **retail_sales** table with the following columns:  

| Column Name     | Data Type   | Description |
|----------------|------------|-------------|
| transaction_id | INT (PK)   | Unique ID for each transaction |
| sale_date      | DATE       | Date of the sale |
| sale_time      | TIME       | Time of the sale |
| customer_id    | INT        | Unique customer ID |
| gender         | VARCHAR(15) | Gender of the customer |
| age            | INT        | Age of the customer |
| category       | VARCHAR(15) | Product category |
| quantity       | INT        | Number of units sold |
| price_per_unit | FLOAT      | Price per unit |
| cogs          | FLOAT      | Cost of goods sold |
| total_sale     | FLOAT      | Total sales amount |

## **SQL Queries Implemented**  

### **1️⃣ Data Cleaning Queries**  
- Identified and removed missing values from key columns  
- Checked for duplicate records (if applicable)  

### **2️⃣ Data Exploration Queries**  
- Total number of sales and unique customers  
- List of distinct product categories  

### **3️⃣ Business Analysis Queries**  
- Total sales for each category  
- Top 5 customers based on total sales  
- Best-selling month in each year  
- Average age of customers by category  
- Sales distribution across different time shifts (Morning, Afternoon, Evening)  

