## Overview

Business communities in the United States face growing workforce demands and increasingly rely on foreign talent to fill skill shortages. However, reviewing and approving visa applications is complex and time-consuming due to the rising number of applicants each year.

This project builds a machine learning–powered visa approval prediction system to streamline candidate screening and improve decision efficiency.

## Problem Statement

The Office of Foreign Labor Certification (OFLC) processes a rapidly increasing number of visa applications annually, making manual case review slow and resource-intensive. The absence of an automated prioritization system delays decisions and reduces operational efficiency.

## Objective

Develop a predictive classification model to identify applicants with a higher probability of visa approval and assist in data-driven certification decisions.

## Approach

• Performed exploratory data analysis to identify key demographic, employment, and wage-related drivers influencing visa case status.

• Engineered features and handled missing values, categorical encoding, and preprocessing for model readiness.

• Built and compared multiple classification models:
Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, and AdaBoost.

• Performed hyperparameter tuning on high-performing ensemble models using GridSearchCV.

• Evaluated models using ROC-AUC, Accuracy, Precision, Recall, and F1-score to select the most reliable classifier.

Skill set applied

Python, Pandas, NumPy, Scikit-learn, XGBoost, EDA, Feature Engineering, Classification Modeling, Model Evaluation (ROC-AUC, Precision, Recall, F1-score), Hyperparameter Tuning.

## Result
Final Model: AdaBoost (Tuned)

Test Performance Metrics
• ROC-AUC: 0.756
• Accuracy: 69.17%
• Precision: 80.02%
• Recall: 71.77%
• F1-Score: 0.757

The tuned AdaBoost model achieved strong precision and balanced recall, effectively identifying high-probability approval cases while controlling false approvals.

From a business perspective, this enables:
• Faster visa case screening
• Improved approval decision consistency
• Better prioritization of high-likelihood applicants
• Reduced administrative workload through data-driven filtering
