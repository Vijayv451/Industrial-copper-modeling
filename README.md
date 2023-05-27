##    Industrial-copper-modeling 

# Approach:

1 - skewness and outliers in the dataset.

2 - Transform the data into a suitable format and perform any necessary cleaning and pre-processing steps.


3 - ML Regression model which predicts continuous variable ‘Selling_Price’.


4 - ML Classification model which predicts Status: WON or LOST.


5 - Creating a streamlit page where you can insert each column value and you will get the Selling_Price predicted value or Status(Won/Lost)

# Libraries:

# library
   import pandas as pd
   
   import numpy as np
  
   import matplotlib.pyplot as plt
  
   import seaborn as sns
   
   from scipy.stats import skew
   
   from sklearn.model_selection import train_test_split
   
   from sklearn.tree import DecisionTreeRegressor
   
   from sklearn.metrics import mean_squared_error, r2_score
   
   from sklearn.model_selection import GridSearchCV
   
   from sklearn.tree import DecisionTreeClassifier
   
   from sklearn.metrics import accuracy_score, confusion_matrix
   
   from sklearn.preprocessing import StandardScaler, OneHotEncoder,LabelBinarizer
   
   from sklearn.metrics import  classification_report, roc_curve, auc
   
#  To ignore warnings
   import warnings
   
   warnings.filterwarnings("ignore")
   
 
   
