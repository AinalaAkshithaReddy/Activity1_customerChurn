PROJECT OVERVIEW
The objective of this project is to predict whether a customer will churn (i.e., discontinue service) based on various features like tenure, contract type, monthly charges, and usage of additional services. Understanding churn behavior is critical for developing retention strategies.

DATA PREPROCESSING
Missing Values: No missing values were found in the dataset.
Encoding: Categorical variables were label encoded to convert them into numerical values suitable for modeling.
Feature Selection: Unnecessary columns were removed, and relevant features were retained for modeling.
Models Implemented

LOGISTIC REGRESSION
Description: A linear model used to establish the relationship between independent variables and the likelihood of customer churn.
Evaluation: Confusion Matrix, Classification Report.
Insights: Highlights how each feature (e.g., tenure, MonthlyCharges) influences churn probability. The model is highly interpretable and provides clear coefficients indicating the direction of impact.

DECISION TREE
Description: A tree-based model that creates decision rules based on feature splits.
Evaluation: Decision tree visualization and feature importance analysis.
Insights: Provides actionable decision rules, such as "customers with short tenure and high monthly charges are likely to churn." Visual representation makes it easy to interpret how individual features contribute to the churn decision.

RANDOM FOREST
Description: An ensemble model combining multiple decision trees to enhance predictive power and reduce overfitting.
Evaluation: Confusion Matrix, Feature Importance plot.
Insights: Consistently identifies key features like Contract type, OnlineSecurity, and MonthlyCharges as critical factors. The ensemble approach improves model robustness and accuracy compared to a single decision tree.

XGBoost
Description: A powerful gradient boosting algorithm known for handling complex feature interactions effectively.
Evaluation: Confusion Matrix, Feature Importance plot using SHAP values for interpretability.
Insights: Captures complex relationships between features, providing high accuracy and detailed insights. Especially useful for identifying subtle patterns, such as interaction effects between service types and charges.