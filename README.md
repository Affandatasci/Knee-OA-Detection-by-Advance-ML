Human Knee OA Prediction Using Machine Learning
This repository presents a compact but complete machine learning workflow for predicting 2-year knee osteoarthritis (OA) progression using clinical, biomechanical, and imaging-derived data. The aim is to identify high-risk patients early.
Project Summary
The dataset includes demographics, biomarkers, gait and biomechanical measures, and quantitative imaging variables. The workflow covers data cleaning, feature pre-processing, class balancing, model training, and evaluation.
Main Steps
•	Conducted EDA, checked missing values, removed duplicates, and visualized key patterns.
•	Pre-processed numeric and categorical features using scaling, polynomial features, and one-hot encoding.
•	Managed class imbalance with SMOTE.
•	Trained three models: Logistic Regression, Random Forest, and HistGradientBoosting, optimized with cross-validated GridSearch.
•	Evaluated models with accuracy, F1, ROC–AUC, precision, recall, and confusion matrices.
•	Generated ROC curves, PR curves, and feature-importance visualizations.
•	Random Forest performed best and revealed the most influential predictors.
•	Saved the final model and outputs for future use.
