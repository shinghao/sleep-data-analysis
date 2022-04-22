# Welcome to sleep-data-analysis repository
This is our Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence).

## Contributors
- [shinghao](https://github.com/shinghao) (Soh Shing Hao) - Data Preparation & Cleaning, Exploratory Analysis and Presentation
- [leechunyang98](https://github.com/leechunyang98) (Lee Chun Yang) - Data Resampling, Machine Learning Models
- [czhi-heng](https://github.com/czhi-heng) (Cheung Zhi Heng) - Data Analysis, Organisation and Presentation 

## Practical Motivation
We are often told that we need at least 7 hours of sleep to be well-rested. However, we often still feel tired and unsufficiently rested even after sleeping for at least 7 hours. Are other variables apart from the duration of our sleep affecting our sleep quality?

## Problem Definition
**Can we predict a person's sleep quality using information on his sleep cycle, the time he goes to sleep, and his activities throughout the day?**

We will only use data where the person has slept for at least 7 hours.

## Dataset Source
The dataset we will be using is the Sleep Data dataset created and shared by Dana Diotte on Kaggle. The sleep data dataset consists only of Dana Diotte's own sleep information which he accquired between 2014-2018 and collected through the Sleep Cycle app from Northcube on iOS. The dataset can be found here: https://www.kaggle.com/danagerous/sleep-data

## Machine Learning Models Used
1. Linear Regression
2. Random Forest
3. Polynomial Regression
4. K-nearest Neighbour
5. Gradient Boosting Decision Tree
6. Histogram-Based Gradient Boosting
7. AdaBoost

## Sampling Methods
1. Random Sampling
2. K-Folds
3. Repeated K-Folds

## Conclusion

## Recommendations
- Create a more balanced response variable through methods such as resampling. This is because for our model, the response variable, `Sleep quality`, is more skewed towards the right (representing higher sleep quality).
- Collect more data as the data may become too small to measure the actual accuracy of the models. 
- Since this data is only about one person, it may be biased and hard to make accurate analysis of the information being given. It will be better to have a specific range/group of sleep information to give.(Continuation of point 2) Or a specific research centre/sleep centre of information to analyse will generate more interesting insights. 
- Consider other variables such as sleep environment or sleep problems such as insomnia. 

## What Did We Learn?
- Random Forest Model
- Polynomial Regression
- Encoding Categorical data with Label Encoding
- Sampling data with K-Folds and repeated K-Folds
- Representing data in time-series

## References
- https://towardsdatascience.com/getting-started-with-xgboost-in-scikit-learn-f69f5f470a97 
- https://machinelearningmastery.com/gradient-boosting-with-scikit-learn-xgboost-lightgbm-and-catboost/
- https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
- https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.PolynomialFeatures.html
- https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html#sklearn.ensemble.HistGradientBoostingRegressor
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostRegressor.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RepeatedKFold.html
