# Sales Insight Dashboard using PowerBI

## Sales Insights Project PowerBI Dashboard

This project gives detailed insight into the sales of the company AtliQ.

## Problem Statement

AtliQ Hardware is a company which delivers computer hardware & peripheral manufacturers to its clients and has several branches throughout India. The company's sales director is facing a lot of issues in terms of understanding how the business is performing and the problems the company is currently facing as sales are not as expected and are declining gradually. Whenever he calls the regional managers to get the current status of the sales and market, these people are not comfortable consuming numbers from Excel files, which is an obvious reason for the frustration.

## Solution

The sales director of AtliQ Hardware decided to build a PowerBI Dashboard for converting the data into visual representation to make data-driven decisions. So, he hired a team of data professionals to complete this task.

### AIMS Grid

By using the AIMS grid project management tool, we ensured that the purpose, stakeholders, result, and success criteria of our project were clear.

![AIMS Grid](https://github.com/mishraji900/SalesDashboard/blob/main/Screenshot%202024-07-10%20215119.png)

## Steps Followed in This Project

1. Learned about the AIMS grid for project planning.
2. Used MySQL for retrieving the data from the database into Power BI.
3. Data cleaning in Power Query.
4. Performed ETL process (Extract, Transform, Load).
5. Created measures as needed and used them for creating visuals in PowerBI.
6. Performed currency conversion to standardize different currencies in transactions.
7. Data validation.
8. Data modeling and visualization.

## Major Changes/Customizations Made

1. Solved the ‘(blank)’ problem for the products section by deleting the original products table and adding a self-modified products table (added products ranging from Prod280 to Prod339 with their product type).
2. Merged the original modified ‘sales_transaction’ table with a new ‘sales_transaction’ table having profit margin, cost price, etc.

### Insights

1. The company generated a total revenue of ₹985M over 4 years, with a total profit margin of ₹24.7M, a profit margin of 2.5%, and a sales quantity of ₹2M. In 2020, the company generated a total revenue of ₹142M by selling 350K units and earned a profit of ₹2.1M.
2. Over 4 years, Delhi NCR has been the largest market in terms of revenue with ₹520M and a total contribution of 52.8%, but it has a profit margin of only 2.3%.
3. In 2020, Bhubaneshwar had the highest profit margin of 10.48%. Mumbai has the largest profit contribution percentage with 23.89%.
4. Bengaluru generated the lowest profit margin of -20.8% over 4 years, with the lowest profit contribution percentage of -0.3%.
5. Electricalsara Stores is the biggest customer, generating ₹413M in revenue over 4 years.
6. Prod318 is the highest-selling product, generating ₹69M in revenue over 4 years.
7. The 'Distribution' product type generated a revenue of ₹494M, and 'Own Brand' generated ₹494M over the entire 4 years.
8. The revenue trend shows a drastic decrease in June 2020 compared to the previous year, with the lowest profit margin in April 2020.

### Key Learnings

1. Learned about what real business data sets look like.
2. Learned how to write major analysis queries in MySQL.
3. Learned how to connect the database’s tables to Power BI and clean & modify unwanted data in Power Query.
4. Learned about major practical DAX functions and measures.
5. Learned about major analytical visuals and reports.

## Final Result

#### Dashboard KPI Page

![Dashboard KPI Page](https://github.com/mishraji900/SalesDashboard/blob/main/1%20-%20key%20Insights.PNG)

#### Dashboard Performance Insights

![Dashboard Performance Insights](https://github.com/mishraji900/SalesDashboard/blob/main/2%20-%20Profit%20Analysis.PNG)

#### Dashboard Profit Analysis

![Dashboard Profit Analysis](https://github.com/mishraji900/SalesDashboard/blob/main/3%20-%20Performance%20Insights.PNG)
