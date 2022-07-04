# credit_risk

## Overview of Analysis
The purpose of this analysis is to provide good machine learning models to predict good and bad credit risk loans. To do this, we are using over- and under-sampling methods to gather relevant data on bad credit risks - because they are not as prevalent as the good credit risks - in order to train the algorithm to more accurately predict bad credit risks

## Results

### Naive Random Oversampling

* Balanced Accuracy Score: 62.94%
* Precision: High-Risk - 1%; Low-Risk - 100%
* Sensitivity: High-Risk - 63%; Low-Risk - 62%
* Interpretation: This sample is very good at predicting the good credit risk, but very poor at predicting the poor credit risks (Precision). This sample also has a moderate to moderately-low ability of predicting the good credit risks and the bad credit risks (Sensitivity).

### SMOTE Oversampling

* Balanced Accuracy Score: 62.77%
* Precision: High-Risk - 1%; Low-Risk - 100%
* Sensitivity: High-Risk - 68%; Low-Risk - 57%
* Interpretation: This sample is very good at predicting the good credit risk, but very poor at predicting the poor credit risks (Precision). This sample also has a moderate to moderately-low ability of predicting the good credit risks and the bad credit risks (Sensitivity).

### Undersampling

* Balanced Accuracy Score: 62.77%
* Precision: High-Risk - 1%; Low-Risk - 100%
* Sensitivity: High-Risk - 47%; Low-Risk - 57%
* Interpretation: This sample is very good at predicting the good credit risk, but very poor at predicting the poor credit risks (Precision). This sample also has a moderate to moderately-low ability of predicting the good credit risks and the bad credit risks (Sensitivity).

### Combination Sampling (SMOTEENN)

* Balanced Accuracy Score: 65.47%
* Precision: High-Risk - 1%; Low-Risk - 100%
* Sensitivity: High-Risk - 61%; Low-Risk - 70%
* Interpretation: This sample is very good at predicting the good credit risk, but very poor at predicting the poor credit risks (Precision). This sample also has a moderate ability of predicting the good credit risks and the bad credit risks (Sensitivity).

