## CAPSTONE-PROJECT-ON- AN -ONLINE-PAYMENT-FRAUD
Blossom Bank also known as BB PLC is a multinational financial services group, that offers retail and investment banking, pension management, asset management and payments services, headquartered in London,UK.
## Problem statement
Blossom Bank wants to build a Machine Learning model to predict online paymentfraud.
## Column Heads and meaning 
step: represents a unit of time where 1 step equals 1 hour
type: type of online transaction
amount: the amount of the transaction
nameOrig: customer starting the transaction
oldbalanceOrg: balance before the transaction
newbalanceOrig: balance after the transaction
nameDest: recipient of the transaction
oldbalanceDest: initial balance of recipient before the transaction
newbalanceDest: the new balance of recipient after the transaction
isFraud: fraud transaction
## Procedures 
Data loading and understanding was carried out to know what kind of problem there is to solve .
Data preparation which includes exploratory data analysis was carried out to define the  target variable(is fraud) and the feature variable 
Data prepocessing which include feature engineering  and creation of a dataframe  with a 50/50 ratio of fraud and non-fraud transactions to avoid -OVERFITTING and WRONG CORRELATIONS
Performed Random Undersampling and Oversampling to test the models to see if both the train and test label distribution were similarly distributed
At the end 8 Machine learning  Algorithms were applied to the dataset and the accuracy score, cross validation and roc_auc_list of the algorithms range from 95-100% overall.
## challenges Encountered 
I had some key errors , syntax errors and logic errors pop up during the process and was able to solve them thanks to Tiwalade ,Mr obinna and Mr Efemena.
