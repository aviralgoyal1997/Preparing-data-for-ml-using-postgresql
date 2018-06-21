# Preparing-data-for-ml-using-postgresql
We all know before applying model on data we always do filtering like data cleaning,feature extraction,etc.In last we have useful data to be given to model.

Suppose our dataset is so big and even more worse that we have dataset divided into multiple big  csv files then its not efficient to load whole data into dataframes and work on it using pandas,in such case we use relational databases.We gonna load each of csv files into sql and gonna write queries to work on them and in last will export useful dataset into csv file.

We gonna see a example using LIVES dataset.
Data link : https://download.data.world/download/louisville/yelp-data   *remove blank columns from cs files in this data<br>
Reference : https://blog.bigml.com/2013/10/30/data-preparation-for-machine-learning-using-mysql/
