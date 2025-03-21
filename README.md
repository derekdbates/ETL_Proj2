# Project-2-Group-2: Crowdfunding ETL Project

# Overview
This project focuses on building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform data. After transforming the data, we created four CSV files, which were used to design an Entity Relationship Diagram (ERD) and a table schema. Finally, the transformed data was uploaded into Postgres database. The purpose of this database is to create crowdfunding campaign data, including information on categories, subcategories, campaigns, and contacts. 

# Files
- crowdfunding.xlsx: The raw data for crowdfunding campaigns
- contacts.xlsx: The raw data for contact info
- category.csv: The CSV file with the category data
- subcategory.csv: The CSV file with subcategory data
- campaign.csv: The CSV file with campaign details 
- contacts.csv: The CSV file with campaign details 
- crowdfunding_db_schema.sql: The SQL schema to create the tables in the Postgres database

# Project Structure 
- ETL Pipeline: We extract the data from crowdfunding.xlsx and contacts.xlsx, transform it into a clean format, and load it into a Postgres database
- CSV Files: After transforming the data, it's saved as CSV files
- Postgres Database: The CSV data gets imported into a Postgres database called crowdfunding_db
- ERD: You can check out a visual representation of how the tables are related in the ERD

# Instructions
The instructions for this mini project are divided into the following subsections:
- Create the Category and Subcategory DataFrames
- Create the Campaign DataFrame
- Create the Contacts DataFrame
- Create the Crowdfunding Database

