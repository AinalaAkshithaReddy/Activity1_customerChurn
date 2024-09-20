# Activity1_customerChurn
# Customer Churn Prediction - EDA

## Project Overview
This project focuses on analyzing customer churn in a telecom company using the **Telco Customer Churn** dataset. The goal of this analysis is to identify patterns in the data that contribute to customer churn, which will help in building predictive machine learning models.

## Dataset Information
The dataset used in this project contains customer information including demographic details, services subscribed to, charges, tenure, and whether or not the customer churned.

### Key Features:
- `gender`: Male/Female.
- `SeniorCitizen`: Indicates whether the customer is a senior citizen (1) or not (0).
- `tenure`: Number of months the customer has stayed with the company.
- `MonthlyCharges`: Monthly bill amount.
- `TotalCharges`: Total amount charged to the customer.
- `Churn`: Target variable (Yes/No), indicating if the customer churned.

## Steps in Exploratory Data Analysis (EDA)

### 1. Data Inspection
The dataset was loaded and an initial inspection was done using `df.info()` and `df.head()` to check the data structure, column types, and missing values.

2. Descriptive Statistics
We calculated basic statistical information about the numerical columns (tenure, MonthlyCharges, TotalCharges) to understand their distributions.

3. Correlation Analysis
We created a correlation matrix to observe relationships between numerical variables, especially focusing on churn-related columns.

4. Visualizations
We used histograms and boxplots to visualize the distribution of key variables and how they relate to churn:

Distribution of Tenure, MonthlyCharges, and TotalCharges

5. Missing Values
We checked for missing values and handled any missing data found.

Conclusion
The EDA provided key insights into customer behavior, specifically:

Customers with higher tenure or lower monthly charges tend to stay with the company.
Contract type, internet service, and gender have distinct patterns related to churn.
This analysis sets the foundation for the machine learning phase of the project, where we will use these insights to build predictive models.