# Crowdfunding_ETL

![istockphoto-1219719976-612x612](https://github.com/user-attachments/assets/ba3740dc-1777-4196-89f3-6eabeb86c57a)

# Team Members:
1. Thomas, Christine
2. Allotey, Shannon
3. Anwar, Iram

For the second project, we were required to work in groups to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After transforming the data, we  created four CSV files and use the CSV file data to create an ERD and a table schema. Finally, we uploaded the CSV file data into a Postgres database.


The instructions for this  project were divided into the following subsections:

1. Create the Category and Subcategory DataFrames

2. Create the Campaign DataFrame

3. Create the Contacts DataFrame

4. Create the Crowdfunding Database

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


![QuickDBD-Free Diagram (1)](https://github.com/user-attachments/assets/dec2e07d-f0ad-461c-9b7f-369e0edc1e4f)


# Conclusion:

ETL (Extract, Transform, Load) projects teach several essential skills and principles relevant to data analytics and engineering. 

###  **Data Handling and Pipeline Management**
   - **Data Extraction**: Understanding how to pull data from different sources such as databases, APIs, flat files, and web scraping.
   - **Data Transformation**: Learning how to clean, format, and process raw data to make it consistent and ready for analysis.
   - **Data Loading**: Storing data in an optimized way, often in a database or data warehouse, ensuring it's accessible and organized for future analysis.

###  **Data Cleaning and Quality**
   - We gained experience in handling missing, inconsistent, or erroneous data, which is crucial for accurate analysis.
   - ETL projects often involve applying business rules to ensure data quality, which is essential for creating reliable datasets.

###  **SQL and Scripting Skills**
   - ETL processes rely heavily on SQL for data extraction and transformation, as well as scripting (e.g., Python, R) for additional transformations or data manipulation.
   - Mastering these skills can be useful for both data engineering and analytics work, as it makes you proficient in data querying and manipulation.

###  **Understanding Data Integration**
   - WE learn to integrate data from multiple sources, which is essential in analytics for combining disparate data to create comprehensive views of information.
   - This skill is crucial for creating data-driven insights, as it enables us to see patterns and trends across datasets.




In summary, ETL projects provide hands-on experience with data processing and integration, which are foundational to any data-driven role. 
