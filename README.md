# Fraud Detection in Credit Card Transactions

This project focuses on developing machine learning models to detect fraudulent credit card transactions, aiming to minimize financial losses and maintain customer trust for Mastercard, a leading global credit card provider in Europe.

## Overview

The project addresses the challenges faced by Mastercard's Fraud Detection Department in reducing false positives and false negatives associated with fraudulent transactions. Leveraging historical transaction data, machine learning models are employed to enhance fraud detection accuracy compared to the existing rule-based system.

### Objectives

- Reduce False Positives: Minimize legitimate transactions mistakenly identified as fraudulent.
- Reduce False Negatives: Increase the detection rate of actual fraudulent transactions.

## Contents

- **Documentation**: Comprehensive documentation detailing the project's objectives, challenges, data understanding, modeling, evaluation, and recommendations.
- **Code**: Python scripts used for data analysis, model development, evaluation, and model serialization.
- **Model Files**: Pickled Logistic Regression and Random Forest models for deployment.

## Key Components

- **Data Source**: Kaggle dataset comprising credit card transactions from European cardholders over two days in September 2013.
- **Models Evaluated**: Logistic Regression, Random Forest, Gradient Boosting.
- **Model Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, AUPRC.

## Model Deployment

### Models Selected for Deployment

- **Logistic Regression Model**
  - File: `logistic_regression_model.pkl`
  - Performance Metrics: Accuracy - 97.32%, Precision - 5.23%, Recall - 92.65%, F1 Score - 9.91%, AUPRC - 79.5%

- **Random Forest Model**
  - File: `random_forest_model.pkl`
  - Performance Metrics: Accuracy - 99.95%, Precision - 83.22%, Recall - 87.50%, F1 Score - 85.30%, AUPRC - 88.35%

### Usage

The pickled models can be loaded and utilized for fraud detection in credit card transactions. Refer to the accompanying documentation for further details on deployment, model loading, and usage instructions.

## Recommendations

- Deploy Logistic Regression as an initial filter followed by Random Forest for enhanced precision and recall.
- Explore unsupervised learning and deep learning techniques for continued improvement in fraud detection.
- Regularly monitor and update models to adapt to evolving fraud patterns.

## Contributors

- Mwenda James

## License

This project is licensed under MIT License. Refer to the LICENSE file for details.
