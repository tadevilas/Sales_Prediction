# Sales_Prediction
Mini Project Sales prediction

Objective : To predict the outlet sales

Python libraries neesd to install:
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib.pyplot as plt
from sklearn.impute import KNNImputer
from sklearn.feature_selection import SelectKBest
from sklearn.feature_selection import chi2

# Dataset Info:

The data set contains the following columns 

 -   Column                     Non-Null Count  Dtype  
---  ------                     --------------  ----- 

 0   Item_Identifier            8523 non-null   object 
 1   Item_Weight                7060 non-null   float64
 2   Item_Fat_Content           8523 non-null   object 
 3   Item_Visibility            8523 non-null   float64
 4   Item_Type                  8523 non-null   object 
 5   Item_MRP                   8523 non-null   float64
 6   Outlet_Identifier          8523 non-null   object 
 7   Outlet_Establishment_Year  8523 non-null   int64  
 8   Outlet_Size                6113 non-null   object 
 9   Outlet_Location_Type       8523 non-null   object 
 10  Outlet_Type                8523 non-null   object 
 11**  Item_Outlet_Sales          8523 non-null   float64**

 Based on the availble feature we wanted to predict the outlet sales

# Steps involve:

 1. check the data type, missing values, data preprocessing
 2. Univariet and bi-varient analysis for categorical and numerical features
 3. Missing values imputation and label encoding
 4. Features selection
 5. Select the best features and split the data
 6. Model building and Testing. 














