# Higgs-Twitter-Analysis-Using-PySpark-DataBricks

This is small project to perform the Extract, Transform & Load of the HIGGS Twitter Data using Pyspark in DataBricks Environment. The dataset used for this project is in CSV format (Compressed with GZLIB). We have also carried out some performance testing to showcase how Pyspark work best with Parquet format as compare to other formats.

## ETL with PySpark SQL

HIGGS Tweeter Database
The Higgs dataset has been built after monitoring the spreading processes on Twitter before, during and after the announcement of the discovery of a new particle with the features of the elusive Higgs boson on 4th July 2012. The messages posted in Twitter about this discovery between 1st and 7th July 2012 are considered.

The four directional networks made available here have been extracted from user activities in Twitter as:

- re-tweeting (retweet network)
- replying (reply network) to existing tweets
- mentioning (mention network) other users
- friends/followers social relationships among user involved in the above activities
- information about activity on Twitter during the discovery of Higgs boson

It is worth remarking that the user IDs have been anonimized, and the same user ID is used for all networks. This choice allows to use the Higgs dataset in studies about large-scale interdependent/interconnected multiplex/multilayer networks, where one layer accounts for the social structure and three layers encode different types of user dynamics .

Note that this dataset has been updated on Mar 31 2015. If you downloaded a previous version, please update it, results could differ.

Dataset Link:- http://snap.stanford.edu/data/higgs-twitter.html


 
