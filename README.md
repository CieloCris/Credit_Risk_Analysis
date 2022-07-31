# Credit Risk Analysis

In this project, we used Supervised Machine Learning models to predict credit risk. To fulfill our objective, we applied different algorithms utilizing a credit card dataset from LendingClub where we analyzed the performance of each model to decide which one was the best to predict credit risk.

Below we listed the Supervised Machine Learning Models that we used:

- Naive Random Oversampling

- SMOTE Oversampling

- Undersampling (Cluster Centroids)

- Combination (Over and Under) Sampling (SMOTEENN)

- Balance Random Forest Classifier

- Easy Ensemble ADABoost Classifier

In order to complete our goal, we employed the following tools as resources: Jupyter Notebook, Python 3.9.7., Pandas, NumPy, SciPy, Scikit-learn, imbalanced-learn.

## Results

In the following screenshots of our code, we show the results we obtained from the six Supervised Machine Learning Models utilized for this challenge.

### Naive Random Oversampling

![Alt text](/Resources/oversampling.png "imagen1")

As we could see, the Balanced Accuracy Score of this model is 67.21%. The confusion matrix and the Classification Report are also presented, showing an average precision of 99% and a total recall of 62%.

- Balance Accuracy Score: 64.17%
- Precision High Risk:
- Precision Low Risk:
- Avg/Total Precision:
- Recall High Risk
- Recall Low Risk:
- Avg/Total Recall:

### SMOTE - Oversampling

![Alt text](/Resources/smote.png "imagen2")

This model has a Balanced Accuracy Score of 64.17%. The results obtained also show the confusion matrix and the Classification Report
- Balance Accuracy Score: 64.17%
- Precision High Risk:
- Precision Low Risk:
- Avg/Total Precision:
- Recall High Risk
- Recall Low Risk:
- Avg/Total Recall:

, this show a avg/total precision of 99% and an avg/total recall of 68%.

### Undersampling - Cluster Centroids

![Alt text](/Resources/undersampling.png "imagen3")

As we can see, the Accuracy Score balance is lower than the previous models, with a percentage of 54.31%. In the Classification Report, the high-risk precision is 1% and the low-risk precision is 100%. In addition, the high-risk recall is 40% and the low-risk recall is 68%.
- Balance Accuracy Score: 64.17%
- Precision High Risk:
- Precision Low Risk:
- Avg/Total Precision:
- Recall High Risk
- Recall Low Risk:
- Avg/Total Recall:

### SMOTEENN - Combination -Over and Under- Sampling

![Alt text](/Resources/overunder.png "imagen4")

The balance accuracy score of this algorithm is 65.44%. The confusion matrix and the Classification Report are also presented in the picture, showing a high-risk precision of 1%, a low-risk precision of 100%, a high-risk recall of 74% and a low-risk recall of 57%.

- Balance Accuracy Score: 64.17%
- Precision High Risk:
- Precision Low Risk:
- Avg/Total Precision:
- Recall High Risk
- Recall Low Risk:
- Avg/Total Recall:

### Balanced Random Forest Classifier

![Alt text](/Resources/randomforest.png "imagen5")

This Supervised Machine Learning model has a Balanced Accuracy Score of 78.85%, which is a higher percentage than the previous algorithms. We also showed the confusion matrix and the Classified Report of the Balanced Random Forest Classifier: its report a avg/total precision of 99%, and a avg/total recall of 87%

- Balance Accuracy Score: 64.17%
- Precision High Risk:
- Precision Low Risk:
- Avg/Total Precision:
- Recall High Risk
- Recall Low Risk:
- Avg/Total Recall:


### Easy Ensemble ADABoost Classifier

![Alt text](/Resources/easyensemble.png "imagen6")

Finally, we developed this model whose Balanced Accuracy Score was the highest, with a percentage of 93.16%. The confusion matrix and the Classified Report also show more favorable metrics, since they have better precision (99%), recall (94%), and F1 or harmony (97%) than the other algorithms used.

- Balance Accuracy Score: 64.17%
- Precision High Risk:
- Precision Low Risk:
- Avg/Total Precision:
- Recall High Risk
- Recall Low Risk:
- Avg/Total Recall:


###Summary

After developing, training, applying, and analyzing the different algorithms that We previously explained, We conclude that the model with the best performance and the one that We suggested to be used is the Easy Ensemble ADABoost Classifier, not only because it has a better Balanced Accuracy Score, but also because in its Classification Report there is a balance between precision and sensitivity, while in the other models the precision is overfitted and the recall was low. In addition, the confusion matrix and the classification report have more favorable metrics in terms of sensitivity, precision, and F1 score.

Another recommendation is to look for other models and do more tests to find better results.
