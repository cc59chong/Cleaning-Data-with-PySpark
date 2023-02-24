# Cleaning-Data-with-PySpark
## Description
To learn what’s needed to prepare data processes using Python with Apache Spark. You’ll learn terminology, methods, and some best practices to create a performant, maintainable, and understandable data processing platform.
### 1. DataFrame details
A review of DataFrame fundamentals and the importance of data cleaning.
* Defining a schema: `StructField()`
* Parquet: `.withColumnRenamed()`, `.union()`
### 2. Manipulating DataFrames in the real world
A look at various techniques to modify the contents of DataFrames in Spark.
* `.where()`, `.size()`, `.getItem()`, `.distinct()`, `when()`, `.otherwise()`, .rand()`
* User defined functions or UDFs
* Partitioning: `.rdd.getNumPartitions()`
* Adding an ID Field: `.monotonically_increasing_id()`
### 3. Improving Performance
Improve data cleaning tasks by increasing performance or reducing resource requirements.
* Caching: `.cache()`, `.is_cached()`, `.unpersist()`
* Caculating running time: `start_time = time.time()  time.time() - start_time`
* Cluster configurations: `spark.conf.get()`, `spark.conf.set()`
* Shuffling: `.explain()`, .coalesce(num_partitions)`, `.join()`, `.broadcast()`
### 4. Complex processing and data piplines
Learn how to process complex real-world data using Spark and the basics of pipelines.
* `.write()`, `print("Initial count: %d\nFinal count: %d" % (initial_count, final_count))`
* **Project**: Resolve questions about the type of dogs seen in an image and some details regarding the images.
