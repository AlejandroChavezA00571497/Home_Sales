# Home_Sales
Module 22 Challenge for the Tec de Monterrey Data Analysis Bootcamp, Introduction to Spark

Jupyter notebook that takes in data from a CSV and performs SparkSQL queries in order to learn key metrics about home sales data, as well as creating temporary views, partitioning the data, cacheing and uncacheing a temporary table.

Home_Sales_colab.ipynb is the main file, it used data related to home sales, and performs the following steps upon it:
- Creating a Spark session and reading the data into it.
- Creating a temporary view of the Dataframe.
- Querying in SparkSQL.
- Cacheing the table and running more queries, evaluating execution time.
- Partitioning data into Parquet format, and creating a new temporary table.
- Running queries again and evaluating execution time.
- Removing the temporary table from cache.

The file exists in the main directory, as well as the README and the Resources directory, with the CSV that has the home sales information.

Contributions:
- Data Analysis Bootcamp Classes
- https://spark.apache.org/docs/latest/sql-ref.html
- https://spark.apache.org/docs/latest/api/python/index.html
