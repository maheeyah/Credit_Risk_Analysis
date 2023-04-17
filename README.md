# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis:
The purpose of this project is to apply machine learning to credit card risk. This real-world challenge is an unbalanced classification problem. In order to solve it, different techniques to train and evaluate models are needed. RandomOverSampler and SMOTE algorithms will be used to oversample the data, and ClusterCentroids will be used to undersample the data. SMOTEENN will be the combinatorial approach of over- and undersampling. BalancedRandomForestClassifier and EasyEnsembleClassifer will be compared to reduce bias in credit risk. 

## Results:

* There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
## Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

credit_risk_ensemble line 16 from https://stackoverflow.com/questions/40159161/feature-importance-vector-in-decision-trees-in-scikit-learn-along-with-feature-n#:~:text=Then%20you%20can%20print%20the%20top%205%20features,sorted%20%28zip%20%28clf.feature_importances_%2C%20X_train.columns%29%2Creverse%3DTrue%29%20%5B%3A5%5D%3A%20print%20%28name%2C%20importance%29
