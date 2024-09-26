# ANN-Classification-Churn

In churn classification I am having the data of shape (10000,14). In this the target variable is the Exited. The Input data that we are using to predict the Churn customers are :-CreditScore,Gender,Age,Geography,Tenure,Balance,NumOfProducts,HasCrCard,IsActiveMember and EstimatedSalary . After preprocessing and applying EDA on the dataset I applied ANN Modeling where training and validation set is producing an Accuracy rate of 85% and loss epoch is 0.35. I have set a Threshold of 0.5 ,So if the prediction probability is > 0.5 then the Customer is likely to churn.
