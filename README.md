# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis:
The purpose of this project is to apply machine learning to credit card risk. This real-world challenge is an unbalanced classification problem. In order to solve it, different techniques to train and evaluate models are needed. RandomOverSampler and SMOTE algorithms will be used to oversample the data, and ClusterCentroids will be used to undersample the data. SMOTEENN will be the combinatorial approach of over- and undersampling. BalancedRandomForestClassifier and EasyEnsembleClassifer will be compared to reduce bias in credit risk. 

## Results:
### RandomOverSampler: 
    * Balanced Accuracy Score: 0.6287664527357772 or 62.9%
    * Precision Score: 0.01 or 1%
    * Recall Score: 0.60 or 60%
### SMOTE
  * Balanced Accuracy Score: 0.6307234570587121 or 63.1%
  * Precision Score: 0.01 or 1%
  * Recall Score: 0.60 or 60%
### ClusterCentroids
  * Balanced Accuracy Score: 0.5151725749463159 or 51.5%
  * Precision Score: 0.01 or 1%
  * Recall Score: 0.60 or 60%
### SMOTEENN
  * Balanced Accuracy Score: 0.6078467513526797 or 60.8%
  * Precision Score: 0.01 or 1%
  * Recall Score: 0.66 or 66%
### BalancedRandomForestClassifer
  * Balanced Accuracy Score: 0.7877672625306695 78.8%
  * Precision Score: 0.04 or 4%
  * Recall Score: 0.67 or 67%
### EasyEnsembleClassifer
  * Balanced Accuracy Score: 0.925427358175101 or 92.5%
  * Precision Score: 0.07 or 7%
  * Recall Score: 0.91 or 91%
## Summary:
All six models explored in this analysis show weak precision in determining high risk. The best precision score is observed in the EasyEnsembleClassifer with a score of 7%. The EasyEnsembleClassifer also has the highest recall score of 91% while the other five models are around 60-67%. I would not recommend any of these models to predict credit risk as the relatively low precision observed in all the models is not ideal for banks as good loans outnumber risky loans. 

Code source note:
credit_risk_ensemble code on line 16 was written with help from https://stackoverflow.com/questions/40159161/feature-importance-vector-in-decision-trees-in-scikit-learn-along-with-feature-n#:~:text=Then%20you%20can%20print%20the%20top%205%20features,sorted%20%28zip%20%28clf.feature_importances_%2C%20X_train.columns%29%2Creverse%3DTrue%29%20%5B%3A5%5D%3A%20print%20%28name%2C%20importance%29
