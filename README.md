# Cleaning-Data-with-PySpark
## Description
To learn what’s needed to prepare data processes using Python with Apache Spark. You’ll learn terminology, methods, and some best practices to create a performant, maintainable, and understandable data processing platform.
### 1. DataFrame details
A review of DataFrame fundamentals and the importance of data cleaning.
* Defining a schema: `StructField()`
* Parquet: `.withColumnRenamed()`, `.union()`
### 2. Manipulating DataFrames in the real world
A look at various techniques to modify the contents of DataFrames in Spark.
* `.shere()`, `.size()`, `.getItem()`, `.distinct()`, `when()`, `.otherwise()`, .rand()`
* User defined functions or UDFs
* Partitioning: `.rdd.getNumPartitions()`
* Adding an ID Field: `.monotonically_increasing_id()`
