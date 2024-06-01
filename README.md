# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project aims to detect fraudulent credit card transactions using machine learning algorithms. The dataset used for this project is obtained from Kaggle and contains a comprehensive set of transaction records, with attributes encoded as V1 to V31. Two machine learning models, Logistic Regression and Random Forest, were implemented to classify the transactions as fraudulent or legitimate.

## Dataset
- Source: Kaggle Credit Card Fraud Detection Dataset
- File: creditcard.csv
- Rows: 284,800
- Columns: 31 (V1 to V31)
<img width="744" alt="image" src="https://github.com/sureshmrd/creditcard_fraud_detection/assets/123853377/f3091a91-31d3-4a43-a8a9-bb4febc7fdc9">

## Algorithms Used
1. **Logistic Regression**:
   - A statistical model that uses a logistic function to model a binary dependent variable.
   - Accuracy: ~96%
2. **Random Forest**:
   - An ensemble learning method that operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes of the 
     individual trees.
   -  Accuracy: ~94%

## Libraries Used
- NumPy: Fundamental package for scientific computing with Python.
- Pandas: Powerful data manipulation and analysis library for Python.
- Scikit-learn (sklearn): A machine learning library for Python, used for implementing the machine learning algorithms.

## Conclusion
This project demonstrates the use of machine learning algorithms for detecting credit card fraud. The Logistic Regression model achieved a slightly higher accuracy compared to the Random Forest model. Both models show promising results and could be further improved with additional feature engineering and hyperparameter tuning.
