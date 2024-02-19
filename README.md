* In this project, SparkSQL is used to determine key metrics about home sales data.
* This project was done in Google colab and required to install Spark and Java
* Following are the key metrics
   * average price for a four-bedroom house that was sold in each year
   * Average price a home that has three bedrooms and three bathrooms. 
   * average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built
   * view rating for homes with the average price greater than or equal to $350,000

* Comparision is made  on the runtimes for executing queries on an uncached temporary table, a cached temporary table, and a cached and partitioned Parquet temporary table.
* Improved performance can be observed when utilizing caching and optimized storage format, Parquet.
  
