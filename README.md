# Credit_Risk_Analysis

## Overview
After obtaining credit card credit data from LendingClub, while looking at the dataset we noticed the data has unbalanced classes. The unbalance is due to good loans far outnumbering the loans with high risk. We looked at this dataset from various angles including resampling, undersampling, over-sampling and a combination of the last 2 by using SMOOTEENN algorithm. We worked to determine which model worked best for the dataset we were provided.

## Results

We broke down the results for each of the 6 machine learning models paying attention to the accuracy score, precision and recall scores. 

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

When it comes to finding the best model we want a combination of good accuracy in addition to good recall. With the above six machine learning alrogithms, all 6 models has a 99% precision accuracy so that wouldn't need to be taken into account when looking for the best model to use. We want as many positive sampled identified, which is why it breaks it down to a high recall percentage which would either be the Ensemble AdaBoost Classifier or Balanced Random Forest Classifier. When looking at the final datapoint of accracy, the Ensemble AdaBoost Classifier has the highest percentage of the 2 machine algorithms remaining. 

We would recommend the model to be used for analyzing credit risk is the Ensemble AdaBoost Classifier. 
![AdaBoost Classifier Data](https://github.com/vstuopis/Credit_Risk_Analysis/blob/main/AdaBoost%20Classifier%20Data.png)
