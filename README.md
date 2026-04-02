# Dataset Overview
The Behavioral Risk Factor Surveillance System (BRFSS) 2015 dataset is a large-scale health survey collected by the Centers for Disease Control and Prevention (CDC) in the United States. It contains self-reported data from hundreds of thousands of individuals, focusing on health-related risk behaviors, chronic conditions, and use of preventive services.
## Key characteristics of Dataset:
- Size: ~250,000+ survey responses
- Type: Tabular, structured data
- Target Variable: Diabetes status (binary or multi-class depending on preprocessing)
## Problem Type
- Supervised Learning for Classification Problem
- Goal: Predict whether a patient has diabetes based on his/her survey response
## Challenges from Dataset
- Class imbalance
- Feature correlation and redundancy
# Project Objectives & Key Results
## Objective 1: Perform Comprehensive Exploratory Data Analysis (EDA)
Key Results:
- Analyze and visualize distributions of key features (BMI, age, health indicators)
- Identify and handle missing values, outliers, and data inconsistencies
- Evaluate class imbalance in diabetes labels
- Discover key correlations between features and diabetes outcome
## Objective 2: Develop and Evaluate Machine Learning Models
Key Results:
- Train at least 3 models (e.g., AdaBoost, Random Forest, Gradient Boosting)
- Evaluate models using Accuracy, Precision, Recall, F1-score, and ROC-AUC
- Perform fine-tune models to get better performance on specific metrics
- Achieve target performance:
  - ROC-AUC ≥ 0.80
  - Recall ≥ 0.75 for diabetes class
- Select champion Machine Learning Model based on its overall performance
## Objective 3: Analyze Decision Threshold Trade-offs for Champion Model
Key Results:
- Generate Precision–Recall curves to evaluate trade-offs
- Analyze how threshold changes impact Precision and Recall
- Plot ROC curves to study TPR vs FPR behavior
- Identify optimal thresholds to balance between Recall and Precision ; between TPR and FPR
## Objective 4: Analyse Feature Importance on Champion Model
Key Results:
- Apply feature importance techniques (e.g., tree-based importance, permutation importance)
- Identify top contributing features to diabetes prediction
- Provide interpretable insights into key risk factors
