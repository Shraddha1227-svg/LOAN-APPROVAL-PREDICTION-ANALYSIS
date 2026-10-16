# LOAN-APPROVAL-PREDICTION-ANALYSIS
Loan Approval Prediction using Machine Learning: Developed a machine learning project to predict loan approval status using Logistic Regression, Decision Tree, and Support Vector Machine (SVM). Applied SMOTE and class weighting to handle class imbalance and compared model performance using accuracy, precision, recall, F1-score, and ROC-AUC.

This project aims to predict loan approval status using machine learning techniques. The dataset contains 45,000 records with features such as age, income, employment experience, home ownership, loan amount, loan intent, interest rate, credit history, and credit score.

Data preprocessing was performed by removing irrelevant variables and checking data quality. The target variable was imbalanced, so **SMOTE (Synthetic Minority Over-sampling Technique)** was applied to balance the training data. Class weights were also used to improve the models' ability to identify both classes.

Three machine learning algorithms were implemented: **Logistic Regression, Decision Tree, and Support Vector Machine (SVM)**. Their performance was evaluated using accuracy, precision, recall, F1-score, ROC-AUC, and training-testing accuracy.

The Weighted Decision Tree achieved the highest test accuracy of **87.34%**, followed by Weighted SVM at **83.38%** and Weighted Logistic Regression at **77.16%**. The results show that machine learning can support loan approval prediction, although actual lending decisions require additional financial assessment, fairness checks, and validation on real-world data.

**Tools Used:** Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, and Seaborn.

**Outcome:** Developed and compared three classification models to predict loan status and evaluated their performance on an imbalanced dataset.
