# AUTOMATIC_TICKET_CLASSIFICATION
Building a Machine Learning Model to Classify the ticket category

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- to build a model that is able to classify customer complaints based on the products/services.
- Dataset is of size 78K tickets
- Performing Topic Modelling using Non Negative Matrix Factorization to analyze and classify tickets
- Classifying Categories:
  - Credit card / Prepaid card
  - Bank account services
  - Theft/Dispute reporting
  - Mortgages/loans
  - Others
 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1: Multinomial Naive Bayes Classifier - ROC AUC Score Train: 0.96 and ROC AUC Score Test: 0.94Train accuracy: 0.73, Test accuracy: 0.69, 
- Model 2: Logistic Regression - ROC AUC Score Train: 1.0, ROC AUC Score Test: 0.99, Train Accuracy : 0.95, Test Accuracy : 0.91
- Model 3: Decision Tree - ROC AUC Score Train: 1.0, ROC AUC Score Test: 0.85, Train Accuracy : 1.0, Test Accuracy : 0.76
- Model 4: Random Forest - ROC AUC Score Train: 1.0, ROC AUC Score Test: 0.98, Train Accuracy : 1.0, Test Accuracy : 0.83
- Model 5: Multinomial Naive Bayes Classifier with GridSearchCV - ROC AUC Score Train: 0.98, ROC AUC Score Test: 0.94, Train Accuracy : 0.85, Test Accuracy : 0.76
- Model 6: Logistic Regression with GridSearchCV - ROC AUC Score Train: 1.0, ROC AUC Score Test: 0.99, Train Accuracy : 0.94, Test Accuracy : 0.93
- Model 7: Decision Tree with GridSearchCV - ROC AUC Score Train: 0.97, ROC AUC Score Test: 0.94, Train Accuracy : 0.81, Test Accuracy : 0.78
- Model 6 is picked for making the inferences 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Numpy -- version -1.24.3
- Pandas -- version -1.4.2
- Matplotlib -- version -3.5.1
- TensorFlow -- version -2.14.0
- plotly -- version -5.9.0
- seaborn -- version -0.12.2
- nltk -- version -3.8.1
