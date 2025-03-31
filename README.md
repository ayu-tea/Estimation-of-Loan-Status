# Estimation-of-Loan-Status
## OBJECTIVE:
The goal of this project is to predict whether a loan applicant will be approved (Loan_Status) based on various financial and demographic factors. The project involves data preprocessing, feature engineering, model training, and hyperparameter tuning to achieve high prediction accuracy.
## PROJECT WORKFLOW:
### 1. **Data Preprocessing & Feature Engineering**
*  Handled missing values using KNN Imputation & mode/median replacement
* Encoded categorical variables using One-Hot Encoding
* Standardized numerical features using StandardScaler
* Removed low-importance features based on Feature Importance Analysis

### 2. **Model Training & Evaluation**
*Implemented:*
*  Random Forest Classifier
* Decision Tree CLassifier
* Support Vector Machine
* Naïve Bayes Classifier

*Performance Metrics used:*
* Accuracy Score
* Confusion Matrix & Classification Report
* Future Importance Analysis

## HYPERPARAMETER TUNING:
* Optimized max_depth, min_samples_split, n_estimators, etc., for Decision Tree & Random Forest
* Adjusted C & kernel for SVM
* Tweaked priors & var_smoothing for Naïve Bayes

## VISUALIZATIONS AND INSIGHTS:
* Loan Status Distribution
* Feature COrrelations
* Incom vs Loan Amount Analysis
* Model Performance Comparison

## KEY OUTCOMES AND FINDINGS:
* Credit History, Applicant Income, and Loan Amount were the most influential features.
* Random Forest performed best after hyperparameter tuning.
* Optimized models significantly improved prediction accuracy.
