# FindDefault: Credit Card Fraud Prediction Capstone Project"

## Project Overview
Credit card fraud is a significant problem that affects both financial institutions and customers. This project uses machine learning techniques to build a model that can identify fraudulent credit card transactions, aiming to reduce the impact of fraud.

## Problem Statment 
A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
We have to build a classification model to predict whether a transaction is fraudulent or not.

## Project Structure
- **dataset(s)**: Contains the raw and cleaned datasets.
- **notebooks**: Jupyter notebooks for exploratory data analysis and model development.
- **visula**: Contains performance evaluation reports, visualisations and eda plots.
- **models**: Machine learning models used for modelling.
- **requirements.txt**: This file contains required packages along with their version

## Dataset
The dataset used in this project is a collection of credit card transactions from September 2013. It contains 284,807 transactions, of which 492 are identified as fraudulent. The dataset includes 23 features related to transaction details, excluding sensitive information like card numbers.

**Features**
1. V1, V2, ... V28: PCA-reduced features from the original dataset
2. Time: Time elapsed since the first transaction in the dataset
3. Amount: Transaction amount
4. Class: Target variable (1 for fraudulent, 0 for legitimate)

## Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook

## Modeling Techniques
**This project explores several machine learning algorithms, including:**
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machines (SVM)
5. Gradient Boosting Classifier
6. XGBoost
7. AdaBoost

## Evaluation Metrics
To assess the performance of the models, we used a variety of evaluation metrics, including accuracy, precision, recall, AUC score, and F1-score. These metrics provide a comprehensive understanding of how well the models perform, particularly in the context of imbalanced data, where traditional accuracy might not give a clear picture. Precision and recall are especially critical in fraud detection, as they focus on the ability to correctly identify fraudulent transactions while minimizing false positives and false negatives. The AUC score provides an overall measure of model performance across all classification thresholds, and the F1-score balances precision and recall, offering a single metric to evaluate the models’ effectiveness.

## Conclusion
In this project, we developed and evaluated several machine learning models to detect fraudulent credit card transactions, addressing the challenges posed by the highly imbalanced dataset. Through careful data preprocessing and feature engineering, we enhanced the models’ ability to identify fraudulent transactions effectively. The results show that the models performed well, with certain algorithms achieving high precision and recall—key factors in minimizing false negatives. This project provides valuable insights into the application of machine learning techniques for fraud detection and lays the groundwork for future improvements and further exploration in this field.

## Future Work
**While the current models have yielded promising results, there are several areas for improvement that could further enhance their effectiveness:

Advanced Feature Engineering: Exploring additional features, such as customer behavior analytics and transaction pattern recognition, could offer deeper insights into fraudulent activities, potentially improving model accuracy.

Real-Time Detection: Deploying the models in a real-time processing environment would allow for immediate fraud detection, reducing the time lag between detection and action, thereby minimizing potential financial losses.

Explainability and Transparency: Incorporating explainable AI techniques can help stakeholders better understand the decision-making process behind model predictions. This would not only foster trust in the system but also enable more informed business decisions.

## Business Insights
**The implementation of a robust credit card fraud detection system offers significant advantages for businesses, including:

Reduced Financial Losses: By accurately identifying fraudulent transactions, companies can mitigate losses related to chargebacks and fraud-related expenses, protecting their bottom line.

Enhanced Customer Trust: Strengthening security measures fosters greater customer confidence, which can lead to increased loyalty, enhanced brand reputation, and potentially higher transaction volumes.

Improved Operational Efficiency: Automating the fraud detection process reduces the reliance on manual reviews, allowing teams to concentrate on more strategic tasks, thereby optimizing operational resources and cutting costs.

Regulatory Compliance: A robust fraud detection system aids businesses in meeting regulatory requirements concerning financial transactions, reducing the risk of non-compliance and associated penalties.

Informed Data-Driven Decisions: The insights derived from fraud detection models can inform key business decisions, drive more effective marketing strategies, and enhance customer relationship management by identifying trends and patterns in consumer behavior.

By leveraging advanced fraud detection methods, organizations not only protect themselves from financial risks but also improve their operational effectiveness and overall customer experience.
