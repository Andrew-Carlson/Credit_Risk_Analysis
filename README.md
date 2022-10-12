# Credit_Risk_Analysis
## Overview of Analysis
In this analysis, credit data from more than 68,000 individuals was analyzed to determine the best Python machine learning model that predicts credit risk using the various data preprocessing methods and machine learning algorithms below:
* Oversampling with **imbalanced-learn**'s RandomOverSampler algorithm and performing a logistic regression with **scikit-learn**.
* Oversampling with **imbalanced-learn**'s SMOTE algorithm and performing a logistic regression with **scikit-learn**.
* Undersampling using **imbalanced-learn**'s ClusterCentroid algorithm and performing a logistic regression with **scikit-learn**.
* Using a combinatorial approach of over- and undersampling using **imbalanced-learn**'s SMOTEENN algorithm and performing a logistic regression with **scikit-learn**.
* Two machine learning models that reduce bias were also employed: **imbalanced-learn**'s BalancedRandomForestClassifier and EasyEnsembleClassifier.
## Results
Each of the machine learning models implemented had their predictions assessed for accuracy, predictive value (pre), recall (rec), and F1-score (f1) (amongst other statistical assessments). A confusion matrix was also created to assess each model.<br/>
**1)** Oversampling with **imbalanced-learn**'s RandomOverSampler and  logistic regression with **scikit-learn**:<br/>

* Accuracy of model:<br/>

    ![random_oversampler_accuracy](./images/random_oversample_accuracy.png)<br/>

* Confusion Matrix: <br/>

    ![random_oversampler_matrix](./images/random_oversampler_matrix.png)<br/>

* Predictive value (pre), recall (rec), and F1-score (f1):<br/>

    ![random_overampler_classification](./images/random_oversampler_classification.png)<br/>

**2)** Oversampling with **imbalanced-learn**'s SMOTE algorithm and logistic regression with **scikit-learn**:<br/>

* Accuracy of model:<br/>

    ![SMOTE_accuracy](./images/smote_accuracy.png)<br/>

* Confusion Matrix: <br/>

    ![SMOTE_matrix](./images/smote_matrix.png)<br/>

* Predictive value (pre), recall (rec), and F1-score (f1):<br/>

    ![SMOTE_classification](./images/smote_classification.png)<br/>
**3)** Undersampling using **imbalanced-learn**'s ClusterCentroid algorithm and logistic regression with **scikit-learn**:

* Accuracy of model:<br/>

    ![cluster_accuracy](./images/cluster_accuracy.png)<br/>

* Confusion Matrix: <br/>

    ![cluster_matrix](./images/cluster_matrix.png)<br/>

* Predictive value (pre), recall (rec), and F1-score (f1):<br/>

    ![cluster_classification](./images/cluster_classification.png)<br/>

**4)** Combinatorial approach of over- and undersampling using **imbalanced-learn**'s SMOTEENN algorithm and logistic regression with **scikit-learn**:

* Accuracy of model:<br/>

    ![SMOTEENN_accuracy](./images/smoteenn_accuracy.png)<br/>

* Confusion Matrix: <br/>

    ![SMOTEENN_matrix](./images/smoteenn_matrix.png)<br/>

* Predictive value (pre), recall (rec), and F1-score (f1):<br/>

    ![SMOTEENN_classification](./images/smoteenn_classification.png)<br/>

**5)** **imbalanced-learn**'s BalancedRandomForestClassifier:

* Accuracy of model:<br/>

    ![rf_accuracy](./images/rf_accuracy.png)<br/>

* Confusion Matrix: <br/>

    ![rf_matrix](./images/rf_matrix.png)<br/>

* Predictive value (pre), recall (rec), and F1-score (f1):<br/>

    ![rf_classification](./images/rf_classification.png)<br/>

* Most important data features for model:<br/>

    ![rf_features](./images/rf_features.png)<br/>

**6)** **imbalanced-learn**'s EasyEnsembleClassifier:

* Accuracy of model:<br/>

    ![easy_ensemble_accuracy](./images/easy_ensemble_accuracy.png)<br/>

* Confusion Matrix: <br/>

    ![easy_ensemble_matrix](./images/easy_ensemble_matrix.png)<br/>

* Predictive value (pre), recall (rec), and F1-score (f1):<br/>

    ![easy_ensemble_classification](./images/easy_ensemble_classification.png)<br/>