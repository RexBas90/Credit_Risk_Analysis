# Credit_Risk_Analysis

## Overview 

LendingClub, a peer-to-peer lending services company, would like to develop a few machine learning models to predict credit risk. Credit risk is an unbalanced since the number of good loans outnumber the risky loans. Multiple techniques will be employed to determine which model(s) perform better at predicting credit risk. The dataset was first oversampled using the RandomOverSampler and SMOTE. The dataset was then undersampled using ClusterCentroids. SMOTEENN algorithm was used next which combines both over- and undersampling of the data. 

## Results: 

### Naive Random Oversampling

- Accuracy: 0.643
- Precision and Recall (Sensitivity) are shown below:
![Naive Random Oversampling](analysis/naive_random_oversampling.PNG)

### SMOTE Oversampling:
- Accuracy: 0.652
- Precision and Recall (Sensitivity) are shown below:
![SMOTE Oversampling](analysis/SMOTE_oversampling.PNG)

### Undersampling:
- Accuracy: 0.544
- Precision and Recall (Sensitivity) are shown below:
![Undersampling](analysis/undersampling.PNG)

### SMOTEENN Combination Over-and Undersampling:
- Accuracy: 0.644
- Precision and Recall (Sensitivity) are shown below:
![SMOTEEN](analysis/SMOTEENN.PNG)

### SMOTEENN Combination Over-and Undersampling:
- Accuracy: 0.788
- Precision and Recall (Sensitivity) are shown below:
![Balanced Random Forest](analysis/balanced_random_forest.PNG)

### Balanced Random Forest:
- Accuracy: 0.788
- Precision and Recall (Sensitivity) are shown below:
![Balanced Random Forest](analysis/balanced_random_forest.PNG)

### Easy Ensemble AdaBoost Classifier:
- Accuracy: 0.931
- Precision and Recall (Sensitivity) are shown below:
![Balanced Random Forest](analysis/easy_ensemble.PNG)

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.