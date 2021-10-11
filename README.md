# Credit Risk Analysis

## Overview

Using the credit card credit data set from LendingClub, a peer-to-peer lending services company, we are tasked with oversampling the data using the RandomOverSample and MSOTE algorithms, and undersample the data using the ClusterCentrods algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results

1.) Oversampling - Naive Random Oversampling

![alt text](images/naive_random_oversampling_balanced_accuracy.png)
![alt text](images/naive_random_oversampling_imbalanced_report.png)

2.) SMOTE Oversampling

![alt text](images/smote_balanced_accuracy.png)
![alt text](iamges/smote_imbalanced_report.png)

3.) Undersampling

![alt text](images/undersampling_balanced_accuracy.png)
![alt text](images/undersampling_imbalanced_report.png)

4.) Combination Sampling

![alt text](images/combination_balanced_accuracy.png)
![alt text](images/combination_imbalanced_report.png)

5.) Balanced Random Forest Classifier

![alt text](images/brfc_balanced_accuracy.png)
![alt text](images/brfc_imbalanced_report.png)

6.) Easy Ensemble AdaBoost Classifier

![alt text](images/eec_balanced_accuracy.png)
![alt text](images/eec_imbalanced_report.png)

## Summary

