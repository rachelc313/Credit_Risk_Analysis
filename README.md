# Credit_Risk_Analysis

## Overview of the Loan Prediction Risk Analysis
The purpose of the analysis was to create six supervised machine learning models to determine which model would be best to use. The machine learning models that were created were:

- Naive Oversampling Model
- SMOTE Oversampling Model
- Undersampling Model
- SMOTEEN Algorithm
- BalancedRandomForestClassifier Algorithm
- EasyEnsembleClassifier Algorithm

## Results
The results of this analysis are as follows:

1-
The above image is a screenshot showing the code and output for the Naive Oversampling Model.


- Naive Oversampling Model
    - Balanced Accuracy Score: 65%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 63%
        - Low Risk: 67%

2-
The above image is a screenshot showing the code and output for the SMOTE Oversampling Model.


- SMOTE Oversampling Model
    - Balanced Accuracy Score: 65%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 66%
        - Low Risk: 65%

3 -
The above image is a screenshot showing the code and output for the Undersampling Model.

- Undersampling Model
    - Balanced Accuracy Score: 65%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 66%
        - Low Risk: 65%

4-
The above image is a screenshot showing the code and output for the SMOTEEN Algorithm.

- SMOTEEN Algorithm
    - Balanced Accuracy Score: 64%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 69%
        - Low Risk: 58%

5-
The above image is a screenshot showing the code and output for the BalancedRandomForestClassifier Algorithm.

- BalancedRandomForestClassifier Algorithm
    - Balanced Accuracy Score: 79%
    - Precision Score 
        - High Risk: 4%
        - Low Risk:100%
    - Recall Score
        - High Risk: 67%
        - Low Risk: 91%

6-
The above image is a screenshot showing the code and output for the EasyEnsembleClassifier Algorithm.

- EasyEnsembleClassifier Algorithm
    - Balanced Accuracy Score: 93%
    - Precision Score 
        - High Risk: 7%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 91%
        - Low Risk: 94%

## Summary
Based on the analysis, the best performing model or algorithm was the EasyEnsembleClassifier. This algorithm returned the highest Balanced Accuracy Score of 93% and the highest Recall Scores of 91% and 94% for high and low risk, respectively. 

The worst performing model or algorithm was the SMOTEEN Algorithm which is also considered a combination sampling model.The Balance Accuracy Score was 64%. The Recall Scores were: high risk: 69% and low risk: 58%.

My recommendation would be to use the EasyEnsembleClassifier algorithm based on the analysis performed.