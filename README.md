# Bank Marketing – Comparing Classification Models

## Project Overview
This project compares multiple classification algorithms to predict whether a bank client will subscribe to a term deposit product based on demographic and campaign data.

## Business Problem
Accurate prediction allows the bank to reduce unnecessary calls and better allocate marketing resources.

## Dataset
The dataset comes from a Portuguese banking institution and includes demographic, social, and marketing attributes.

## Data Understanding and EDA
The dataset exhibits a clear class imbalance, with the majority of clients not subscribing to the term deposit.
This reflects real-world telemarketing conditions and motivates the use of evaluation metrics beyond accuracy.
Exploratory analysis shows meaningful relationships between campaign characteristics and subscription behavior.

## Models Compared
- Logistic Regression
- k-Nearest Neighbors
- Decision Tree
- Support Vector Machine

## Evaluation Metric
ROC-AUC was used to evaluate model performance due to class imbalance.

## Key Results
Logistic Regression achieved the highest ROC-AUC (~0.93), followed by SVM, Decision Tree, and k-NN.

## Key Findings
- Logistic Regression demonstrated the strongest discriminatory power.
- Simpler, interpretable models performed competitively against more complex algorithms.
- Model transparency is especially valuable in regulated financial environments.

## Notebook
View the full analysis here:  
https://github.com/Felipe-Ulloa-CA/bank-marketing-comparing-classifiers/blob/main/bank_marketing_comparing_classifiers.ipynb

## Business Recommendation
Based on performance and interpretability, Logistic Regression is recommended for deployment.

## Repository Structure
- bank_marketing_comparing_classifiers.ipynb — Full analysis notebook
- bank-additional.csv — Dataset
- README.md — Project overview

## Author
**Felipe Eduardo Ulloa Orellana**  
UC Berkeley Professional Certificate in Machine Learning & AI  
Silicon Valley, California

### License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
© 2025 **Felipe E. Ulloa**
