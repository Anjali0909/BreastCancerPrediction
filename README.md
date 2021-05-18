# BreastCancerPrediction

## Team Members

Anjali Badlani 03 D12C
Sejal Kriplani 35 D12C
Khushi Makhijani 38 D12C

##  Problem Statement

We are using the Breast Cancer Wisconsin (Diagnostic) Database, we can create a classifier that can help diagnose patients and predict the likelihood of a breast cancer. A few machine learning techniques will be explored. In this exercise, Support Vector Machine is being implemented with highest accuracy.

## Dataset Used

The dataset we used is given in the URL:
https://www.kaggle.com/syedadaraqshan/breast-cancer-prediciton-using-machine-learning

## Objective

1. Identifying the problem and Data Sources
2. Exploratory Data Analysis
3. Pre-Processing the Data
4. Build model to predict whether breast cell tissue is malignant or Benign

## Algorithms Implemented

From the dataset, we will analysis and build a model to predict if a given set of symptoms lead to breast cancer. This is a binary classification problem, and a few algorithms are appropriate for use. Since we do not know which one will perform the best at the point, we will do a quick test on the few appropriate algorithms with default setting to get an early indication of how each of them perform. We will use 10 fold cross validation for each testing.

The following non-linear algorithms will be used, namely: Classification and Regression Trees (CART), Linear Support Vector Machines (SVM), Gaussian Naive Bayes (NB) and k-Nearest Neighbors (KNN).

Classification and Regression Trees (CART): CART are commonly used in data mining with the objective of creating a model that predicts the value of a target (or dependent variable) based on the values of several input (or independent variables).

Linear Support Vector Machines (SVM): SVM divides the data into two classes by a line, if the margin is more it means classes are better separated, and if there are more than two classes the line is replaced  by a hyperplane. 

Gaussian Naive Bayes (NB): A Gaussian Naive Bayes algorithm is a special type of NB algorithm. It’s specifically used when the features have continuous values. It’s also assumed that all the features are following a gaussian distribution i.e, normal distribution

 k-Nearest Neighbors (KNN): K-nearest neighbors (KNN) is a type of supervised learning algorithm used for both regression and classification. KNN tries to predict the correct class for the test data by calculating the distance between the test data and all the training points.
 
 
 Since, after standardizing the data and Comparing the algorithm ,SVM was giving better performance. Wr prepared the model using SVM and attained the accuracy of more than 95%.
 
