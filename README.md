Home Sales Analysis using PySpark
This repository contains a Jupyter Notebook (Home_Sales.ipynb) which performs analysis on home sales data using PySpark SQL. The notebook addresses the following tasks:

File Renaming and Importing Dependencies:

Renamed the Home_Sales_starter_code.ipynb file to Home_Sales.ipynb.
Imported necessary PySpark SQL functions.
Data Loading and Temporary Table Creation:

Read the home_sales_revised.csv data into a Spark DataFrame.
Created a temporary table named home_sales.
Analytical Queries:

Calculated the average price for a four-bedroom house sold for each year.
Determined the average price of a home for each year it was built, with specific criteria.
Computed the average price of a home per "view" rating having an average home price greater than or equal to $350,000.
Performance Optimization:

Cached the temporary table home_sales to improve query performance.
Checked if the table was cached.
Ran the analytical query again using the cached data to compare runtime.
Data Partitioning and Optimization:

Partitioned the data by the date_built field and saved it in Parquet format.
Created a temporary table for the parquet data.
Ran the analytical query on the parquet data to evaluate performance.
Uncaching and Verification:

Uncached the home_sales temporary table.
Verified that the table was uncached using PySpark.
Notebook Management:

Saved the notebook.
Downloaded and uploaded the Home_Sales.ipynb file to the "Home_Sales" GitHub repository.
