# Internet Traffic Classification And Recognition With Statistical Approach And Intrusion Detection
The machine learning (ML) technique is based on the labeled dataset. In this technique, a machine learning classifier is trained as input, and then using the trained sample prediction, unknown classes are classified. I first establish a reference standard performance for five classifiers (Random Forest, AdaBoost.M1, C 4.5, MLP, and SVM) using publicly available network traffic NSL KDD datasets. The features are calculated using the wrapper method and then the ML classifier is trained with these features with known traffic classes and creates the classifier model known as the Memorization process. This model is then used to classify unknown traffic known as testing or Generalization process. Five ML algorithms are used for IP traffic classification with mentioned datasets and also intrusions are detected for the same datasets. Finally, 
performance analysis is done with the help of several evaluation metrics.

## Objectives
-->To study and train machine learning models to classify the network traffic.

-->To build a predictive model that distinguishes between suspicious behaviour (network intrusions) and normal traffic.

## KDD Dataset 
The dataset used in this project is the NSL-KDD dataset from the University of New Brunswick, Canada. The dataset is an improved version of the KDDCUP’99 datasets from DARPA Intrusion Detection Evaluation Program. The NSL-KDD dataset used in this project consists of 125,973 records training set and 22,544 records test set with 42 attributes/features for each connection sample including class label containing the attack types. After loading the dataset into Python (Jupyter Notebook) development environment, the first task performed was mapping services into 19 traffic classes and various attack types into four attack classes in the datasets.

##   
This project was made for the course CS6611 - Creative and innovative project
