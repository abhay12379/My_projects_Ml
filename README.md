 Credit Card Eligibility Prediction :

This project aims to build a machine learning model that determines whether an individual is eligible for a credit card based on various demographic, financial, and behavioral attributes. The dataset used is imbalanced, and the workflow includes comprehensive preprocessing, exploratory data analysis (EDA), feature selection, and model evaluation using multiple classification algorithms.

Key Features:

Data Preprocessing & CleaningHandled null values, dropped low-importance features using mutual information and correlation analysis.

Imbalanced Dataset HandlingAddressed class imbalance using SMOTENC for categorical and numerical features.

Feature SelectionEmployed statistical techniques like:

Mutual Information

Chi-Square Test

ANOVA F-test

Models Implemented :

Logistic Regression

Decision Tree

Support Vector Classifier (SVC)

Random Forest

XGBoost

Model EvaluationEvaluated with metrics such as:

Accuracy, Precision, Recall, F1 Score

ROC-AUC and ROC Curve plotting

Cross-validation scores

VisualizationData and model insights were visualized using Seaborn, Matplotlib, and Plotly.

 Tools & Libraries :

pandas, numpy, matplotlib, seaborn, plotly

scikit-learn, xgboost, imblearn

Feature selection: mutual_info_classif, f_classif, chi2

Model evaluation: roc_auc_score, cross_val_score, etc.

Outcome:

Successfully developed and evaluated multiple models to predict credit card eligibility, with insights into the most influential features impacting creditworthiness.

