# Credit_Risk_Analysis
Oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results 

**Oversample using SMOTEENN and SMOTE algos:**

SMOTEENN:

![Smotteen](https://user-images.githubusercontent.com/49954261/154906861-4b2511b6-8c54-4016-89e4-744e305a362e.png)


SMOTE:

![SMOTE](https://user-images.githubusercontent.com/49954261/154906871-8993506e-b35b-4666-b10b-f04342c9f288.png)


Cluster_Centroids:

![Cluster](https://user-images.githubusercontent.com/49954261/154906991-731d7975-d3c3-4ff4-b633-280186c39959.png)


**Machine Learning Models:**

EasyEnsembleClassifier:

![Easy_Ensemble](https://user-images.githubusercontent.com/49954261/154907006-8f756b31-5bd5-4cd3-b0a0-cff639cb11c1.png)

BalancedRandomForestClassifier:

![Balanced_Random](https://user-images.githubusercontent.com/49954261/154907018-24455012-72ac-4171-a600-1ea97657a3df.png)


## Summary 
Of all the models-- EasyEnsembleClassifier is the most accurate at 86%. The other methods did not prove to come close to the machine learning models. The EasyEnsemble Classifier method proves to be the best recommendation to predict credit risk. 
