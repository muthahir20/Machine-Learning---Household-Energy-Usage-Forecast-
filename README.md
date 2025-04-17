# Machine-Learning-Household-Energy-Usage-Forecast

#Problem Statement:
In the modern world, energy management is a critical issue for both households and energy providers. Predicting energy consumption accurately enables better planning, cost reduction, and optimization of resources. The goal of this project is to develop a machine learning model that can predict household energy consumption based on historical data. Using this model, consumers can gain insights into their usage patterns, while energy providers can forecast demand more effectively.

#Packages used:

`'import numpy as np'` </br>
`'import seaborn as sns'` </br>
`'import matplotlib.pyplot as plt'` </br>
`'import pandas as pd'` </br>
`from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score` </br>
`from sklearn.linear_model import LinearRegression` </br>
`from sklearn.ensemble import RandomForestRegressor, GradientBoostingRegressor` </br>
`from sklearn.neighbors import KNeighborsRegressor` </br>
`from sklearn.tree import DecisionTreeRegressor` </br>

#Steps Followed in this Project
1. Get the data from the link: [https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption]
2. Get the info about the data frame and check for updation.
3. Changing unnecessory symbols from all the columns.
4. Update necessory data type of the columns.
5. Find the outliers in the numeric columns.
6. Handle the outliers with IQR method.
7. Split the testing and training data set.
8. Define the models for training.
9. Find the MEA, RMSE and R-Squared tests.
10. Find the best model among all defined models by evaluating the model.
11. Then find the Feature Importance for finding the best feature for prediction of model.

