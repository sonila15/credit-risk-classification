# credit-risk-classification
Overview of the Analysis
The purpose of this analysis was to build machine learning models to predict high-risk loans based on a given set of financial data. The data was on loans issued by a peer-to-peer lending services company. The company provided a CSV file that contained 77,536 loans and a range of financial data on each loan.

The target variable in the data set was loan_status, which included two possible values: 0 for healthy loans and 1 for high-risk loans. In the original data set, there were 75,036 healthy loans and only 2,500 high-risk loans, which made it highly imbalanced.

In this analysis, we used two models to predict high-risk loans: a logistic regression model and a random forest classifier model. We also employed different resampling techniques to address the class imbalance issue in the data set.

Results
Logistic Regression Model:

Accuracy Score: 0.9505
Precision Score:
0: 1.00
1: 0.85
Recall Score:
0: 0.99
1: 0.99
Random Forest Classifier Model:

Accuracy Score: 0.9943
Precision Score:
0: 1.00
1: 0.85
Recall Score:
0: 0.99
1: 0.99
Summary
Both machine learning models had high accuracy scores and performed well in predicting high-risk loans. However, the random forest classifier model performed slightly better than the logistic regression model, with a higher precision score for predicting high-risk loans. The precision score for the random forest classifier model was 0.92, meaning that 92% of the high-risk loans it predicted were actually high-risk loans.

In contrast, the precision score for the logistic regression model was 0.85, meaning that 85% of the high-risk loans it predicted were actually high-risk loans. The recall score for both models was the same, meaning that they both correctly identified 99% of the high-risk loans in the data set.

Therefore, we recommend using the random forest classifier model for predicting high-risk loans. The model had a higher precision score for predicting high-risk loans, which is more important in this case, as the company wants to minimize the risk of issuing high-risk loans.












