Database Creation in Postgresql database, ETL, Python

In this project, I wrote ETL process to get data from JSON files, process these data and divided into different tables and stored those tables into Postgresql database. I used Python language. For connecting and process data to Postgresql database, I used 'psycopg2' externel library. I used 'Star Schema' for storing data into Postgresql database.

Input: Data Folder has all input files in JSON format which we need to take as input to project.

Steps:

1. Run "create_tables.py" file for creating Database and tables in Postgresql database.

2. Then after run "etl.py" file to getting data from JSON files from all folders in Data folder and adding data to the tables which we created ariler.

"sql_queries.py" file has all SQL Queries which need to use in this project.

"test.ipynb" file has SQL Query, for test data in database via Jupyter notebook.