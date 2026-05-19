# Medical-Insurance-Cost-Prediction-using-Linear-Regression

This repository contains a Jupyter Notebook that performs predictive analysis on medical insurance data. The project implements a Linear Regression model to estimate insurance charges based on patient demographics and health metrics.

Key Features:

Exploratory Data Analysis (EDA) with visualization.

Feature selection and data splitting.

Implementation of Linear Regression assumptions (Linearity, No Multicollinearity).

Model training and performance evaluation.

Importand Libraries
Code Content
# the most imp assumption

# X and Y have a linear relation i.e if on is increases other also increase or decrease with it

#input feature (independent column should not have any correlation --- No Multicollnearity )

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

df =pd.read_csv('insurance.csv')

df.head()

df.tail()

df.info()
