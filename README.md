# Credit_Risk_Analysis

## Overview of Analysis
In this project we have considered all the factors in our loan_stats file to predict whether low or high risk status of the people. Mostly data scientists create a model, evaluate and train the models. We are using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. We have oversampled the data using randomoversampler and smote algorithms and undersample the data with the clustercentroid algorithm. In the remaining models we used a combination approach to over and undersample the data using smoteenn. Finally compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


## Naive Oversampling Results:
The balanced accuracy test it 63%, the precision for the high_risk is at a low positivity at 1% and the recall is 64%
![alt text](https://github.com/nikmahadeshwar/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-10-28%20at%2010.42.01%20AM.png) I

## SMOTE oversampling results: 
The accuracy score is 65%, the precision for the high_risk loans is at a low positvity again at 1% and recall is 60% overall
![alt text](https://github.com/nikmahadeshwar/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-10-28%20at%2010.47.21%20AM.png)

## Undersampling results: 
balanced accuracy score is 54.4% overall, the precision is at .99% and the recall is 42%
![alt text](https://github.com/nikmahadeshwar/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-10-28%20at%2010.56.28%20AM.png)

## Combination(over and undersampling) results:
balanced accuracy score is 54.7% the precision is .99% and the recall is 58% overall
![alt text](https://github.com/nikmahadeshwar/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-10-28%20at%2011.08.16%20AM.png)



## Summary:
We performed undersampling, oversampling and combination of both in the first four models to predict the loans at high risk and determine the best model.
The next two models we used ensemble classifiers to resample the data and predict loans at high or low risk. Our accuracy score and recall is highest in the ensemble classifiers thus we can consider the ensemble classifiers as best fit over the first four models. Thus we can conclude that the Easy Ensemble had the best accuracy score and good balance of precision and recall scores.

