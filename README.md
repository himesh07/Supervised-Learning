![image](https://user-images.githubusercontent.com/108557163/221387349-96c56da5-e0e9-4a6b-9e45-24448b3fd35f.png)


This project is a study of Supervised Machine Learning using the Adult dataset. The goal of the study is to build a model that can predict whether an individual earns more than $50,000 per year based on various demographic and employment-related features.

Here's a brief overview of what the report covers:

Introduction: This section provides an overview of the study and the dataset used. The adult dataset contains information on over 32,000 individuals, including their age, education, occupation, and marital status.

Data preparation: This section describes how the data was prepared for analysis, including cleaning and formatting. The data is also split into a training set and a testing set.

Model building: This section describes how the model was built using various supervised machine learning algorithms, including logistic regression, decision trees, and random forests.

Model evaluation: This section evaluates the performance of the different models based on various metrics such as accuracy, precision, recall, and F1 score. The best performing model is identified and its predictions are compared to the actual values in the testing set.

Conclusion: This section summarizes the key findings of the study and provides recommendations for future work.

Overall, the report provides a comprehensive overview of the process of supervised machine learning, including data preparation, model building, and model evaluation. The report also demonstrates how the techniques can be applied to a real-world problem, namely predicting income based on demographic and employment-related features.


# Contents

## 1 Project Topic
### 1.1 Task
### 1.2 Goals

## 2 Data
### 2.1 Data Source
### 2.2 Data Description
### 2.3 Data Attributes
### 2.4 Data Summary
2.4.1 Missing Values and Loading the Data Set
<br>2.4.2 Removing ‘fnlwgt’
<br>2.4.3 Data Summary Statistics

## 3 Data Cleaning 
### 3.1 Data Type Change
### 3.2 Whitespace Removal
### 3.3 Missing Values
### 3.4 Check of Imbalanced Data Set 
3.4.1 Cleaning target variable
### 3.5 Conclusion of Data Cleaning

## 4 Exploratory Data Analysis
### 4.1 Univariate Analysis
4.1.1 Histogram of age
<br>4.1.2 Histogram of hours worked per week
<br>4.1.3 Histogram of capital gain
<br>4.1.4 Histogram of capital loss
<br>4.1.5 Histogram of education
<br>4.1.6 Histogram of workclass
<br>4.1.7 Histogram of education number
<br>4.1.8 Histogram of marital status
<br>4.1.9 Histogram of occupation
<br>4.1.10 Histogram of relationship
<br>4.1.11 Histogram of race
<br>4.1.12 Histogram of sex
<br>4.1.13 Histogram of native country
### 4.2 Bivariate Analysis
4.2.1 Relationship between age and annual income
<br>4.2.2 Relationship between capital gain and annual income
<br>4.2.3 Relationship between capital loss and annual income
<br>4.2.4 Feature Engineering
<br>4.2.5 Relationship between delta capital and annual income
<br>4.2.6 Relationship between hours per week and annual income
<br>4.2.7 Relationship between workclass and annual income
<br>4.2.8 Relationship between education and annual income
<br>4.2.9 Relationship between education num and annual income
<br>4.2.10 Relationship between marital status and annual income
<br>4.2.11 Relationship between occupation and annual income
<br>4.2.12 Relationship between relationship and annual income
<br>4.2.13 Relationship between race and annual income
<br>4.2.14 Relationship between sex and annual income
<br>4.2.15 Relationship between native country and annual income
### 4.3 Multivariate Analysis
4.3.1 Correlation Matrix
<br>4.3.2 Multivariate Categorical Analysis
### 4.4 Conclusion of Exploratory Data Analysis

## 5 Models
### 5.1 Marital status and Relationship: Multicollinearity?
### 5.2 Encoding categorical variables
### 5.3 Standardizing Feature Set
### 5.4 Multicollinearity Test
### 5.5 SMOTE: Synthetic Minority Over-sampling Technique
### 5.6 Train-Test split
### 5.7 Evaluation Metric
5.7.1 Logistic Regression
<br>5.7.2 Logistic Regression using SMOTE
<br>5.7.3 Random Forest
<br>5.7.4 Random Forest using SMOTE
<br>5.7.5 Gaussian Naive Bayes Classifier
<br>5.7.6 Gaussian Naive Bayes Classifier using SMOTE

## 6 Results and Analysis
### 6.1 Logistic Regression
6.1.1 Without SMOTE
<br>6.1.2 With SMOTE
<br>6.1.3 AUC
### 6.2 Random Forest
6.2.1 Without SMOTE
<br>6.2.2 With SMOTE
<br>6.2.3 AUC
### 6.3 Gaussian Naive Bayes
6.3.1 Without SMOTE
<br>6.3.2 With SMOTE
<br>6.3.3 AUC

## 7 Discussion and Conclusion
7.1 Discussion
<br>7.2 Conclusion
