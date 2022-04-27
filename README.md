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

### Oversampling with SMOTE model
![smote](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/smote.png)

### Undersampling with ClusterCentroids
![CC](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/undersampling.png)

### Combo-sampling with SMOTEENN model
![combo](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/combo.png)

### BalancedRandomForestClassifier model
![brfc](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/brfc.png)

### EasyEnsembleClassifier Model
![eec](https://github.com/rhiandoy/credit_risk_analysis/blob/8590317f6c367694b6ae942144eb17dbf023ae6e/images/eec.png)
