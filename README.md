# Crowdfunding-ETL-Project2

This project was to demonstrate being able to extract, transform and load data using python, pandas, jupter notebook, sql and sqlalchemy.

In this project, the data was tansformed into CSV files and then uploaded into postgreSQL. A quickdb diagram is included to show the connection between dataframes.

In the first portion with the campaign data, data was transformed by splitting up sub category and category into seperate columns and merging dataframes. Column names were changed and other columns that were unnecessary were dropped. 
The 'goal' and 'pledged' column were changed from an interger to a float.
Times were converted to standard time for 'launch_date' and 'end_date.'

Category and subcategory were spun off into lists and then their own dataframes were created to be transformed as well.

For the 2nd portion, a contacts database was created by breaking data into columns by name, contact id, and email.
Name was further broken down into first name and last name columns.
A dataframe was then created with the info and converted to a CSV.

In the final portion, sqlalchemy was used as an engine to import information to postgreSQL.
