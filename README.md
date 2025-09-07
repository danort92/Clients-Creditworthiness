# Clients-Creditworthiness

![image](images/credit-score-rating-concept-tiny-characters-with-huge-pile-banknotes-credit-card-brilliant-banking-service-clients-creditworthiness-poster-banner-flyer-cartoon-people-vector-illustration_87771-14497.jpg)

A model has been created capable of estimating the creditworthiness of a customer, in order to help the dedicated team understand whether or not to accept the request for the issuance of the credit card.
The anonymized data is organized in 2 csv files present in the credit_card_approval folder.

The project follows these steps:

* _Initial EDA, in order to analyse potential interesting patterns and anomalies;_
* _Preprocessing to clean the data for the training phase, defining the target label (not included in the original dataframe) and resampling with different techniques - SMOTE, RUS, ADASYN, SMOTEENN;_
* _Test different classifiers: Logistic Regression, Decision Tree, Random Forest, SGD, KNN, Gradient Boosting and XGBoost;_
* _Fine tune the classifiers to find their best hyperparameters through Randomized Search._
