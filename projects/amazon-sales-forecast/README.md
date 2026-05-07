# Analyzing and Forecasting Amazon Product Sales Using R

## 📋 Overview
This project, completed for the University of Arizona DATA-375 Statistical Computing course, analyzes and forecasts Amazon product sales data. The analysis combines time series forecasting with machine learning techniques to provide actionable business insights.

## 📊 Data Preparation
- Collected and cleaned historical sales data and stock market data
- Handled missing values by classification into **MCAR, MAR, and MNAR** types
- Identified and handled outliers via **IQR analysis**
- Removed duplicates and standardized field conventions
- Completed feature engineering to build standardized training dataset

## 🔬 Methodology

### Time Series Analysis
- Aggregated product-category sales time-series data
- Generated **3- to 6-month sales forecast trends**
- Calculated **coefficient of variation** as a sales consistency metric

### Machine Learning Models
- **Random Forest** — ensemble learning for robust prediction
- **Support Vector Machine (SVM)** — for classification and regression tasks
- Feature selection techniques to filter key variables
- Hyperparameter optimization through cross-validation

### Business Analysis
- Constructed **business analysis matrix**
- Plotted **heatmaps** to explore price-rating-sales correlations
- Integrated forecast results with business insights

## 📈 Key Outcomes
- Achieved high accuracy in sales prediction tasks
- Provided quantitative foundations for inventory management
- Formulated recommendations for marketing strategy optimization
- Delivered data support for investment and business decisions

## 🛠️ Tech Stack
- **Language:** R
- **Libraries:** randomForest, e1071, caret, forecast, ggplot2, tidyverse
- **Methods:** Time Series Analysis, Random Forest, SVM, IQR Analysis, Heatmap Visualization

## 👤 Author
Jiayu Chen (Jayne)  
📧 chenjiayu@arizona.edu
