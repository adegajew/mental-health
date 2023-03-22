# Mental Health and Psychological Distress

## 🔥 Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Installation](#installation) 
- [Metrics](#metrics)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

## 💢 Project Overview

This project is to analyze factors influencing psychological distress of medical students. Mental healh 

We use a dataset containing data on medical students' mental health in Switzerland: demographic information, self-reported health status, psychological tests results, and survey responses.  

## 💢 Problem Statement

With the given dataset we try to answer the following questions: 

- is there any strong correlation between mental health factors?
- are there any different patterns in approach to studies (academic efficacy, motivation or hours of study) depending on categorical variables?
- how gender, partnership status and language spoken by the medical students relates to mental health? 
- can we predict the occurrence of psychological distress looking at demographic variables and psychological tests results?

Psychological distress is a binary variable identified by the question 'During the last 12 months, have you ever consulted a psychotherapist or a psychiatrist for your health?' No/ Yes.

We use different ML algorithms: kNN, Logistic Regression, Decision Tree, XGBoost to predict  psychological distress.

## 💢 Installation
Anaconda distribution of Python should be just fine to run the code here (Python versions 3.*).

## 💢 Metrics

In order to check the relationship between variables we use Pearson's correlation coefficient and present the results using correlation matrix.

In order to compare what ML algorith would perform best we calculate confusion matrix and classification report. Since we are interested in both true positives and true negatives we use accuracy and F1 score to choose the right model. F1 score is especially useful because the dataset is inbalanced.

We use SHAP to explain the output of machine learning model.

## 💢 Results

The main findings and takeaways from the analysis of medical students' mental health are presented at the post [here](https://medium.com/@adegajew/where-does-students-psychological-distress-come-from-840e373ef36).


## 💢 Acknowledgments
Data can be downloaded from Kaggle at the link [here](https://www.kaggle.com/datasets/thedevastator/medical-student-mental-health) (the licensing for the data and other descriptive information can also be found there).

