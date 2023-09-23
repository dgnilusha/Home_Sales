# Home_Sales

Home Sales Data Analysis with PySpark

In this project, we will analyze home sales data using PySpark. We will perform various data processing and analysis tasks, including creating temporary views, calculating average prices, caching tables, partitioning data, and measuring query runtimes.

Project Tasks

Task 1: Data Loading and Setup
Import the necessary PySpark SQL functions for this assignment.
Read the "home_sales_revised.csv" data into a Spark DataFrame.
Create a temporary table called "home_sales" using Spark SQL.

Task 2: Data Analysis with SparkSQL

Answer the following questions using SparkSQL:
What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

Task 3: Caching and Query Runtime
Cache your temporary table "home_sales."
Check if your temporary table is cached.
Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

Task 4: Data Partitioning
Partition the formatted Parquet home sales data by the "date_built" field.

Task 5: Parquet Data Analysis
Create a temporary table for the Parquet data.
Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

Task 6: Uncaching
Uncache the "home_sales" temporary table.
Verify that the "home_sales" temporary table is uncached using PySpark.
