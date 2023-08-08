# Home_Sales
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

In this Home Sales PySpark Challenge, the following tasks were undertaken:

1. Renaming the Notebook file: The original file "Home_Sales_starter_code.ipynb" was renamed to "Home_Sales.ipynb" to begin the assignment.
2. Importing necessary PySpark SQL functions: Essential PySpark SQL functions were imported to perform data analysis.
3. Reading the dataset: The "home_sales_revised.csv" data was read into a Spark DataFrame to prepare it for analysis.
4. Creating a temporary table: A temporary table named "home_sales" was created using the DataFrame, enabling the use of SparkSQL queries.
5. Answering the questions: SparkSQL queries were employed to answer specific questions related to the home sales dataset, such as average prices and view ratings.
6. Caching the temporary table: The "home_sales" temporary table was cached to improve query performance.
7. Checking cache status: Verification was done to ensure that the "home_sales" table was successfully cached.
8. Running the filtered query using cached data: The filtered query, which involved view ratings with prices above $350,000, was executed using the cached data to compare its runtime with the uncached runtime.
9. Partitioning the formatted parquet data: The formatted parquet home sales data was partitioned based on the "date_built" field for optimized future queries.
10. Creating a temporary table for parquet data: A temporary table was created using the partitioned parquet data for further analysis.
11. Running the filtered query using parquet data: The filtered query, similar to the previous one, was executed using the parquet data to compare its runtime with the uncached runtime.
12. Uncaching the temporary table: The "home_sales" temporary table was uncached to release cached memory.
13. Verifying uncaching: The uncaching status of the "home_sales" table was verified using PySpark.

Overall, these tasks helped analyse and answer various questions related to the home sales dataset using PySpark and SparkSQL.

## Requirements

* Python
* Jupyter Notebook Environment
* PySpark (pip install pyspark)
* Google Colab was used to execute this code.

Once you have set up the required environment and fulfilled the prerequisites mentioned above, you can execute the "Home_Sales_colab.ipynb" script. Follow the instructions and execute each cell in the notebook to perform the data analysis tasks as outlined.