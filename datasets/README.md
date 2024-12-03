# FindDefault: Credit Card Fraud Prediction Capstone Project
This project involves predicting fraudulent transactions using a dataset containing credit card transactions made by European cardholders in September 2013. The dataset spans two days and includes 284,807 transactions, of which only 492 are fraudulent, making it highly imbalanced. The positive class (frauds) accounts for only 0.172% of all transactions. The goal is to build a classification model to predict whether a transaction is fraudulent.

## Dataset Description
**Time**: The number of seconds elapsed between each transaction and the first transaction in the dataset.
V1 to V28: Anonymized features derived using Principal Component Analysis (PCA). They represent various transaction characteristics.
**Amount**: The transaction amount.
**Class**: The target variable, where 0 indicates a non-fraudulent transaction and 1 indicates a fraudulent transaction.

## Data Cleaning Process
1. **Loading the Data:**
The dataset was imported from a CSV file for analysis.

2. **Understanding the Data:**
Key insights were gathered by examining the dataset's shape, structure, and basic statistics (mean, median, skewness, and kurtosis) using commands like info() and describe().

3. **Handling Missing Values:**
No missing values were found in the dataset.

4. **Removing Duplicates:**
Duplicate transactions were identified and removed to maintain data integrity.

5. **Outlier Treatment:**
Outliers were analyzed in both fraudulent and non-fraudulent transactions. Outliers in non-fraudulent transactions were capped, as those in fraudulent transactions could be important for modeling.

6. **Standardizing Features:**
The Amount and Time columns were standardized using StandardScaler to ensure consistency across features, which improves model performance.

7. **Feature Selection:**
Features were evaluated based on their correlation with the target variable (Class). Low-correlation features were removed to reduce dimensionality and enhance model efficiency.

8. **Saving the Cleaned Data:**
The cleaned dataset was saved as cleaned_data.csv for further analysis and model development.

## Conclusion
The cleaned dataset is ready for exploratory data analysis, feature engineering, and machine learning model training. This foundation will help build an effective model to predict credit card fraud.