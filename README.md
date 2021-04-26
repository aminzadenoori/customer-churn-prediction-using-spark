# Customer Churn Prediction with Apache Spark
predict customer churn by the help of machine learning models is a prevelant problem data scientists are often try to handle in every buisness. In the current project a machine learning model is utlized to predict customer churn. To be able to use the model not only on small datasets, but also on "big data", I have used Apache Spark's machine learning library MLlib and PySpark.

## Data and project
This project is the capstone project of Udacity's Data Scientist Nanodegree. The users and log data of a fictitious music streaming service called "Sparkify" serve as a database. The dataset contains 286,500 rows and 18 features. 

Corresponding blog post: https://amin-zadenoori.medium.com/customer-churn-prediction-using-spark-and-mlib-47fac0dc7e38

## Machine Learning Pipeline
In this following classification algorithm is trained and evaluated in order to predict customer churn:Random Forest, Gradient Boosting . For this a Machine Learning pipeline is set up, which contains the steps below:
- Load Data
- Create Features
- Feature Scaling (Min-Max Normalization)
- Train-Test Split
- Cross Validation & Grid Search Hyperparameter Tuning
- Training of Machine Learning Model
- Evaluation of Prediction Performance (Metric: F1 Score)

## Model Performance
Of the tested models `Gradient Boosting` achieved results:
- precision: 0.97,
- recall: 0.97, 
- f1:  0.975, 
- accuracy: 0.9642



## Dependencies
- Python 3
- Spark's Machine Learning Library MLlib
- PySpark
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Datetime
