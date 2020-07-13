# Heart disease prediction
The objective of this project is to predict whether a patient is having a heart disease or not, given the information about the parameters given in the dataset.
The dataset is taken from [https://www.kaggle.com/ronitf/heart-disease-uci]

In this project the secondary objective was to get hands on experience on following algorithms
1. K-NN
2. Decision Tree
3. Random Forest

The results are based on following constraints:
* GridSearcCV was chosen as cross_validation of hyperparameters
* Auc score is considered as performance metric for the entire project
* For K-NN algorithm the hyperparamter i.e k was chosen from 1 to 20.
* For Decision Tree 'max_depth' and 'min_samples_split' were chosen for hyperparameter tuning and the best value for both was chosen from [1,5,10,15] and [5,10,100,500] respectively.
* For Random forest 'max_depth' and 'n_estimators' were chosen for hyperparameter tuning and the best value for both was chosen from [5,10,15,20] and [200,400,700,1000] respectively.

K-NN and Random Forest has approax similar auc_score.
