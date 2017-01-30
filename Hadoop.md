Intro to Big Data with Hadoop
==================

Brought to you by [Lesley Cordero](http://www.columbia.edu/~lc2958).

## Table of Contents

- [0.0 Setup](#00-setup)
	+ [0.1 R and R Studio](#01-r-and-r-studio)
	+ [0.2 Packages](#02-packages)
- [1.0 Background](#10-background)
	+ [1.1 Machine Learning](#11-Machine Learning)
	+ [1.2 Data](#12-data)
	+ [1.3 Overfitting vs Underfitting](#13-overfitting-vs-underfitting)
	+ [1.4 Glossary](#14-glossary)
		* [1.4.1 Factors](#141-factors)
		* [1.4.2 Corpus](#142-corpus)
		* [1.4.3 Bias](#143-bias)
		* [1.4.4 Variance](#144-variance)
- [2.0 Data Preparation](#30-data-preparation)
	+ [2.1 dplyr](#31-dplyr)
	+ [2.2 Geopandas](#32-geopandas)
- [3.0 Exploratory Analysis](#30-exploratory-analysis)
- [4.0 Data Visualization](#50-data-visualization)
- [5.0 Machine Learning & Prediction](#50-machine-learning--prediction)
	+ [5.1 Random Forests](#51-random-forests)
	+ [5.2 Natural Language Processing](#52-natural-language-processing)
		* [5.2.1 ANLP](#521-anlp)
	+ [5.3 K Means Clustering](#53-k-means-clustering)
- [6.0 Final Exercise]($60-final-exercise)
- [7.0 Final Words](#60-final-words)
	+ [7.1 Resources](#61-resources)
	+ [7.2 More!](#72-more)


This guide was written in R 3.2.3.


### 0.1 R and R Studio

Download [R](https://www.r-project.org/) and [R Studio](https://www.rstudio.com/products/rstudio/download/).


### 0.2 Packages


```
install.packages("")
```

## 1.0 Background

Hadoop is an Apache Software Foundation project. It is the open source version inspired by Google MapReduce and Google File System. It's designed for distributed processing of large data sets across a cluster of systems often running on commodity standard hardware. Hadoop is designed with an assumption that all hardware fails sooner or later and the system should be robust and able to handle the hardware failures automatically.

Apache Hadoop consists of two core components:


### 1.1 HDFS

Distributed File System called Hadoop Distributed File System.


### 1.2 MapReduce

Framework and API for MapReduce jobs. MapReduce is a software framework or programming model, which enable users to write programs so that data can be processed parallelly across multiple systems in a cluster. MapReduce consists of two parts: 


#### 1.2.1 Map 

Map task is performed using a `map()` function that basically performs filtering and sorting. This part is responsible for processing one or more chunks of data and producing the output results which are generally referred as intermediate results. As shown in the diagram below, map task is generally processed in parallel provided the maping operation is independent of each other.


#### 1.2.2 Reduce

Reduce task is performed by `reduce()` function and performs a summary operation. It is responsible for consolidating the results produced by each of the Map task.




## 5.0 Final Words


### 5.1 Resources

[]() <br>
[]()
