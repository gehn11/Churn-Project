# Churn-Project
The bank started to lose clients. Marketing department considered that maintaining current clients is cheaper than attracting new ones.
We need to predict if the client will churn or not. We have some records about the churning of the clients.
We need to make a model with the biggest F1 possible. Also it must be greater than 0.59.
Also we need to measure AUC-ROC and compare it with the F1.

Data description
Data is in the Churn.csv file.

Feature variables
- RowNumber — row index in data
- CustomerId — unique client identifier
- Surname
- CreditScore
- Geography — country of the client
- Gender
- Age
- Tenure
- Balance — account balance
- NumOfProducts — number of bank products that client uses
- HasCrCard — if client has a credit card or not
- IsActiveMember
- EstimatedSalary

Target variable
- Exited — if the client churned or not

We achieved to make a model that has the F1 value of more than targeted 0.59. The biggest F1 value we got is 0.5991. The AUC-ROC value of the model is 0.8614.
