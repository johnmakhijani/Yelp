# Analysis of Yelp Business Intelligence Data
## _Analyzing 10Gb of Yelp Reviews Data_
by John Makhijani Spring 2021

This project consists of analysis of datasets of Yelp’s businesses, reviews, and user data. In total there are over 8.6 million user reviews with information on 160,000 business from 9+ markets in US / Canada. All the data sets combined exceed 10GB of data over five datasets.
- Business Dataset
- User Dataset
- Review Dataset
- Tip Dataset
- Checkin Dataset

The datasets are saved in JSON format. I primarily worked with the Business, Review and User datasets 

Conducted analysis in Python with the use of an AWS EMR Cluster and Jupyter Notebook
-  Provisioned a Spark cluster on AWS EMR
[![cluster_image](https://github.com/johnmakhijani/Yelp/blob/fe07c9efee43824f616d01ebfbae80f6da02138c/cluster_configuration.png?raw=true)](https://github.com/johnmakhijani/Yelp/blob/fe07c9efee43824f616d01ebfbae80f6da02138c/cluster_configuration.png?raw=true)
-  Connect it to a Jupyter Notebook
[![notebook_image](https://github.com/johnmakhijani/Yelp/blob/fe07c9efee43824f616d01ebfbae80f6da02138c/notebook_configuration.png?raw=true)](https://github.com/johnmakhijani/Yelp/blob/fe07c9efee43824f616d01ebfbae80f6da02138c/notebook_configuration.png?raw=true)

-  Ran a series of queries (in python with DataFrame API and/or Spark SQL) 

Sample Vizualizations:

[![Top Business Categories](https://github.com/johnmakhijani/Yelp/blob/b3f85e7686e689ed4be05928319879dba6fea3d9/Bus_Cat.png?raw=true)](https://github.com/johnmakhijani/Yelp/blob/b3f85e7686e689ed4be05928319879dba6fea3d9/Bus_Cat.png/Bus_Cat.png?raw=true)

[![Top User Categories](https://github.com/johnmakhijani/Yelp/blob/b3f85e7686e689ed4be05928319879dba6fea3d9/User_Cat.png?raw=true)](https://github.com/johnmakhijani/Yelp/blob/b3f85e7686e689ed4be05928319879dba6fea3d9/User_Cat.png?raw=true)

[![User Review Skew](https://github.com/johnmakhijani/Yelp/blob/b531517ec7e60fb09c4f4c2a63ddba1a7a1e2c33/Skew.png?raw=true)](https://github.com/johnmakhijani/Yelp/blob/b531517ec7e60fb09c4f4c2a63ddba1a7a1e2c33/Skew.png?raw=true)

[Yelp Dataset](https://www.kaggle.com/yelp-dataset/yelp-dataset) - Data source on Kaggle
[John Github](https://github.com/johnmakhijani/) - John Makhijani Github
