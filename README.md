# Analyzing 10Gb of Yelp Reviews Data
## STA9760-Project2-YelpData-Analysis
I will analyze a subset of Yelp's business, reviews and user data. The dataset came from Kaggle then taken steps to pull this data into a publis s3 bucket:`https://sta9760-yelp-datasets.s3.us-east-2.amazonaws.com/`

note: screenshot of s3 bucket can be found in conf folder - named bucketsc.png

### URL links to each individual dataset
Business subset: https://sta9760-yelp-datasets.s3.us-east-2.amazonaws.com/yelp-business/yelp_academic_dataset_business.json

Review subset: https://sta9760-yelp-datasets.s3.us-east-2.amazonaws.com/yelp_academic_dataset_review.json

User subset: https://sta9760-yelp-datasets.s3.us-east-2.amazonaws.com/yelp-user/yelp_academic_dataset_user.json



## EMR cluster configuration and Notebook configuration.
Setup of clusters and notebook is needed before any analysis. See below for configuration:

![alt text](conf/Yelp-EMR-Cluster-Conf.png)

![alt text](conf/Yelp-NB-Conf.png)

## Analysis.ipynb
Refer to the Analysis notebook
