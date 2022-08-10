# Telecom_Churn_Prediction
The objective is to predict customer churn and identify the factors which can help the business focus on retaining customers

#Notebook Steps
1. Data Preparation and Preprocessing
2. Baseline Logistic Regression
3. Logistic Regression using Class Weights
4. Dimensionality Reduction using PCA
5. Random Forests using Hyperparameter tuning
6. XG Boosting using Hyperparameter tuning
7. Test Data Evaluation and Submission File Preparation
8. Observations and Conclusions


#Conclusion
Important variables have been identified for the customer churn prediction using the logistic regression model
In terms of accuracy :
XG Boosting has the best training and validation accuracy and a hight AUC value in the ROC curve and this will be used to submit for the Kaggle competition since accuracy is the most important
In terms of overall model performance :
Random Forest performs the best since it has the has an appropriate tradeoff between precision and recall which is necessary metric other than accuracy which doesn't indicate the overall model performance.
Dimensionality Reduction using PCA has been done and it helps in improved model performance
Class Imbalance :
Class Imbalance has been identified as 90:10 (Non churn : Churn) and it has been considered while the training of the models, class weights concept is used for penalizing the non-churn customers during training
Future Improvements : Hyperparameters can be tuned further to get the optimized model, however due to time and infrastructure constraints, it has been coarsely tuned for the results
