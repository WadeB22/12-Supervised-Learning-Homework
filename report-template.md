# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

I used various techniques to train and evaluate logistic regression models with imbalanced classes between healthy and high-risk loans. I was provided with, and utilized, a dataset of historical lending activity from a peer-to-peer lending services company to build a model to identify the creditworthiness of borrowers.  The historical data contained 75,036 "healthy" loans, compared to only 2,500 "at-risk/defaulted" loans. These were divided into training and testing sets, and logistic regression was used to predicts results based on the original data set.  Then the data was manipulated to create oversampled data (creating more "high risk" loans in the training data), and logistic regression was again utilized.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
