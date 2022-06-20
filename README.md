# Credit_Risk_Analysis
### Resources
Libraries:
- imbalanced-learn 
- scikit-learn
- RandomOverSampler
- SMOTE algorithms
- ClusterCentroids algorithm
- SMOTEENN algorithm
- BalancedRandomForestClassifier
- EasyEnsembleClassifier 

## Overview
Credit risk presents an unbalanced classification problem due to the fact that good loans (low risk) significantly outnumber bad loans(risky loans). We sued different strategies and techniques to train models with an unbalanced class. 
## Purpose: 
Our purpose in this analysis was to explain how a machine learning algorithm is used in data analytics. We wanted to create training and test groups for the data set. We also implemented logistical regression, decision tree mapping, random forest, and support vector machine learning algorithms to interpret the data. Once completed, we were to compare the pros and cons of each supervised learning algorithm and determine which is best used for the given scenario. Finally, we are to use ensemble and resampling techniques to maximize the potential of the model.

## Results:
Our results for the six various machine learning models are below:

### Naive Random Oversampling
![Native]( https://github.com/gonzalesbarrett/Credit_Risk_Analysis/blob/main/Challenge/Images/Native_OverSamp.png)     
- Balanced Accuracy: 0.6612700484668286
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
-  Recall: High/Low risk = .66/.67

### SMOTE Oversampling
![Smote]( https://github.com/gonzalesbarrett/Credit_Risk_Analysis/blob/main/Challenge/Images/Smote_OverSamp.png)     
- Balanced Accuracy: 0.6303296388959394
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .62/.64

### Undersampling
![UnderSamp]( https://github.com/gonzalesbarrett/Credit_Risk_Analysis/blob/main/Challenge/Images/UnderSamp.png)     
- Balanced Accuracy: 0.6303296388959394
- Precision:  The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .63/.40

### Combination Under-Over Sampling
![Combo]( https://github.com/gonzalesbarrett/Credit_Risk_Analysis/blob/main/Challenge/Images/Combo_UnderOverSamp.png)     
- Balanced Accuracy: 0.5173713090878325
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .70/.57

### Balanced Random Forest Classifier
![Balanced]( https://github.com/gonzalesbarrett/Credit_Risk_Analysis/blob/main/Challenge/Images/Balanced_RandomClass.png)     
- Balanced Accuracy: 0.7877672625306695
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .67/.91

### Easy Ensemble AdaBoost Classifier
![Easy]( https://github.com/gonzalesbarrett/Credit_Risk_Analysis/blob/main/Challenge/Images/Easy_AdaBoostClass.png)     
- Balanced Accuracy: 0.925427358175101
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .91/.94

## Summary:
For Balanced accuracy, results are evaluated for accuracy on a scale of zero to one with the result that is closest to 1 being considered the most accurate model. For the provided data set, the Easy Ensemble AdaBoost Classifier scored the highest with a balanced accuracy rate of .93. All of the other models fell below .90 and thus would be considered less accurate. Precision for the models were similar and all fell within an acceptable range. Recall score results share the same evaluation method as balanced accuracy (zero to one range) and once again the Easy Ensemble AdaBoost Classifier has the highest score of .91/.94. Due to these results the Easy Ensemble AdaBoost Classifier would be considered the most accurate machine learning model for the credit card analysis.
