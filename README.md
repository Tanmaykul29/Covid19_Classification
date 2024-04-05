# COVID-19 Classification Project

## Overview
This project aims to predict the admission of confirmed COVID-19 cases to ICU using machine learning techniques. By early prediction, it assists in resource allocation and patient care planning, contributing to reducing mortality rates.

## Motivation
The unprecedented COVID-19 pandemic necessitated proactive measures to manage healthcare resources efficiently. Early ICU admission prediction aids in resource allocation and prioritization, potentially saving lives.

## Dataset
- **Size:** 5000 rows, 85 columns
- **Source:** Obtained as part of a data science course
- **Features:** Various clinical, demographic, and diagnostic indicators

## Methodology
1. **Exploratory Data Analysis (EDA):**
   - Utilized Pandas profiling, Seaborn, Matplotlib, and Plotly for comprehensive insights.
   - Conducted data cleaning to handle duplicates, null values, and outliers.

2. **Feature Selection:**
   - Employed 7 algorithms including Pearson correlation, SelectFromModel, SelectKBest, Recursive Feature Elimination, and VarianceThreshold to reduce dimensionality to 35.

3. **Model Building:**
   - Explored 13 classification algorithms such as Logistic Regression, SVM, Decision Trees, Random Forest, AdaBoost, Gradient Boosting, XGBoost, KNN, and Naive Bayes.
   - Utilized GridSearchCV for hyperparameter tuning.
   - Implemented a voting classifier to ensemble top-performing models.

4. **Evaluation:**
   - Achieved a testing accuracy of 85%, precision of 91%, and recall of 84%.

## Libraries Used
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Plotly
- Scikit-learn

## Conclusion
This project demonstrates the efficacy of machine learning in predicting ICU admissions for COVID-19 patients. The insights gained can inform healthcare resource allocation strategies and aid in optimizing patient care.
