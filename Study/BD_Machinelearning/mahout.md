#***Mahout Manual***

##Installation

###*1. On IntelliJ*

- Install *org.apache.mahout:mahout-mr:0.11.2*
- Install *org.apache.mahout:mahout-spark_2.10:0.11.2*

Since version 0.10+ mahout-core is refractored into *mahout-hdfs* and *mahout-mr*.
Therefore, you need to choose above libs instead of mahout-core.

##Recommender Algorithms

###**[Disclaimer]**

*content-based filtering (CBF)* is not provided in Mahout. It only provided algorithms based on *collaborative filtering (CF):*

- User-Based Collaborative Filtering		
- Item-Based Collaborative Filtering
- Matrix Factorization with ALS			
- Matrix Factorization with ALS on Implicit Feedback
- Weighted Matrix Factorization, SVD++
