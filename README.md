# LOAN-ELIGIBILITY-CRITERIA
Overview
This project aims to streamline the loan approval process by predicting loan eligibility using machine learning. By analyzing applicant information such as income, credit history, and demographics, financial institutions can make data-driven decisions, improving efficiency and fairness in loan allocation.

**Features**
**Data Preprocessing:**
Handling missing values and outliers.
Encoding categorical variables.
Feature scaling for model compatibility.
**Exploratory Data Analysis (EDA):**
Statistical summaries and visualizations to uncover trends.
Analysis of factors impacting loan eligibility.
**Machine Learning Models:**
Training and comparison of multiple classifiers (e.g., Logistic Regression, Decision Trees, Random Forest).
Hyperparameter tuning for improved performance.
**Model Evaluation:**
Metrics include accuracy, precision, recall, F1-score, and ROC-AUC.
Cross-validation to assess generalization.

**Tech Stack**
Programming Language: Python
Libraries Used: matplotlib, numpy, pandas, sklearn, seaborn

**Project Highlights**
Exploratory Data Analysis (EDA)
Income and Loan Amount Analysis: Visualization of income brackets and corresponding loan approval rates.
Credit History Impact: Quantitative analysis of the correlation between credit history and loan approval.
Loan Amount Trends: Examination of how loan amounts vary across demographics.
Machine Learning Models
Logistic Regression for baseline modeling.
Random Forest for feature importance and improved accuracy.
Gradient Boosting for optimizing predictions on imbalanced datasets.


Results
Best Model: Naive Bayes achieved an accuracy of 82.93%, outperforming other models such as Decision Tree (70.73%).
Key Insights:
Applicants with a good credit history have a 75% higher approval rate compared to those without.
The top three features influencing loan eligibility are:
Credit History
Applicant Income
Loan Amount

Future Enhancements
Feature Engineering: Add new features such as applicant job stability, spending patterns, or regional economic data.

Scalability: Integrate with real-time data pipelines for continuous model predictions.
Contributing
Contributions are welcome! Please fork the repository, make changes, and submit a pull request with detailed descriptions.



Acknowledgments
The dataset was inspired by OpenML or Kaggle competitions (replace with source).
Thanks to the contributors of Scikit-learn and other Python libraries for making machine learning accessible.
