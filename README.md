This project connects and extracts data from an SQL Server and transforms the data into reports for different regions of a company.
This repository contains two versions of the project. 
The first version creates the report from 4 CSV files for customer billing details, adjustments, and payments for two different categories of customers, 
with billing details being the largest with over 714,000 rows and 51 columns, 
payment file for category 1 customers with over 266,000 rows and 64 columns,
payment file for category 2 with over 265,000 rows and 54 columns and 
adjustment with over 2,000 rows and 11 columns.

The latest version connects directly to the database and extracts all required data for the report, making the process faster and better.
The SQL queries and further are hidden for privacy’s sake.

The raw data is cleaned and transformed based on the peculiarity of the dataset and of the requirements of the reports.
An aggregation is carried out on the data to produce a summary of the data for 3 different types of report files in CSV format –
Billing status for the 28 regions, Consolidated report (which is a further summary of all the regional reports), and a further summary of the consolidated report. 
Each report file has 3 sheets for the 2 different categories of customers and a summary of both categories of customers. 

