# Automatidata
Data analysis of Automatidata project (part of Google Advanced Data Analytics Certification)
This project is completed as a part of the Google Advanced Data Analytics Capstone Project.
It utilizes data analytics concepts and techniques covered in the professional certification course.

## Overview
Automatidata is a fictitious company created for educational purposes only.
Automatidata is a data analysis company which has received a project from the New York Taxi and Limousine Commisson.
The project is to predict the fare prices of taxi cab rides and perform analysis on the data to provide relevant insights

## Objectives
- Provide insights from the data
- Predict fares for taxi cab rides
- To determine if a passenger is a generous tipper (>20%)
- To build a machine learning model for predictions

## Analysis
A PACE strategy document was formulated to initiate the process and workflow.
An initial exploratory data analysis was conducted and the dataset was cleaned, structured for modelling.
Several outliers were identified in the data and trips with 0 fare or 0 total distance were removed.
Visualizations on tableau provided us with a better understanding of the data.
There is correlation between the variables which might affect the model.
A machine learning model was built to determine the fare prices and to predict if a customer is a generous tipper, 
using different methods such as Random Forest Classification,
Logistic Regression, Extreme Gradient Boosting and Decision Tree Classifier.

## Results
The results of the analysis were as follows:
- Ride duration was the highest contributing factor to the fare
- Trip distance and total amount are key variables in the model's prediction.
- There was a mean increase of $7 for each additional minute
- Comparisons between payment methods used by customers revealed tip amount variations
- The customer with tip amount >20% were predicted using the model
- The estimated fare amount was predicted.

## Solutions
Proposed solutions are as follows :
- Encouraging customers to pay with credit card increases the revenue
- The model can be used in their app to predict fares of cab rides beforehand.
- Beta testing of the model is recommended to gain better insights
- Additional information can improve the predictions and feedback

The results of the models are shown in the jupyter notebook, a brief overview of the scores of each model is given below :
|  model	 | precision  |  recall   |	   F1     |  accuracy  |
| -------- | ---------- | --------- | --------- | ---------- |
|  RF CV	 | 0.674919	  | 0.757312  | 0.713601	|  0.680233  |
|	RF test	 | 0.675297	  | 0.779091  | 0.723490	|  0.686538  |
|	XGB CV	 | 0.673074	  | 0.724487	| 0.697756	|  0.669669  |
|	XGB test |	0.675660	| 0.747978	| 0.709982	|  0.678349  |

**NOTE : Visualizations and charts can be found in the jupyter notebooks and executive summaries of each phase in the PACE strategy lifecycle.**

## Libraries Used
- numpy
- pandas
- sklearn
- xgboost
- matplotlib
- seaborn
