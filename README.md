DJI Stock Prediction Project

This repository contains a comprehensive pipeline for analyzing and predicting DJI (Dow Jones Industrial Average) stock market trends. The project is structured into six Jupyter notebooks (A to F) that collectively handle data loading, preprocessing, analysis, feature engineering, feature selection, and predictive modeling.

Project Structure

A) DJI Loading Indicators

  Purpose: Import and consolidate multiple economic and financial indicators that might influence the DJI index.
  
  Key Steps:
  
  Load raw indicator data.
  
  Initial inspection and formatting for subsequent processing.

B) DJI Data Cleaning

  Purpose: Clean and preprocess the loaded data.
  
  Key Steps:
  
  Handle missing values.
  
  Normalize inconsistent formats.
  
  Outlier detection and treatment.

C) DJI Descriptive Analysis

  Purpose: Perform exploratory data analysis (EDA).
  
  Key Steps:
  
  Generate statistical summaries.
  
  Visualize distributions, correlations, and trends.
  
  Initial hypotheses formulation based on data behavior.

D) DJI Feature Engineering

  Purpose: Create additional meaningful features to enhance model performance.
  
  Key Steps:
  
  Construct technical indicators.
  
  Time-series lag features and moving averages.
  
  Encode cyclical and categorical information.

E) DJI Feature Selection

  Purpose: Identify the most relevant features for modeling.
  
  Key Steps:
  
  Apply feature importance techniques (e.g., correlation, feature importance scores).
  
  Dimensionality reduction when necessary.

F) DJI Modeling (OLS, LSTM, CatBoost, XGBoost, Naive Bayes, GRU)

  Purpose: Build and evaluate predictive models.
  
  Key Steps:
  
  Implement several machine learning models:
  
  Ordinary Least Squares (OLS)
  
  LSTM (Long Short-Term Memory networks)
  
  CatBoost
  
  XGBoost
  
  Naive Bayes
  
  GRU (Gated Recurrent Unit)
  
  Compare model performances.
  
  Final model selection and interpretation.

Requirements

  Python 3.8+
  
  Jupyter Notebook
  
  Main libraries:
  
  pandas, numpy
  
  scikit-learn
  
  matplotlib, seaborn
  
  tensorflow, keras
  
  catboost, xgboost
  
  statsmodels

Install dependencies:
  
  bash
  Copy
  Edit
  pip install -r requirements.txt
  Note: Create a virtual environment for better dependency management.

How to Run

  Clone this repository.
  
  Open the notebooks sequentially (A to F).
  
  Execute all cells in order.
  
  Analyze and interpret the results.

Author: Thomas Sogge

Project developed by Thomas Sogge










