# Unraveling the Dynamics of Airfare Price Predictions
This is the capstone project for the University of San Diego’s ADS 599 Capstone Project course.
#### -- Project Status: [Completed]

## Project Intro
Airline ticket pricing is vital to the aviation industry, affecting travelers and airlines. Many factors, such as route demand, seasonality, competitor pricing, and operational costs, contribute to the complexity of pricing strategies.In the constantly changing landscape of the airline industry, accurately predicting ticket prices is crucial for travelers seeking cost-effective travel options and airlines aiming to optimize revenue. This project aims to develop a predictive model for airline ticket pricing, utilizing machine learning techniques to improve pricing accuracy and provide valuable insights into the factors that influence fare fluctuations. 


## Project Description
This project tackles issues of airfare uncertainty and limited filtering options in flight aggregation apps. We focus on two main objectives: predicting airfare changes over time and correlating airfare prices with desired amenities. For the first objective, we assist customers in predicting price changes within one day, one week, and one month. This empowers travelers with insights for making informed decisions on when to book flights. The second objective addresses the challenge of limited filtering options for specific features. Leveraging machine learning, our model helps users predict how airfare prices correlate with desired amenities, providing a more comprehensive understanding of the relationship between ticket prices and specific features.

## Methods Used
* Data preprocessing
* Exploratory Data Analysis
* Data Visualization
* Predictive Modeling
* Ensemble Modeling

## Technologies
* Python
* Google Colabratory

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- presentation
- voice recordings

## Required Python Packages
* import pandas as pd
* import zipfile
* import io
* import os
* import json
* import requests
* import matplotlib.pyplot as plt
* import seaborn as sns
* import numpy as np

* from pandas import json_normalize
* from datetime import datetime
* from io import BytesIO
* from scipy import stats
* from sklearn.neighbors import KNeighborsRegressor
* from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score
* from sklearn.model_selection import GridSearchCV, train_test_split, cross_val_score, KFold
* from sklearn.ensemble import RandomForestRegressor, GradientBoostingRegressor
* from sklearn.tree import DecisionTreeRegressor
* from sklearn.linear_model import LinearRegression, Lasso, Ridge, ElasticNet
* from sklearn.svm import SVR
* from xgboost import XGBRegressor
* from sklearn.neural_network import MLPRegressor
* from sklearn.preprocessing import StandardScaler

## Getting Started

1. Clone this repo using raw data.
2. add code and push new code into repo. To ensure cohesive code make sure to run all cells prior to upload.

## Featured Notebooks/Analysis/Deliverables

* [Presentations](https://docs.google.com/presentation/d/1cRvS6SqtaMvnvQHZATnPcAvk3zlHf92q/edit#slide=id.p38): Powerpoint Presentation

  
## Repository Contents
### [Code Library](https://github.com/VSbr22/Capstone/tree/main/code)
* [Data Extraction](https://github.com/VSbr22/Capstone/blob/main/code/Data_Extraction.ipynb): Details the steps taken to extract and store data from BFM API
* [Data Preparation](https://github.com/VSbr22/Capstone/blob/main/code/Data%20Preparation.ipynb): Details the steps taken to prepare and preprocess the raw data for analysis.
* [Data Exploration](https://github.com/VSbr22/Capstone/blob/main/code/Data%20Exploration.ipynb): The exploratory data analysis (EDA) phase is documented. It includes visualizations, statistical analyses, and insights gained from exploring the dataset.
* [Modeling](https://github.com/VSbr22/Capstone/blob/main/code/Modeling.ipynb): Application of eleven machine learning models to the preprocessed data. It covers model training, evaluation, and tuning processes. The results and performance metrics of each model are presented, providing a comprehensive overview of the modeling phase of the capstone project.
* [Notebook](https://github.com/VSbr22/Capstone/blob/main/code/Notebook.ipynb): Contains the contents from all other Notebooks.
  
### [Images Library](https://github.com/VSbr22/Capstone/tree/main/images)
* [Visualizations](https://github.com/VSbr22/Capstone/tree/main/images): Contains visualizations derived within the Notebook.

### [Data Folder](https://github.com/VSbr22/Capstone/tree/main/data)
* [Data](https://github.com/VSbr22/Capstone/blob/main/data/jsons.zip): Includes the original data used for this project, packaged within a ZIP folder.

## Authors
* [Dennis Myasnyankin](https://github.com/demyasa)
* [Vannesa Salazar](https://github.com/VSbr22)
* [Christine Vu](https://github.com/christinevu510)

