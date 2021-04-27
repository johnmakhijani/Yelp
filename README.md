# CIS9760 Project 2 
## _Analyzing 10Gb of Yelp Reviews Data_
by John Makhijani CIS9760 Big Data Technologies Spring 2021

This project consists on a dataset of Yelp’s businesses, reviews, and user data. The datasets are saved in JSON format. In total there are over 8.6 million user reviews with information on 160,000 business. All the data sets combined exceeds 10GB of data in five datasets.
- Business
- User
- Review
- Tip
- Checkin

I have worked with the Businessm Review and User datasets 

Conducted analysis in Python with the use of AWS EMR Cluster and Jupyter Notebook
-  Provisioned a Spark cluster on AWS EMR
[![cluster_image](https://github.com/johnmakhijani/Yelp/blob/fe07c9efee43824f616d01ebfbae80f6da02138c/cluster_configuration.png?raw=true)]
-  Connect it to a Jupyter Notebook
[![notebook_image](https://github.com/johnmakhijani/Yelp/blob/fe07c9efee43824f616d01ebfbae80f6da02138c/notebook_configuration.png?raw=true)]

-  Ran a series of queries (in python with DataFrame API and/or Spark SQL) 

[![Top Business Categories](https://github.com/johnmakhijani/Yelp/blob/cdadca41ef93adee1e2721e80e31d15ff4356d36/Bus_Cat.png?raw=true)] - Top Business Categories that get reviewed

[![Top User Categories](https://github.com/johnmakhijani/Yelp/blob/cdadca41ef93adee1e2721e80e31d15ff4356d36/User_Cat.png?raw=true)] - Top Categories the Users review

[![User Review Skew](https://github.com/johnmakhijani/Yelp/blob/cdadca41ef93adee1e2721e80e31d15ff4356d36/Skew.png?raw=true)] - Negative Review Skew of Users

[Yelp Dataset](https://www.kaggle.com/yelp-dataset/yelp-dataset) - Data source on Kaggle
[John Github](https://github.com/johnmakhijani/t) - John Makhijani Github
