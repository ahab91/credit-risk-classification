# credit-risk-classification

## Overview of the Analysis

In this project, I used a historical dataset of loans from different lending servicers to build and train a logistic regression model capable of predicting high-risk loans with high accuracy and precision. After creating the labels using the "loan_status" column and understanding the count of each label (0 signifying a healthy loan and "1" indicating a high-risk loan), I built my initial model and ran balanced accuracy scores, created a confusion matrix, and formed a classification report. Then I resampled the data to create a more effective model using the same methods.

## Results

* Machine Learning Model 1:
  * Demonstrated 95% accuracy in its predictions
  * Confusion matrix highlighted 102 false positives and 56 false negatives
  * Classification report revealed 100% precision in healthy loan predictions and 85% precision with high-risk loans



* Machine Learning Model 2:
  * Demonstrated 99% accuracy in its predictions
  * Confusion matrix highlighted slightly more false positives (116) but significantly fewer false negatives (2)
  * Classification report revealed 100% precision in healthy loan predictions and 84% precision with high-risk loans

## Summary

I recommend Machine Learning Model 2 primarily due to the notable difference in false negatives. For lending institutions, false negatives are far more dangerous than false positives because an incorrectly predicted false negative could lead to servicing a loan that is likely to be high-risk and default over time. Despite the model predicting slightly higher false positives, that's a safer error for the model to make.
