# Diamons-Project

The project consists of achieving the best prediction based on different Machine Learning algorithms.


### Steps to follow:
1. We download the Kaggle dataset. Having 2 datasets. The first, the train.csv is the one we use at all times to train our models and predict the prices of each one. Once trained, we use the test.csv , where is the same dataset but without the price column and is where we add our predicted prices. 

2. First of all, I clean the train.csv, change the columns from color, cut and clarity to numeric values. 

3.  I train the dataset with the following algorithms:
- Simple linear regression
- Random Forest regression
- Boosting regression
- Knn Neighbors
- Random Forest with Grid search

4. Once I have all the predicted prices of each model, I keep the "id" and "price" column to see it in a more visual way.
