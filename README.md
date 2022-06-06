# Credit_Risk_Analysis

## Overview
The purpose of this activity was to use Machine Learning statistical algorythms to make predictions on certain lending data provided by LendingClub. Supervised Learning methodology was used for this activity, and the LendingClub data was known to be unbalanced due to having more risky loans than safe ones. To properly balance this, and make better predictions off the data, several Machine Learning algorithms were used including: RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Analysis and Results
The results for the siz Machine Learning modules and their respective balanced accuracy, precision and recall scores:

### Naive OverSampling
![Naive_Random_Oversample](https://user-images.githubusercontent.com/97924142/172096479-4ce03253-d17e-45b2-842a-28d0deef5357.png)
1.) Balanced Accuracy score of 65.73%
2.) **High-Risk** precision rate was only 1% while it's recall rate was 71%
3.) **Low-Risk** precision rate was 100% while the recall rate was 60%

### SMOTE Oversampling
