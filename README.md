# Titanic Survival Prediction

This project focuses on predicting passenger survival in the Titanic dataset using machine learning techniques. The workflow includes exploratory data analysis, missing value handling, feature engineering, model development, dimensionality reduction, feature selection, hyperparameter optimization, and ensemble learning.

The main engineered features include Title, FamilySize, IsAlone, HasCabin, Deck, LogFare, and FarePerPerson. Several models were compared, including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. PCA and SelectKBest feature selection were also evaluated.

The final model is a Soft Voting Ensemble combining Tuned Logistic Regression and Tuned Feature-Selected Gradient Boosting. The best Kaggle public leaderboard score achieved in this project is 0.77990.

## Files

- `titanic_project.ipynb`: Main notebook including preprocessing, modeling, evaluation, and submission.
- `titanic_project_report.docx`: Project report.
- `titanic_presentation.pptx`: Project presentation.
- `submission.csv`: Final Kaggle submission file, if included.

## Main Methods

- Exploratory Data Analysis
- Feature Engineering
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- PCA
- SelectKBest Feature Selection
- Grid Search CV
- Soft Voting Ensemble
