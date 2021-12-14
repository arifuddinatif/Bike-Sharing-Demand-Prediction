


![App Screenshot](https://storage.googleapis.com/kaggle-competitions/kaggle/3948/media/bikes.png)




## Inrtoduction
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


 


## Problem statement

We are tasked with predicting the number of bikes rented each hour so as to make an approximate estimation of the number of bikes to be made available to the public given a particular hour of the day.




## Overview of the data
We are given the following columns in our data:
1. Date : year-month-day
2. Rented Bike count - Count of bikes rented at each hour
3. Hour - Hour of the day
4. Temperature-Temperature in Celsius
5. Humidity - %
6. Wind Speed - m/s
7. Visibility - 10m
8. Dew point temperature - Celsius
9. Solar radiation - MJ/m2
10. Rainfall - mm
11. Snowfall - cm
12. Seasons - Winter, Spring, Summer, Autumn
13. Holiday - Holiday/No holiday
14. Functional Day - No(Non Functional Hours), Yes(Functional hours)


## Steps involved
1. Installing libraies and getting the dataset.
2. Performing EDA (exploratory data analysis).
3. Drawing conclusions from the data.
4. Preprocessing the data.
5. Training different models.
6. Evaluating metrics of all the models.

## Algorithms used
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Extra Trees Regressor

## Conclussion
We used R2-score to understand which model fit our data better, and the scores are as follows:
1. Linear Regression - 0.515109
2. Decision Tree Regressor - 0.795209
3. Random Forest Regressor - 0.844341
4. Extra Trees Regressor - 0.852685

Its evident from above that the Extra trees regressor model performed well in fitting the data with R2-score of 0.852685. The model which performed poorly was elastic net regularization with R2-score of 0.42.
