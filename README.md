# Credit Risk Analysis

In this project, we used Supervised Machine Learning models to predict credit risk. To fulfill our objective, we applied different algorithms utilizing a credit card dataset from LendingClub where we analyzed the performance of each model to decide which one was the best to predict credit risk.

Below we listed the Supervised Machine Learning Models that we used:

- Naive Random Oversampling
- SMOTE Oversampling
- Undersampling (Cluster Centroids)
- Combination (Over and Under) Sampling (SMOTEENN)
- Balance Random Forest Classifier
- Easy Ensemble ADABoost Classifier

In order to complete our goal, we employed the following tools as resources: Jupyter Notebook, Python 3.9.7., Pandas, NumPy, SciPy, Scikit-learn, and imbalanced-learn.

## Results

In the following screenshots, we show the results we obtained from the six Supervised Machine Learning Models utilized for this challenge.

### Naive Random Oversampling

![Alt text](/Resources/oversampling.png "imagen1")

As we could see, the Balanced Accuracy Score of this model is 67.21%. The confusion matrix and the Classification Report are also presented with the results showing below:

- Balance Accuracy Score: 67.21%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Avg/Total Precision: 99%
- Recall High Risk: 72%
- Recall Low Risk: 62%
- Avg/Total Recall: 62%
- Avg/Total f1: 76%

### SMOTE - Oversampling

![Alt text](/Resources/smote.png "imagen2")

This model has a Balanced Accuracy Score of 64.17%. The results obtained also show the confusion matrix and the Classification Report:

- Balance Accuracy Score: 64.17%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Avg/Total Precision: 99%
- Recall High Risk: 60%
- Recall Low Risk: 68%
- Avg/Total Recall: 68%
- Avg/Total f1: 80%

### Undersampling - Cluster Centroids

![Alt text](/Resources/undersampling.png "imagen3")

As we can see, the Accuracy Score Balance is lower than the previous models, with a percentage of 54.31%. In the Classification Report, the high-risk precision is 1% and the low-risk precision is 100%. In addition, the high-risk recall is 40% and the low-risk recall is 68%.

- Balance Accuracy Score: 54.31%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Avg/Total Precision: 99%
- Recall High Risk: 40%
- Recall Low Risk: 68%
- Avg/Total Recall: 40%
- Avg/Total f1: 57%

### SMOTEENN - Combination -Over and Under- Sampling

![Alt text](/Resources/overunder.png "imagen4")
 
The Balance Accuracy Score of this algorithm is 65.44%. The confusion matrix and the Classification Report are also presented in the picture, showing the followin results:

- Balance Accuracy Score: 65.44%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Avg/Total Precision: 99%
- Recall High Risk: 74%
- Recall Low Risk: 57%
- Avg/Total Recall: 57
- Avg/Total f1: 72%

### Balanced Random Forest Classifier

![Alt text](/Resources/randomforest.png "imagen5")

This Supervised Machine Learning model has a Balanced Accuracy Score of 78.85%, which is a higher percentage than the previous algorithms. We also obtained the confusion matrix and the Classified Report. In short, we presented the principal metrics of the report:

- Balance Accuracy Score: 78.88
- Precision High Risk: 3%
- Precision Low Risk: 100%
- Avg/Total Precision: 99%
- Recall High Risk; 70%
- Recall Low Risk: 87%
- Avg/Total Recall: 87
- Avg/Total f1: 93%


### Easy Ensemble ADABoost Classifier

![Alt text](/Resources/easyensemble.png "imagen6")

Finally, we developed this model whose Balanced Accuracy Score was the highest, with a percentage of 93.16%. The confusion matrix and the Classified Report also show more favorable metrics, as we can see in the folloewing list:

- Balance Accuracy Score: 93.16
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Avg/Total Precision: 99%
- Recall High Risk: 94%
- Recall Low Risk: 92%
- Avg/Total Recall: 92%
- Avg/Total f1: 97%

## Summary

After developing, training, applying, and analyzing the different algorithms that we previously explained, we conclude that the supervised machine learning model with the best performance and the one that we suggest to be used is the Easy Ensemble ADABoost Classifier, not only because it has a better Balanced Accuracy Score, but also because in its Classification Report there is a balance between precision, sensitivity and f1, while in the other models the precision is overfitted and the recall was low. In addition, the confusion matrix and the classification report have more favorable metrics in terms of sensitivity, precision, and F1 score.

Another recommendation is to look for other models and do more tests to find better results.
