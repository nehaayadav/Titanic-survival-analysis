# Titanic-survival-analysis

🛳️ Titanic Survival EDA & Feature Engineering
📌 Project Overview

This project explores the famous Titanic dataset (from Kaggle) to uncover patterns behind passenger survival.
The goal is to perform Exploratory Data Analysis (EDA), feature engineering, and prepare the dataset for predictive modeling.

🔍 Steps Covered
1. Data Understanding
Basic exploration of the dataset (shape, columns, missing values).
Identification of categorical & numerical features.

2. Univariate Analysis
Distribution plots for Age, Fare, Pclass, Sex, etc
Checked missing values and potential outliers.

3. Bivariate Analysis
Categorical vs Target (e.g., Sex vs Survived, Pclass vs Survived).
Numerical vs Target (e.g., Fare vs Survived, Age vs Survived).
Category vs Category with target overlays (e.g., Sex + Pclass vs Survived).

4. Multivariate Analysis
Heatmaps to check correlation between numerical features.
Scatterplots for combinations like Age × Fare vs Survived.
Grouped analysis (Pclass + Sex, Cabin + Age, etc.).

5. Feature Engineering
Extracted Title from passenger names (Mr, Mrs, Miss, etc.).
Created FamilySize (SibSp + Parch + 1).
Derived IsAlone (binary feature from FamilySize).
Extracted Cabin Deck (first letter of cabin).
Created binned versions of Age & Fare for better grouping.

6. Key Insights
Females had a much higher survival rate.
Passengers in 1st class were more likely to survive.
Higher Fare was associated with better chances of survival.
Children and women had priority in lifeboats.
Titles carried hidden information about social status & survival.
Traveling alone decreased survival probability.

📊 Visualizations
Barplots for categorical comparisons.
Boxplots to explore distributions & outliers.
Heatmap for correlation.
Scatterplots for multivariate relations.

🚀 Next Steps
Apply machine learning models (Logistic Regression, Random Forest, etc.).
Compare performance with/without engineered features.
Optimize using cross-validation & feature importance analysis.

⚡ Requirements
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  

Dataset: Kaggle Titanic Dataset

Inspiration: Kaggle Titanic Survival Prediction Challenge
