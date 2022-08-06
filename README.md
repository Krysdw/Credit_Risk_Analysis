# Credit_Risk_Analysis

Overview Loan Prediction Risk Analysis

In the following analysis: 
Imbalanced-learn & scikit – learn libraries were used to build models using resampling.
The following algorithms were used:

RandomOversampler
SMOTE
ClusterCentroids
SMOTEENN
Along with the following modules:
BalancedRandomForestClassifier
EasyEnsembleClassifier 
To assess, evaluate and predict credit risk. 

Purpose of Analysis
The purpose of the following analysis is to employ the above libraries, algorithms and modules to allow for greater prediction of credit risk of the LendingClub, peer to peer lending services dataset. 

Results:
The following models reference the respective high risk and low risk scores and respective precision and recall scores:
Imbalanced Classification Report


![Screenshot (326)](https://user-images.githubusercontent.com/102800315/183264317-78651935-61e9-4cac-a56f-113985aee0ad.png)

 
•	Balanced Accuracy: 0.67
•	Precision: The precision is low for high _risk loans and the precision is high for low_risk loans
•	Recall Scores:
-High: 0.67
-Low: 0.91

SMOTE Oversampling



 ![Screenshot (328)](https://user-images.githubusercontent.com/102800315/183264336-6d3fcf08-7f39-4ec4-b1d3-6dbf72da8abc.png)


•	Balanced Accuracy: 0.93
•	Precision: The precision is low for high _risk loans and the precision is high for low_risk loans
•	Recall Scores:
-High: 0.91
-Low: 0.94



Under Sampling
 
 
 
 
 ![Screenshot (331)](https://user-images.githubusercontent.com/102800315/183264368-10eb1b3e-a0c1-4c1a-a272-221d4c9800bc.png)



•	Balanced Accuracy: 0.51
•	Precision: The precision is low for high _risk loans and the precision is high for low_risk loans
•	Recall Scores:
-High: 0.59
-Low: 0.44

Combination Under-Over Sampling



![Screenshot (336)](https://user-images.githubusercontent.com/102800315/183264472-dac68db3-2961-4d73-8904-8aae3aea6859.png)

 
•	Balanced Accuracy: 0.63
•	Precision: The precision is low for high _risk loans and the precision is high for low_risk loans
•	Recall Scores:
-High: 0.70
-Low: 0.57


Balanced random Forest Classifier


![Screenshot (336)](https://user-images.githubusercontent.com/102800315/183264509-74e59b9f-3384-466f-8ea3-3a1299bd6a8b.png)

 
•	Balanced Accuracy: 0.63
•	Precision: The precision is low for high _risk loans and the precision is high for low_risk loans
•	Recall Scores:
-High: 0.70
-Low: 0.57



Easy Ensemble AdaBoost Classifier


![Screenshot (328)](https://user-images.githubusercontent.com/102800315/183264554-08727f0f-918b-414c-a58f-1c766dbeb08f.png)


 
•	Balanced Accuracy: 0.93
•	Precision: The precision is low for high _risk loans and the precision is high for low_risk loans
•	Recall Scores:
-High: 0.91
-Low: 0.94




Summary
Overall, the Easy Ensemble AdaBoost Classifier would be the best machine learning model to use for additional credit analysis. With a Balanced Accuracy score of about .93 and significantly higher Recall scores than the other models, makes the AdaBoost Classifier the best model to use. The Recall scores for the other models were all below .70, some as low as .44. The Balanced Accuracy scores for the other models were also a lot lower compared to the model of the Ensemble AdaBoost Cla
