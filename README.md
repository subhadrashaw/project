# project
House Price Prediction Model

Goal :
To predict the price of the house.

Problem Statement :
The goal is to understand the relationship between house features and how these variables affect the house price. Using more than one model, predict the price of the house using the given dataset. Compare the accuracy of the models and recommend the final prediction model.

This project has following parts :

Exploratory Data Analysis (EDA) : Data is pre processed to find the co-relation or patterns between the given features and the target value i.e. price of the house. report.html is generated using the sweetviz tool which is used to show the distribution of different features along with their maximum, minimum and average values. The co-relation among data is shown using heatmap.

Data Pre-Processing : In this part the longitude and latitude features are precessed to find the address or location (road, city, state, country, pin code) of the house using geopy library. The road column is added to the dataset rest are ignored because the dataset contains house from same city. So the other part of the address will not impact the target value. The null values of road column are filled using Linear Regression model.

Understanding which model to use: In the last section three machine learning algortihms are used to predict the house price. They are- Support Vector Machine, Random Forest Regression and Linear Regression. Accuracy is evaluated using mean_absolute_percentage_error and R2 score metrics. 

Conclusion - The accuracy values show that Random Forest Regression method performs the best.


Dataset Attributes :
Dataset contains 9 columns and 414 rows with CSV extension. The data contains the following columns : 

1. Transaction date
2. House Age	
3. Distance from nearest Metro station (km)	
4. Number of convenience stores	
5. latitude	
6. longitude	
7. Number of bedrooms	
8. House size (sqft)	
9. House price of unit area

Tools and Algorithms Used for Analysis :
Python, Numpy, Pandas, sklearn, Linear Regression, RandomForestRegressor, svm

References :
Datasets - DS - Assignment Part 1 data set.xlsx (attached)
