# Telecom_Customer_Churn_Prediction
•	Dataset contained 7043 rows (customers) and 21 features such as “tenure”, “online security”, “paperless billing”, etc.
•	Performed EDA, applied SMOTE to balance the data and RFE (Recursive Feature Elimination) to select the 15 significant features  
•	Logit and Probit models were used for classifying the Churn class; features were dropped based on p-value and VIF
•	Logit showed better results as the accuracy was about 79%, precision of 73.8% and a recall of 62.4%, AUC of ROC curve was 0.83
