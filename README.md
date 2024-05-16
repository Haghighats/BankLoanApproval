# **Bank Loan Approval** <br>
Python project for classifying loan eligibility of bank customers using various classification algorithms. <br>
In this repository, I am going to publish one of my notebooks about classification tasks in Python. In total, I used 3 of the most common ML algorithms; Logistic regression, naive bayes and KNN to divide the customers of a bank according to their possibility of accepting a loan. You can find the details below. <br>

In this notebook, there was information of 5000 customers of a bank in California. Different information of each customer was reported and the target was to make a machine learning model that can accurately predict whether a specific customer gets a loan or not. Steps of data analysis include: <br>
## **a) importing and reading the dataset** <br>
I employed numpy and pandas as my go-to tools for delving into the dataset. For visualization purposes, I utilized matplotlib and Seaborn. Additionally, SciKit Learn provided the models I needed for ML modeling. <br>
## **b) Data Cleaning:** <br>  
no missing or duplicate values were found. However, there was a minor issue with one of the columns, CCAvg. The “/” symbol was used instead of “.”, which made a confusion in the model and caused it to read each value as an object type unique value instead of continuous numbers. Data type conversion and correcting the symbol was done accordingly. <br>
## **c) Exploratory Data Analysis:** <br> 
bar chart, pie chart, and histogram were used to show the distribution of columns. Also, data was extracted from the zip code column, which showed the location information of customers. <br>
## **d) Data Preparation:** <br> 
I prepared the data for modeling by converting all columns to numeric format and normalizing the data using the min-max scaler method.  <br>
## **e) Machine Learning Modeling:** <br> 
For the machine learning modeling, I employed logistic regression, Naïve Bayes, and KNN. KNN exhibited the highest performance with an accuracy of over 0.96, while logistic regression also performed well. However, Naïve Bayes yielded lower accuracy at 0.88.
