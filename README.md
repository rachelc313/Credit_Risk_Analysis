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

![1](https://user-images.githubusercontent.com/111570965/211094537-07a32db4-f69c-4072-895c-17e1375aab6c.png)

The above image is a screenshot showing the code and output for the Naive Oversampling Model.


- Naive Oversampling Model
    - Balanced Accuracy Score: 65%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 63%
        - Low Risk: 67%

![2](https://user-images.githubusercontent.com/111570965/211094566-1f94df3b-c70a-4499-9319-8eb7f6513767.png)

The above image is a screenshot showing the code and output for the SMOTE Oversampling Model.


- SMOTE Oversampling Model
    - Balanced Accuracy Score: 65%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 66%
        - Low Risk: 65%

![3](https://user-images.githubusercontent.com/111570965/211094586-c05fcd82-593a-4390-932b-89e294f5b918.png)

The above image is a screenshot showing the code and output for the Undersampling Model.

- Undersampling Model
    - Balanced Accuracy Score: 65%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 66%
        - Low Risk: 65%

![4](https://user-images.githubusercontent.com/111570965/211094590-552e1845-9b57-428e-a14d-d6d6878a4b8c.png)

The above image is a screenshot showing the code and output for the SMOTEEN Algorithm.

- SMOTEEN Algorithm
    - Balanced Accuracy Score: 64%
    - Precision Score 
        - High Risk: 1%
        - Low Risk: 100%
    - Recall Score
        - High Risk: 69%
        - Low Risk: 58%

![5](https://user-images.githubusercontent.com/111570965/211094605-4a68c3ec-9228-4db0-ba3e-c3c1defa123e.png)

The above image is a screenshot showing the code and output for the BalancedRandomForestClassifier Algorithm.

- BalancedRandomForestClassifier Algorithm
    - Balanced Accuracy Score: 79%
    - Precision Score 
        - High Risk: 4%
        - Low Risk:100%
    - Recall Score
        - High Risk: 67%
        - Low Risk: 91%

![6](https://user-images.githubusercontent.com/111570965/211094620-8cb85134-f73a-4d6d-84e7-d750658cdad0.png)

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
