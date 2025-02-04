Introduction
Fraud detection in financial transactions is a critical challenge in the banking industry, as fraudulent activities cause significant financial losses worldwide. This project explores different machine learning models to classify fraudulent transactions effectively, ensuring high fraud detection rates while minimizing disruptions for legitimate users.

The dataset used in this project is a synthetic dataset provided by Kaggle, designed to simulate real-world banking transactions. It can be accessed at the following link:

https://www.kaggle.com/datasets/ealaxi/paysim1?resource=download

Dataset Description: 
 - The dataset contains 6,362,620 transactions, each labeled as fraudulent (1) or non-fraudulent (0). The available features are:

    . step: Time step of the transaction (hourly simulation).
   
    . type: Type of transaction (CASH_OUT, PAYMENT, TRANSFER, etc.).
   
    . amount: Transaction amount.
   
    . nameOrig: Unique identifier of the sender.
   
    . oldbalanceOrg: Sender's balance before the transaction.
   
    . newbalanceOrig: Sender's balance after the transaction.
   
    . nameDest: Unique identifier of the recipient.
   
    . oldbalanceDest: Recipient's balance before the transaction.
   
    . newbalanceDest: Recipient's balance after the transaction.
   
    . isFraud: Target variable (1 = Fraud, 0 = Legitimate).
   
    . isFlaggedFraud: Indicates if the transaction was flagged as fraud by the system.
   
Objective
  In this notebook, we will:
  
    .Clean and preprocess the dataset by handling missing values and encoding categorical variables.
    .Explore and analyze the data to identify patterns in fraudulent transactions.
    .Train multiple machine learning models, including Random Forest, SVM, LightGBM, and Neural Networks, to detect fraud.
    .Optimize model performance using threshold tuning and validation techniques.
    .Evaluate the final model and determine the best fraud detection strategy for deployment.

By the end of this project, we will identify the best-performing model that balances fraud detection accuracy with customer experience, ensuring security in financial transactions. 
