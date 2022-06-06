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
![SMOTE_Oversample](https://user-images.githubusercontent.com/97924142/172096879-b20a30ac-7c58-4302-b480-8827342f728a.png)

1.) Balanced Accuracy Score of 66.22%
2.) **High-Risk** preciscion rate of 1% and a recall rate of 63%
3.)**Low-Risk** precision rate was 100% while the recall rate was 69%

### UnderSampling
![Undersampling](https://user-images.githubusercontent.com/97924142/172097825-4b18221a-ddd9-4462-9f6f-6c3b1c25dbe9.png)

1.) Balanced Accuracy Score of 54.42%
2.) **High-Risk** preciscion rate of 1% and a recall rate of 69%
3.)**Low-Risk** precision rate was 100% while the recall rate was 40%

### Comination (Over-Under) Sampling
![Combination_Sampling](https://user-images.githubusercontent.com/97924142/172097977-0f69dabd-6841-4a5e-b5f0-5b707a461179.png)

1.) Balanced Accuracy Score of 64.47%
2.) **High-Risk** preciscion rate of 1% and a recall rate of 72%
3.)**Low-Risk** precision rate was 100% while the recall rate was 57%

### Balanced Random Forest Classifier
![Balanced_Random_Forest_Classifier](https://user-images.githubusercontent.com/97924142/172098345-8d279dc7-c055-432d-aa5a-29875869f2aa.png)

1.) Balanced Accuracy Score of 78.85%
2.) **High-Risk** preciscion rate of 3% and a recall rate of 70%
3.)**Low-Risk** precision rate was 100% while the recall rate was 87%

### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/97924142/172098487-9999a6a1-cf37-438b-b021-73e3f5567ba8.png)

1.) Balanced Accuracy Score of 93.17%
2.) **High-Risk** preciscion rate of 9% and a recall rate of 92%
3.)**Low-Risk** precision rate was 100% while the recall rate was 94%

## Summary
In reviewing all models used, the Easy Ensemble Adaboost Classifier was the best by far with an accuracy rating of 93.17%, High-Risk preciscion rate and recall rate of 9% and 92% respectively and a Low-Risk precision and recall rate of 100% and 94%. The next closest model would be the Balanced Random Forest Classifier with an accuracy of 78.85%, High-Risk precision and recall rates of 3/70% and Low-Risk rates of 100/87%. Given Easy Ensemble Adaboost Classifiers 10%+ lead in accuracy and recall score over it's nearest competitor, it is clear that this model should be used for all future analysis of this data.
