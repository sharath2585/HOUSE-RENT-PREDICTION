HOUSE  RENT PREDICTION
---------------------------------------------------------------------------------------------------------------
The rent of a house depends on a lot of factors. With appropriate data and Machine Learning techniques, many real estate platforms find the housing options according to the customer’s budget. So, if you want to learn how to use Machine Learning to predict the rent of a house, this article is for you. In this article, I will take you through the task of House Rent Prediction with Machine Learning using Python.
House Rent Prediction
The rent of a housing property depends on a lot of factors like:

Number of bedrooms, hall, and kitchen
size of the property
the floor of the house
area type
area locality
City
furnishing status of the house
To build a house rent prediction system, we need data based on the factors affecting the rent of a housing property.
The model is based on Random forest regression.
---------------------------------------------------------------------------------------------------------------
RANDOM FOREST REGRESSION
---------------------------------------------------------------------------------------------------------------
A Random forest regression is a supervised learning algorithm used to predict values depend on several factors by using several decesion trees.
Random Forest is an ensemble technique capable of performing both regression and classification tasks with the use of multiple decision trees and a technique called Bootstrap and Aggregation, commonly known as bagging. The basic idea behind this is to combine multiple decision trees in determining the final output rather than relying on individual decision trees. 

Random Forest has multiple decision trees as base learning models. We randomly perform row sampling and feature sampling from the dataset forming sample datasets for every model. This part is called Bootstrap.
We need to approach the Random Forest regression technique like any other machine learning technique 

>> Design a specific question or data and get the source to determine the required data.
>> Make sure the data is in an accessible format else convert it to the required format.
>> Specify all noticeable anomalies and missing data points that may be required to achieve the required data.
>> Create a machine-learning model.
>> Set the baseline model that you want to achieve
>> Train the data machine learning model.
>> Provide an insight into the model with test data
>> Now compare the performance metrics of both the test data and the predicted data from the model.
>> If it doesn’t satisfy your expectations, you can try improving your model accordingly or dating your data, or using another data modeling technique.
>> At this stage, you interpret the data you have gained and report accordingly.
---------------------------------------------------------------------------------------------------------------
IMPLEMENTATION
---------------------------------------------------------------------------------------------------------------
Step 1: Import the required libraries.
Step 2: Import and print the dataset .
Step 3: Select all rows and column 1 from dataset to x and all rows and column 2 as y. 
Step 4: Fit Random forest regressor to the dataset.
Step 5: Predicting a new result.
Step 6: Visualising the result.
---------------------------------------------------------------------------------------------------------------
Advantages:
---------------------------------------------------------------------------------------------------------------
It is easy to use and less sensitive to the training data compared to the decision tree.
It is more accurate than the decision tree algorithm.
It is effective in handling large datasets that have many attributes.
It can handle missing data, outliers, and noisy features.
---------------------------------------------------------------------------------------------------------------
Disadvantages:
---------------------------------------------------------------------------------------------------------------
The model can also be difficult to interpret.
This algorithm may require some domain expertise to choose the appropriate parameters like the number of decision trees, the maximum depth of each tree, and the number of features to consider at each split.
It is computationally expensive, especially for large datasets.
It may suffer from overfitting if the model is too complex or the number of decision trees is too high.
---------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------
                        ----------------THE END-----------------                                               
---------------------------------------------------------------------------------------------------------------
                        ---------------THANK YOU----------------                           
---------------------------------------------------------------------------------------------------------------
