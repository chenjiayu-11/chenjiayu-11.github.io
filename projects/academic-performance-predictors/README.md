# Academic Performance Revisited: Identifying Key Predictors of High Achievement in Portuguese Secondary Students

## 📋 Overview
This project, completed for the University of Washington DATA 467 course, investigates the key predictors of high academic achievement among Portuguese secondary students. The study integrates traditional academic performance data with social media sentiment analysis to build comprehensive predictive models.

## 📊 Dataset
- **UCI Math Performance Dataset:** 395 students, 33 variables
- **Additional Data:** Social media user comment data for sentiment analysis
- **Preprocessing:** Missing value handling, sensitivity analysis, standardized dataset construction

## 🔬 Methodology

### Sentiment Analysis Component
- Collected and cleaned social media comment data
- Applied **Natural Language Processing (NLP)** techniques
- Built sentiment classification models using **SVM** and **deep learning** algorithms

### Regression Analysis Component
- Constructed full and simplified linear regression models
- Diagnosed multicollinearity via **Generalized Variance Inflation Factor (GVIF)**
- Conducted **nested F-tests** for model selection
- Applied **square root transformation** for distribution violations

### Advanced Modeling
- Constructed **Poisson Generalized Linear Models** with log link function
- Assessed overdispersion
- Converted coefficients to **incidence rate ratios** for interpretability

### Model Comparison
- Compared competing frameworks using **AIC criteria**
- Performed residual diagnostics
- Quantified variable correlations
- Detected extreme leverage points

## 📈 Key Findings
- **Prior academic performance** identified as the core predictor of math achievement
- **Course failure** quantified as having a significant negative effect
- High-precision positive-negative emotion recognition achieved on test set
- Group difference characteristics clarified through statistical analysis

## 🛠️ Tech Stack
- **Languages:** Python, R
- **Machine Learning:** SVM, Deep Learning
- **NLP:** Text preprocessing, sentiment classification
- **Statistics:** Linear Regression, Poisson GLM, GVIF, AIC, F-tests
- **Libraries:** scikit-learn, TensorFlow/PyTorch, NLTK, caret, glm2

## 👤 Author
Jiayu Chen (Jayne)  
📧 chenjiayu@arizona.edu
