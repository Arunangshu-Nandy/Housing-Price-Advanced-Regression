
In this problem I use various ML model to check for best fitted model. Work is broken down as per below list-

1.	Understand the shape of the data (drop sales price column, check for null values, explore unique values)

2.	Data Cleaning (removal of rows where very less number of unique values are there in train dataset. We also checked if the same are there in test dataset)

3.	Data Exploration ()

4.	Feature Engineering (we explore per sq feet rate/area, and in doing so we look for –

a.	Per SqFT rate of an N BHK cannot be more than N+1, in same neighbourhood. 
b.	Total SqFT area of N BHK cannot be more than N+1)

5.	Data Processing for Model (imputation & create dummies for object columns )

6.	Basic Model Building (evaluate results for different models)

7.	Result Submission in Kaggle (link shared below)


Data source-Kaggle dataset (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

Work Submission link in Kaggle-( https://www.kaggle.com/code/arunangshukumarnandy/housing-submissio-rev-0-date-01-12-2022)
