# 12-Supervised-Learning-Homework

# Module 12 Report Template

## Overview of the Analysis

I used various techniques to train and evaluate logistic regression models with imbalanced classes between healthy and high-risk loans. I was provided with, and utilized, a dataset of historical lending activity from a peer-to-peer lending services company to build a model to identify the creditworthiness of borrowers.  

The historical data contained 75,036 "healthy" loans, compared to only 2,500 "at-risk/defaulted" loans. These were divided into training and testing sets, and logistic regression was used to predicts results based on the original data set.  The data was then resampled to create oversampled data (creating more "high risk" loans in the training data), and logistic regression was again utilized.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy = 95.2%
  * Precision = 99%
  * Recall = 99%

* Machine Learning Model 2:
  * Accuracy = 99.4%
  * Precision = 99%
  * Recall = 99%
  

## Summary

I would recommend using Machine Learning Model 2, with the oversampled data.  The overall accuracy of the model is significantly higher overall.  Further, the number of false negatives (unidentified bad loans) was down significantly, from 56 down to 4 out of the 619 population.  Model 2 will provide overall better portfolio performance than Model 1. 