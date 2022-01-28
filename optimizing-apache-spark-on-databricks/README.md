## Course Description
In this course, students will explore five key problems that represent the vast majority of performance problems in an Apache Spark application: Skew, Spill, Shuffle, Storage, and Serialization. With each of these topics, we explore coding examples based on 100 GB to 1+ TB datasets that demonstrate how these problems are introduced, how to diagnose these problems with tools like the Spark UI, and conclude by discussing mitigation strategies for each of these problems.

We continue the conversation by looking at a series of key ingestion concepts that promote strategies for processing Tera Bytes of data including managing Spark-Partition sizes, Disk-Partitioning, Bucketing, Z-Ordering, and more. With each of these topics, we explore when and how each of these techniques should be implemented, new challenges that productionalizing these solutions might provide along with corresponding mitigation strategies.

Finally, we introduce a couple of other key topics such as issues with Data Locality, IO-Caching and Spark-Caching, Pitfalls of Broadcast Joins, and new features like Spark 3’s Adaptive Query Execution and Dynamic Partition Pruning. We then conclude the course with discussions and exercises on designing and configuring clusters for optimal performance given specific use cases, personas, the divergent needs of various teams, and cross-team security concerns.

## Learning Objectives

+ Articulate how the five most common performance problems in a Spark application can be mitigated to achieve better application performance.
+ Summarize some of the most common performance problems associated with data ingestion and how to mitigate them.
+ Articulate how new features in Spark 3.0 can be employed to mitigate performance problems in your Spark applications.
Configure a Spark cluster for maximum performance given specific job requirements and while considering a multitude of other factors.
