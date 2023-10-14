# Project--Hadoop-6

<table>

 **In this project we use Apache Spark and we make an amazing Movie Recommendation using this ADLS of Apache Spark which which is built on top of hadoop**.<br></br>
 Here we try to predict ratings for User 0 which is first three rows in u.data for getting top 20 movies prediction by User 0 on the basis of training of our ALS model and then testing it
 on User 0 for movie recommendation.
 
  **This dataset contains 4 columns:** <br></br>
  **(UserId):** The user id of person who rated the movie<br></br>
  **(Movie-Id):** The movie id of movie which users rated<br></br>
  **(Ratings):** The ratings which the user gave to the given movie<br></br>
  **(Timestamp):** The time at which the user rated the given movie<br></br>

**Here we make use of**:<br></br>
Collaborative filtering is commonly used for recommender systems. 
These techniques aim to fill in the missing entries of a user-item association matrix. spark.ml currently supports model-based collaborative filtering, in which users and products are described by a small set of latent factors that can be used to predict missing entries. spark.ml uses the alternating least squares (ALS) algorithm to learn these latent factors. 
  
Apache Spark is a multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.
It is an open-source, distributed processing system used for big data workloads. It utilizes in-memory caching, and optimized query execution for fast analytic queries against data of any size.<br></br>
Apache Spark is a data processing framework that can quickly perform processing tasks on very large data sets, and can also distribute data processing tasks across multiple computers, either on its own or in tandem with other distributed computing tools. These two qualities are key to the worlds of big data and machine learning, which require the marshalling of massive computing power to crunch through large data stores.<br></br>
Spark also takes some of the programming burdens of these tasks off the shoulders of developers with an easy-to-use API that abstracts away much of the grunt work of distributed computing and big data processing.
From its humble beginnings in the AMPLab at U.C. Berkeley in 2009, Apache Spark has become one of the key big data distributed processing frameworks in the world.<br></br> Spark can be deployed in a variety of ways, provides native bindings for the Java, Scala, Python, and R programming languages, and supports SQL, streaming data, machine learning, and graph processing. You’ll find it used by banks, telecommunications companies, games companies, governments, and all of the major tech giants such as Apple, IBM, Meta, and Microsoft.<br></br>
At the heart of Apache Spark is the concept of the Resilient Distributed Dataset (RDD), a programming abstraction that represents an immutable collection of objects that can be split across a computing cluster. Operations on the RDDs can also be split across the cluster and executed in a parallel batch process, leading to fast and scalable parallel processing.<br></br>
Apache Spark turns the user’s data processing commands into a Directed Acyclic Graph, or DAG. The DAG is Apache Spark’s scheduling layer; it determines what tasks are executed on what nodes and in what sequence.<br></br>

 **Important-Note: Go through the dataset before going to the code.**

</table>


**So what are you waiting for..? Jump to the code to get started and learn to make this amazing project using MapReduce. As usual for any doubt or query see you in pull request section 😁😂. Thanks Again!**
