# Salt hash join technique with Apache Spark

A common problem when working with distributed processing is data skew, a situation where, in the context of Spark, the data is poorly distributed among the DataFrame partitions and consequently among the cluster's workers.

The main consequences of data skew are low performance or memory spills, and this project presents an example of how to mitigate this problem in Join operations.

Check out [salt_hash_join.ipynb](./salt_hash_join.ipynb) for a step-by-step explanation of the implementation, comparisons and demonstrations of results.