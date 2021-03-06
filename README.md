# Enron-Email-Dataset

Project work done as part of the Machine Learning part of the Udacity's  Data Analyst Nanodegree course.


## Table of Contents

1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, Acknowledgements



## 1. Installation

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. 
For the course a range of Scikit-Learn (`sklearn`) modules are used, which is one of the most popular machine learning libraries for Python .

The code is in Jupyter Lab notebooks, and they included modules which loads supporting .py files. The code should run with no issues using Python versions 3.7.



## 2. Project motivations

The goal of this project is to practice Machine Learning as part of [Udacity Data Analyst Nanodegree](https://classroom.udacity.com/nanodegrees/nd002/parts/439faa64-a2d3-45ca-8ecd-a21254ffd107) via a series of mini implementation projects for each of the CRISP steps (especially Data Preparation, Modelling and Evaluation).

The data explored is the [Enron Corpus](https://en.wikipedia.org/wiki/Enron_Corpus) which is a large database of over 600,000 emails generated by 158 employees of the Enron Corporation and acquired by the Federal Energy Regulatory Commission during its investigation after the company's collapse. The research questions are focused on identifying the key Persons Of Interest (POI) in this legal case.


## 3. File Descriptions


Running the `startup.py` file present in folder `/tools/' of this repository will automatically download the tarred and gzipped dataset and extract it for usage.  
Enron Email Dataset can be downloaded from : https://www.cs.cmu.edu/~enron/.  And it is the __May 7, 2015 Version of dataset__.

This aggregated _Enron email + financial dataset_ is stored in a dictionary as a _pickle file_, which is a handy way to store and load python objects directly. 
Use ```datasets_questions/explore_enron_data.py``` to load the dataset.

Each key in the dictionary is a person’s name and the value is a dictionary containing all the features of that person.   

The helper functions (```featureFormat()``` and ```targetFeatureSplit()``` in the folder /tools/ that can take a list of feature names and the data dictionary, and return a numpy array.



## 4. Summary of the results


In the folders you find the results of the following mini-projects:

2. Naive Bayes (GaussianNB)
3. SVM (SVC)
4. Decision Tree (DecisionTreeClassifier)
5. Choose your own algo:
   - KNN - K Nearest Neighbours (KNeigborsClassifier)
   - Random Forest (RandomForestClassifier)
6. Datasets questions - includes the initial analysis done on the datset
7. Regression - includes the regression analysis on bonus, salary and long_term_incentive variables of the dataset
8. Outliers - includes codes and python functions used to remove and check for the outliers.  
9. KMeans clustering_feature_scaling - Deals with feature scaling and clustering.  
11. Text Vectorizing + Text Learning 
12. Feature Selection - the miniproject was to remove the _signature word_ present in all emails.  
13. PCA - study on PCA dimension reduction
14. Validation - train-test-split, k-fold cross validation, StratifiedKFold, GridSearchCV
15. Evaluation - evaluation metrics
16. Final project





## 5. Licensing, Authors, Acknowledgements

Must give credit to Stack Overflow for the data. And Udacity for the course material.
