# credit_risk_classification

## Overview of the Analysis
The primary purpose of the analysis was to build a machine learning model capable of predicting loan status based on financial information to help financial institutions make an informed decision when processing loans. The dataset contained financial information related to loans, such as borrower details, credit scores, loan amounts, and interest rates, in order to predict if it was a healthy or high risk loan.
To create the learning model I split the data into training and testing sets, created a prediction, then assessed the performance of the trained model using evaluation metrics such as accuracy, precision, recall, and F1-score.


## Results
Accuracy Score: 0.9918
    This indicates that it correctly predicted the loan status for about 99.18% of the instances in the test set.
Precision Score (Label 0): 1.00
    For healthy loans, the precision was perfect, reaching 100%.
Precision Score (Label 1): 0.85
    For high-risk loans, the precision was 85%.
Recall Score (Label 0): 0.99
    The model correctly identified about 99% of the healthy loans.
Recall Score (Label 1): 0.91
    The model correctly identified about 91% of the high-risk loans.


## Summary
Given the impressive performance metrics of the logistic regression model, including high accuracy, precision, and recall scores, I would recommend this model for use by the company. While the precision for high-risk loans is slightly lower than for healthy loans (85% compared to 100%), it is still relatively high.
