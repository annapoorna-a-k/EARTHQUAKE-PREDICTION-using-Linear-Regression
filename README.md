# EARTHQUAKE-PREDICTION-using-Linear-Regression
Earthquake Prediction is a way of predicting magnitude of earthquake based on parameters such as longitude, latitude, depth, and duration magnitude, country, depth using machine learning to give warning of potentially damaging earthquakes early enough to allow appropriate response to the disaster, enabling people to minimize loss of life and property.
The steps we have taken here are:
Preparing the dataset
Building a model with Linear Regression
Visualization with Matplotlib and Seaborn
With the help of Python and suitable machine learning algorithms, we can create prediction models and graph the data as we want. In this project, one of the parameters of the earthquake data as a csv file is predicted with the help of Linear Regression, an algorithm of Machine Learning.

#Dataset Information
Earthquake data can be taken from :
https://www.kaggle.com/datasets/caganseval/earthquake

Here we used Turkey's earthquake data and one of the occured earthquakes in Kocaeli in 2007 that has maximum magnitude 4.0 is guessed as 4.05 with linear regression. In order to generate training and test data, other variables like longitude, latitude, depth, and duration magnitude are also used.

The parameters are:
Id: order number of the earthquake
Date: earthquake occurrence date
Time: time of the earthquake
Lat: latitude of the earthquake epicenter
Long: longitude of the earthquake epicenter
Country: country of the earthquake epicenter
City: province of the occurred earthquake
Area: region of the occurred earthquake
Direction: direction of the earthquake signal
Dist: district of the occurred earthquake
Depth: depth of the occurred earthquake (distance from the surface)
Xm: the largest of the given magnitude values
Md: magnitude depending on time
Richter: Richter magnitude or the local magnitude (ML)
Mw: moment magnitude
Ms: surface wave magnitude
Mb: body wave magnitude
