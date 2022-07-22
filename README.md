# Flight-Fare-Prediction

## Problem Statement

This project is about using different machine learning algorithms to determine the price of flight tickets. There are different attributes which affect the price of flight tickets which are departure date and time , arrival date and time , source city and the destination city , the number of stops and the different airlines prefered by people.

## Approach
1. Data Exploration : Getting an idea about the data , type of features , number of categorical and numerica variables and creating plots to get a better understanding of the data.
2. Feature Engineering : Converting the categorical variables into numeric variables using One hot encoding and Label Encoder.
3. Feature Scaling : Transforming the data into Gaussian Normal Distribution.
4. Feature Selection : Selecting the important features and discarding the features which have a high VIF(Variance Inflation Factor) value.
5. Model Training and Testing : Multiple regression models are being built using different ML algorithms and the one with best accuracy is selected.
6. Hyperparameter Tunning : Random Forest Regressor was selected for predicting the outcome , and it was tunned using differnt parameters to get a better accuracy.

## Technologies used
1. Python
2. numpy
3. matplotlib
4. seaborn
5. pandas
6. sklearn
7. Pyspark
