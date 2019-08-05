# Analysis-on-the-the-number-of-emergency-911-calls-made-in-United-States-of-America
Data Visualization

United States of America, one of the world’s largest superpower is not only leading in its businesses and exports but also is one of the leading nations in the number of crimes that occur every hour, every day just like mass shootings, killings etc.Our aim for the project will be built on the the number of 911 calls made by US citizens and the type of 911 calls made. The project dataset will be inspired from kaggle.com. At first, we will be preprocessing data based on some tools like Python,Oracle Desktop to check for the format and the legibility of the data present. This will be followed by a critical analysis of the data processed such as to check for the coordinates where calls are frequent, to check the type of issues citizens face and the daily troubles of the American Society. After this we will be going to implement a prediction setup to visualize and predict the possibilities of new kinds of problems that may arise in future. Also our project could put forth some suggestions about specific regions where the crimes are at an alarming rate and ways to caution the citizens of those areas in being involved in such events.






i. Dataset Used


We have used a dataset that contains the information of the number of 911 calls made in the duration of 3 years between 2015- 2018.The dataset consists of the details of the different kinds of helpline calls made by the citizens regarding any traffic, emergency services for health related issues and fire calls.This dataset does contain some missing values like the zip section latitude section. So we have preprocessed the dataset using the script that either ignores the record or finds the zip code of any missing record by its latitude and longitude.We have added the category column of the type incident occurred according to its type in the pre-processed dataset.
 
Prediction Model used - Gradient Boosting Regressor

Gradient boosting is a machine learning regression and classification problems which produces a prediction model in the form of weak prediction models. In our dataset, it is quite difficult and tough to predict the exact location and the exact type of incident to happen as they depend on climatic, psychological and political factors which makes the above prediction technique the best possible prediction model for the issue.

Visualisation of the prediction

This Visualisation shows the prediction of the number of events made of a specific date(20-05-2016). The blue line indicates the predicts the calls that will be made on that date. And the orange dataset shows the number of calls made on that day in the trained dataset.
