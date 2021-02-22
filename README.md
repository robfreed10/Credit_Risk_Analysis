# Credit_Risk_Analysis

## Overview
The Credit Risk Analysis applied machine learning to LoanStats of the 1st Quarter of 2019 in order to predict credit risk. Some of the methods used were Resampling, SMOTEENN and Esenbmle classification to identify individuals that were of high risk and individiuals that were low risk. The results will be below. 

## Results
Below are the results for 6 Machine Learning Models

### RandomOverSampler

 - Balanced Accuracy Score: 64.03%
 - Precision Score - High Risk: .01
 - Precision Score - Low Risk: 1.00
 - Recall Score Difference: .04%

![Screen Shot 2021-02-22 at 8 12 54 AM](https://user-images.githubusercontent.com/68922663/108713141-cff1df80-74e5-11eb-9a32-671de7eb3e6c.png)


### SMOTE Oversampling

 - Balanced Accuracy Score: 54.74%
 - Precision Score - High Risk: .01
 - Precision Score - Low Risk: 1.00
 - Recall Score Difference: .27%

![Screen Shot 2021-02-22 at 8 15 39 AM](https://user-images.githubusercontent.com/68922663/108713399-2a8b3b80-74e6-11eb-8c9c-4513bfbf8df9.png)


### ClusterCentroids Undersampling

 - Balanced Accuracy Score: 54.74%
 - Precision Score - High Risk: .01
 - Precision Score - Low Risk: 1.00
 - Recall Score Difference: .27%

![Screen Shot 2021-02-22 at 8 17 41 AM](https://user-images.githubusercontent.com/68922663/108713601-75a54e80-74e6-11eb-8c5e-fcbe7c63eba2.png)


### SMOTEEN Combination Sampling

 - Balanced Accuracy Score: 65.51%
 - Precision Score - High Risk: .01
 - Precision Score - Low Risk: 1.00
 - Recall Score Difference: .19%

![Screen Shot 2021-02-22 at 8 20 30 AM](https://user-images.githubusercontent.com/68922663/108713904-d9c81280-74e6-11eb-9d30-860b27cc5d10.png)


### BalancedRandomForestClassifier 

 - Balanced Accuracy Score: 78.85%
 - Precision Score - High Risk: .03
 - Precision Score - Low Risk: 1.00
 - Recall Score Difference: .17%

![Screen Shot 2021-02-22 at 8 23 01 AM](https://user-images.githubusercontent.com/68922663/108714160-33c8d800-74e7-11eb-8ad3-bb0148a280e0.png)


### Easy Ensemble AdaBoost Classifier

 - Balanced Accuracy Score: 93.17%
 - Precision Score - High Risk: .09
 - Precision Score - Low Risk: 1.00
 - Recall Score Difference: .02%

![Screen Shot 2021-02-22 at 8 24 51 AM](https://user-images.githubusercontent.com/68922663/108714369-75f21980-74e7-11eb-9c5f-1dc7ad97c8d1.png)


## Summary
With these 6 machine learning models, the Easy Ensemble AdaBoost Classifier is the preferred method of choice as it has a Balance Accuracy Score of 93.17%. The Balanced Random Forest Classifier was slightly below the Easy Ensemble AdaBoost Classifier at 78.85%. The Easy Ensemble AdaBoost Classifier also had the highest precision score for high risk at .09 and the smallest recall score difference at .02%. Therefore, I believe the Easy Ensemble AdaBoost Classifier is the best model to use for credit risk analysis 
