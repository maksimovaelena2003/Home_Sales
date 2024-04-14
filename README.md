# Home_Sales
Module22

1. Renamed the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

2. Imported the necessary PySpark SQL functions for this assignment.

3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

4. Created a temporary table called home_sales.

5. Answered the following questions using SparkSQL:

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

6. Cached your temporary table home_sales.

7. Checked if your temporary table is cached.

8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

9. Partitioned by the "date_built" field on the formatted parquet home sales data.

10. Created a temporary table for the parquet data.

11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

12. Uncached the home_sales temporary table.

13. Verified that the home_sales temporary table is uncached using PySpark.

14. Downloaded  Home_Sales.ipynb file and uploaded it into  "Home_Sales" GitHub repository.

