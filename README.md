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

### Random Forest Classifier
* Balanced Accuracy Score: 66.06%
* Precision: High-Risk - 74%; Low-Risk - 100%
* Sensitivity: High-Risk - 100%; Low-Risk - 32%
* Interpretation: This sample is very good at predicting the good credit risk, and moderate at predicting the bad credit risks (Precision). This sample also has a very good ability of predicting the poor credit risks and poorly predicts the good credit risks (Sensitivity). 

## Summary
Most of these methods provide moderately low predictions based on the calculations. Of the methods utilized, the combination sampling (SMOTEENN) method was best, so that is the one I would recommed. Despite having a lower accuracy score, I suspect there is some error in the random forest classifier method, exhibited by the odd fluctuation in precision and sensitivity rates.

