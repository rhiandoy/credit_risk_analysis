# credit_risk_analysis

## Project Overview

The purpose of this analysis is to apply machine learning algorithms to predict credit card risks in the real world. To analyze these risks we looked at:
-  Oversampling (using naive random oversampling and SMOTE algorithms)
-  Undersampling (using Cluster Centroids algorithm to determine performance compared to oversampling)
-  Combination Sampling (using SMOTEENN)
-  Ensemble Classifiers (using BalancedRandomForestClassifier & EasyEnsembleClassifier)

For all algorithms, we followed the same procedure of resampling the dataset, viewing target class counts, training logistic regression classifiers, calculating the balanced accuracy scores, generate a confusion matrix, and create a classification report.

## Results
### Oversampling with RandomOverSampler
![naive](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/naive_random.png)

- Balanced Accuracy: 64%
- Precision: High Risk - 1%, Low Risk - 100%, Avg - 99%
- Recall: High Risk - 69%, Low Risk - 59%, Avg - 60%

### Oversampling with SMOTE model
![smote](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/smote.png)

- Balanced Accuracy: 66%
- Precision: High Risk - 1%, Low Risk - 100%, Avg - 99%
- Recall: High Risk - 63%, Low Risk - 69%, Avg - 69%

### Undersampling with ClusterCentroids
![CC](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/undersampling.png)

- Balanced Accuracy: 54%
- Precision: High Risk - 1%, Low Risk - 100%, Avg - 99%
- Recall: High Risk - 69%, Low Risk - 40%, Avg - 40%
### Combo-sampling with SMOTEENN model
![combo](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/combo.png)

- Balanced Accuracy: 64%
- Precision: High Risk - 1%, Low Risk - 100%, Avg - 99%
- Recall: High Risk - 70%, Low Risk - 57%, Avg - 58%

### BalancedRandomForestClassifier model
![brfc](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/brfc.png)

- Balanced Accuracy: 79%
- Precision: High Risk - 3%, Low Risk - 100%, Avg - 99%
- Recall: High Risk - 70%, Low Risk - 87%, Avg - 87%

### EasyEnsembleClassifier Model
![eec](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/eec.png)

- Balanced Accuracy: 93%
- Precision: High Risk - 9%, Low Risk - 100%, Avg - 99%
- Recall: High Risk - 92%, Low Risk - 94%, Avg - 94%


## Summary
When comparing all algorithms performed to determine high risk on credit cards, the Easy Ensemble Classifier Model has the highest percentage of balanced accuracy at 93% (.93 out of 1). This model also showed a 9% precision rate for high risk candidates. The other 5 models analyzed did not come close to the accuracy/precision/recall of the EEC model. 

