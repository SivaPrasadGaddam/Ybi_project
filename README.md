# Credit-Card-Fraud-Detection
This project goals is to predict whether the customer will be defaulted or not. This dataset consist of 307511 records and 112 features.

# Feature Selection
We are using several methods:
1. Quasi constant method
2. Chi square
3. Univariate feature selection
4. Univariate AUC

# Models we tried to use:
we are using AUC score as evaluation metrics, because in credit card default usually AUC is proper evaluation metric for this case.
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Adaboosting
5. Gradient Boosting

# Result:
After implementing hyperparameter tuning, our best fit model is using Random Forest Classifier model with :
- train auc score: 0.7067893531568168
- test auc score: 0.7065710624972077
