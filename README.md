# Building-LInearRegression_Model
Building the linear Regression Model, Using the sklearn dataset of diabetes patient. The purpose is to understand the Linear Regression Model.
Importing libaries with dataset for sklearn
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
from sklearn import datasets, linear_model
diabetes = datasets.load_diabetes()
from sklearn.metrics import mean_squared_error
Loading the dataset from sklearn of daibetes
The dataset is quite big with different features and labels.We will only use one feature and label. With 30 rows each for training and testing. 
We took 30 row for training and testing. Similarly we have to take same amount and same position of data for label too because they are corresponds to features
Choosing Model and importing model and using model.fit for training adn setting parameters for training, prediction.
Calculating Error by using Mean square error, use the function of model.intercept_ to know the intercept value to see our model prediction is right or not
Use model.coef_ function to measure the weight od model.
In the end we use scatter plot to visualise our model prediction.We using the line to decrease the error
END
