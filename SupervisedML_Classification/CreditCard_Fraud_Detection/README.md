# Credit Card Fraud Detection

This project applies supervised classification techniques to detect fraudulent credit card transactions from a highly imbalanced dataset. The workflow includes exploratory data analysis, model training, evaluation, and report generation.

## Project Goals
- Detect fraudulent transactions using machine learning classification models.
- Compare several classification algorithms under a consistent evaluation framework.
- Address the class imbalance problem that is typical of fraud detection applications.
- Document the methodology and results in a professional report.

## Dataset
The project uses the Credit Card Fraud Detection dataset, which contains 284,807 transactions and a binary target variable indicating whether each transaction is fraudulent or legitimate. The dataset is highly imbalanced, with fraudulent cases forming a very small fraction of the total observations.

## Workflow
1. Load and inspect the dataset.
2. Perform exploratory data analysis and visualize key distributions and correlations.
3. Split the data into training and test sets using stratification.
4. Train and compare classification models such as Logistic Regression, Linear SVM, Random Forest, Gradient Boosting, and Stacking.
5. Evaluate models using precision, recall, F1-score, and ROC-AUC.
6. Generate plots and compile the report.

## Project Structure
- data/: contains the raw dataset
- notebooks/: contains the exploratory and modelling notebooks
- figures/: stores generated plots in PDF and PNG format
- reports/: contains the LaTeX report source

## Dependencies
The required libraries are listed in Requirements.txt.
