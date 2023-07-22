# Home_Sales

Using SparkSQL to determine key metrics about home sales data, to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

# For this challenge I did the following:

* Imported the necessary PySpark SQL functions.
* Read the home_sales_revised.csv data into a Spark DataFrame.
* Created a temporary table called home_sales.
* Answered the following questions using SparkSQL:
    * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    * What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to        two decimal places.
    * What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal        to 2,000 square feet? Round off your answer to two decimal places.
    * What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your       answer to two decimal places.
* Cached the temporary table home_sales.
* Checked if temporary table is cached.
* Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. 
 Determine the runtime and compare it to uncached runtime.
* Partition by the "date_built" field on the formatted parquet home sales data.
* Created a temporary table for the parquet data.
* Ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
* Uncached the home_sales temporary table.
* Verified that the home_sales temporary table is uncached using PySpark.


### Documented Help Received For Assignment
