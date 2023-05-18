# credit-risk-classification

### Overview of the Analysis:
The purpose of this analysis is to build a machine learning model that can predict whether a loan from LendingClub is a high-risk or a healthy loan. In order to accomplish this, we use historical data from LendingClub and apply logistic regression model. To improve the model's predictive power, we employ oversampling techniques such as RandomOverSampler from imbalanced-learn.

### Results:

Logistic Regression model without oversampling:

- Accuracy Score: 0.95
- Precision Score: 0.85
- Recall Score: 0.91

Logistic Regression model with oversampling:

- Accuracy Score: 0.99
- Precision Score: 0.85
- Recall Score: 0.99

### Summary:
The oversampling technique used in the second logistic regression model improves the model's performance significantly, especially in terms of recall score for high-risk loans. However, there is a slight decrease in precision score, which indicates the model may predict more false positives than before. Given that the recall score is of utmost importance in identifying high-risk loans, we recommend using the oversampling technique to build the machine learning model for LendingClub.












