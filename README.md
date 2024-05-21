# Loan-Approval-Prediction-
# Problem Statement
       LOANS are the major requirement of the modern world. By this only, Banks get a major part of the total profit. It is beneficial for students to manage their education and living expenses, and for people to buy any kind of luxury like houses, cars, etc.

But when it comes to deciding whether the applicant’s profile is relevant to be granted with loan or not. Banks have to look after many aspects.

So, here we will be using Machine Learning with Python to ease their work and predict whether the candidate’s profile is relevant or not using key features like Marital Status, Education, Applicant Income, Credit History, etc.

# Features In The Dataset
1. Loan -	A unique id
2. Gender	- Gender of the applicant Male/female
3. Married-	Marital Status of the applicant, values will be Yes/ No
4. Dependents	- It tells whether the applicant has any dependents or not.
5. Education - It will tell us whether the applicant is Graduated
or not.
6. Self_Employed - This defines that the applicant is          
self-employed i.e. Yes/ No
7.	ApplicantIncome -	Applicant income
8.	CoapplicantIncome -	Co-applicant income
9. LoanAmount - 	Loan amount (in thousands)
10. Loan_Amount_Term	- Terms of loan (in months)
11.	Credit_History -	Credit history of individual’s repayment of
their debts
12.	Property_Area	- Area of property i.e. Rural/Urban/Semi-urban
13.	Loan_Status - 	Status of Loan Approved or not i.e. Y- Yes,   
 N-No

# Importing Neccessary Libraries
 - import pandas as pd
 - import numpy as np
 - import matplotlib.pyplot as plt
 - import seaborn as sns
 - from sklearn import preprocessing
 - from sklearn.model_selection import train_test_split
 - from sklearn.neighbors import KNeighborsClassifier
 - from sklearn.ensemble import RandomForestClassifier
 - from sklearn.svm import SVC
 - from sklearn.linear_model import LogisticRegression
 - from sklearn import metrics

Developed a machine learning model to predict loan approval using Python, leveraging key features such as Marital Status, Education, and Credit History. Conducted data preprocessing, visualization, and model evaluation, achieving an 82% accuracy with the Random Forest Classifier."

# Conclusion
   The Random Forest Classifier provided the best accuracy with a score of 82% on the testing dataset. To achieve better results, ensemble learning techniques such as Bagging and Boosting can be explored.


