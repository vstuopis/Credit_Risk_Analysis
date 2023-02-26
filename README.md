# Credit_Risk_Analysis

## Overview
After obtaining credit card credit data from LendingClub, while looking at the dataset we noticed the data has unbalanced classes. The unbalance is due to good loans far outnumbering the loans with high risk. We looked at this dataset from various angles including resampling, undersampling, over-sampling and a combination of the last 2 by using SMOOTEENN algorithm. We worked to determine which model worked best for the dataset we were provided.

## Results

We broke down the results for each of the 6 analysis methods were used paying attention to the accuracy score, precision and recall scores. 

### Naive Random Oversampling
* 64.39% Accuracy
* 99.00% Precision
* 60.00% Recall

### SMOTE Oversampling
* 66.29% Accuracy
* 99.00% Precision
* 69.00% Recall

### Cluster Centroids (Undersampling)
* 66.29% Accuracy
* 99.00% Precision
* 40.00% Recall

### SMOTEENN
* 64.48% Accuracy
* 99.00% Precision
* 57.00% Recall

### Balanced Random Forest Classifier
* 72.97% Accuracy
* 99.00% Precision
* 87.00% Recall

### Ensemble AdaBoost Classifier
* 93.17% Accuracy
* 99.00% Precision
* 87.00% Recall

## Summary
