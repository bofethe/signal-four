# Predictive Analysis of Crash Incidents in Hillsborough County
This repository analyzes crash data in Hillsborough County, Florida and uses various machine learning models to predict the probablity of an incapacitating event occuring.  The training data was obtained from Signal Four Analytics and filtered to all crash events in Hillsborough County in 2023. To view this data spatially, visit the interactive map in ArcGIS Online found [here](https://experience.arcgis.com/experience/131319e3bac346e8a3054e43ba6ee53b).

## Models tested
+ **Random Forest (RF)**: An ensemble bagging model that bootstrap aggregates multiple decision trees using randomly sampled subsets of data and features to predict or classify data. Beneficial for handling large datasets with high dimensionality and complexity.
+ **Generalized Boosting Regression (GBM)**: An ensemble gradient boosting model that iteratively builds decision trees and trains weak learners to correct the errors of the previously models. Suitable for a wide range of supervised learning tasks when you can tolerate longer training times.
+ **Logistic Regression (Logit)**: A probabilistic classification model used for binary classification. Suitable for scenarios when you need to understand variable relationships the probability of a particular outcome.


## Requirements:
+ R version 4.3.2 "Eye Holes"
