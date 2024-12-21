# Home_Sales

In this challenge, you are asked to utilize home sales data to query key parameters using Spark based on the following instructions. 

Instructions: 

1. Create a new repository on GitHub for this challenge, clone the repository to your computer.
2. Import the PySpark dependencies. 
3. Read in the home_sales_revised.csv data in the starter code into a Spark DataFrame.
4. Create a temporary table called home.
5. Answer the following questions using SparkSQL:
-What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
-What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
-What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
-What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

6. Cache the temporary table home.
7. Check if your temporary table is cached.
8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data.
11. Run the query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Compute the runtime and compare it to uncached runtime.
12. Uncache the home_sales temporary table.
13. Check if the home_sales temporary table is uncached using PySpark.
14. Download the Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

Source:

https://bootcampspot.instructure.com/