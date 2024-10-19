# Salt hash join technique with Apache Spark

A common challenge in distributed processing is data skew, which occurs in Spark when data is unevenly distributed across the partitions of a DataFrame and, consequently, among the cluster's workers.

Unbalanced partitions usually lead to performance degradation and memory leaks, potentially making it impossible to execute a simple but poorly optimized job.

In this project, I demonstrate how to mitigate this issue in join operations. Access the [salt_hash_join.ipynb](./salt_hash_join.ipynb) file to check the step-by-step explanation of the implementation and demonstration of results.