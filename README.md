# Crowdfunding_ETL

![istockphoto-1219719976-612x612](https://github.com/user-attachments/assets/ba3740dc-1777-4196-89f3-6eabeb86c57a)

# Team Members:
1. Thomas, Christine
2. Allotey, Shannon
3. Anwar, Iram

For the second project, we were required to work in groups to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After transforming the data, we  created four CSV files and use the CSV file data to create an ERD and a table schema. Finally, we uploaded the CSV file data into a Postgres database.


The instructions for this  project were divided into the following subsections:

Create the Category and Subcategory DataFrames

Create the Campaign DataFrame

Create the Contacts DataFrame

Create the Crowdfunding Database

For creating dataframes,we extracted and transformed excel data files and exported the data frames as csv files and saved them in the repository.

To create the Crowdfunding Database:

. First, we inspected the four CSV files, and then sketched an ERD of the tables by using QuickDBDLinks to an external site.

. Used the information from the ERD to create a table schema for each CSV file.

. Saved the database schema as a Postgres file named crowdfunding_db_schema.sql, and saved it to  GitHub repository.

. Created a new Postgres database, named crowdfunding_db.

. Using the database schema, created the tables in the correct order to handle the foreign keys.

. Verified the table creation by running a SELECT statement for each table.

. Imported each CSV file into its corresponding SQL table.

. Verified that each table has the correct data by running a SELECT statement for each.


