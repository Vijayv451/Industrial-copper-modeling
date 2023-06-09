##    Industrial-copper-modeling 
# Libraries:

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
   
# Approach:

1 - skewness and outliers in the dataset.

2 - Transform the data into a suitable format and perform any necessary cleaning and pre-processing steps.


3 - ML Regression model which predicts continuous variable ‘Selling_Price’.


4 - ML Classification model which predicts Status: WON or LOST.


5 - Creating a streamlit page where you can insert each column value and you will get the Selling_Price predicted value or Status(Won/Lost)
   
#  To ignore warnings

   import warnings
   warnings.filterwarnings("ignore")
   
# Result
![image](https://github.com/Vijayv451/Industrial-copper-modeling/assets/125632137/c4921ae2-1aee-4c15-bd8b-3df32c2c2651)
![image](https://github.com/Vijayv451/Industrial-copper-modeling/assets/125632137/1657bd56-56f9-426c-b7cc-3034f9e06246)
![image](https://github.com/Vijayv451/Industrial-copper-modeling/assets/125632137/ce934f6f-c700-401a-933c-4585d9380eae)
![image](https://github.com/Vijayv451/Industrial-copper-modeling/assets/125632137/55fc7a0a-677e-433a-8247-e7ded7bfa834)
![image](https://github.com/Vijayv451/Industrial-copper-modeling/assets/125632137/53ae8256-d978-4d75-8f40-b68957d18567)
![image](https://github.com/Vijayv451/Industrial-copper-modeling/assets/125632137/37c254d5-044d-4c94-93d5-b6494728c2d2)
![image](https://github.com/Vijayv451/Industrial-copper-modeling/assets/125632137/fe796215-67d1-45e0-96cb-5ad16aab35ad)

   
