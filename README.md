# Welcome to sleep-data-analysis repository

## Contributors
- @shinghao - Data Preparation & Cleaning, Exploratory Analysis
- @leechunyang98 - Data Resampling, Machine Learning Models

## Practical Motivation
We are often told that we need at least 7 hours of sleep to be well-rested. However, we often still feel tired and unsufficiently rested even after sleeping for at least 7 hours. Are other variables apart from the duration of our sleep affecting our sleep quality?

## Problem Definition
**Can we predict a person's sleep quality using information on his sleep cycle, the time he goes to sleep, and his activities throughout the day?**

We will only use data where the person has slept for at least 7 hours.

## Dataset
The dataset we will be using is the Sleep Data dataset created by Dana Diotte. The sleep data dataset consists only of Dana Diotte's own sleep information which he accquired between 2014-2018 and collected through the Sleep Cycle app from Northcube on iOS.

## Machine Learning Models Used
1. Linear Regression
2. Random Forest
3. Polynomial Regression

## Sampling Methods
1. Random Sampling
2. K-Folds
3. Repeated K-Folds

## Conclusion

## Recommendations
- Create a more balanced response variable through methods such as resampling. This is because for our model, the response variable, `Sleep quality`, is more skewed towards the right (representing higher sleep quality).
- Collect more data as the data may become too small to measure the actual accuracy of the models. 
- Since this data is only about one person, it may be biased and hard to make accurate analysis of the information being given. It will be better to have a specific range/group of sleep information to give.(Continuation of point 2) Or a specific research centre/sleep centre of information to analyse will generate more interesting insights. 
- We do need to consider external factors and internal factors towards the person, to have a more accurate information. Such as sleep environment or sleep problems like insomnia which can determine sleep quality more accurately. 

## What Did We Learn?
- Random Forest Model
- Polynomial Regression
- Sampling data with K-Foldss and repeated K-Folds
- Representing data in time-series

## References
- https://towardsdatascience.com/getting-started-with-xgboost-in-scikit-learn-f69f5f470a97 
- https://machinelearningmastery.com/gradient-boosting-with-scikit-learn-xgboost-lightgbm-and-catboost/
- https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
- https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.PolynomialFeatures.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RepeatedKFold.html
