# Credit Risk Classification

## Overview
This project aims to build and evaluate a logistic regression model to classify the risk associated with loans. By analyzing loan data, the model predicts whether a loan is likely to be a healthy loan (0) or a high-risk loan (1). This classification is crucial for financial institutions to manage and mitigate potential loan defaults effectively.

## Data
The dataset, `lending_data.csv`, contains various financial metrics such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt, alongside the loan status which indicates whether a loan is healthy or high-risk.

## Methodology
The project follows these key steps:

### Data Preprocessing
- **Data Splitting:** The data is split into training and testing sets to ensure a robust evaluation of the model's performance.
- **Feature Selection:** Features are selected based on their relevance to the loan status, excluding the target variable itself from the feature set.

### Model Building
- A logistic regression model is instantiated and trained using the training dataset. This model is chosen for its efficiency and effectiveness in binary classification tasks.

### Model Evaluation
- The model's performance is evaluated using accuracy and balanced accuracy scores, alongside a detailed classification report that includes precision, recall, and f1-score for each class.

## Results
The logistic regression model demonstrated high accuracy in predicting loan status, with an accuracy score of 99.18% and a balanced accuracy score of 95.20%. The model showed excellent precision in identifying healthy loans and good precision for high-risk loans, albeit with a notable imbalance in the dataset towards healthy loans.

## Conclusion
The logistic regression model is highly effective in classifying loans into healthy and high-risk categories. However, the dataset's imbalance towards healthy loans suggests the need for further analysis and potentially more sophisticated models or rebalancing techniques to improve high-risk loan detection.

## Requirements
- Python 3.8+
- Pandas
- NumPy
- scikit-learn

****
