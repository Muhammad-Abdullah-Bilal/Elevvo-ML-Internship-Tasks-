# Loan Approval Prediction using Machine Learning

## 📌 Project Overview
This project is part of my internship task focused on **binary classification**
and **imbalanced data handling**.
The objective is to predict whether a loan application
will be **approved or rejected** based on applicant financial
and demographic information.

## 🧠 Covered Topics
- Binary Classification
- Imbalanced Data Handling
- Feature Encoding
- SMOTE Oversampling
- Model Comparison
- Precision, Recall, and F1-Score Evaluation

## 🛠 Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- Seaborn

## 📂 Dataset
**Loan Approval Prediction Dataset** from :contentReference[oaicite:0]{index=0}  
The dataset contains loan, income, credit score,
and asset-related information for applicants.

## 🔄 Workflow
1. Load and explore dataset
2. Clean and standardize column names
3. Handle categorical features using encoding
4. Split data using stratified sampling
5. Apply feature scaling
6. Handle class imbalance using SMOTE
7. Train Logistic Regression and Decision Tree models
8. Evaluate models using precision, recall, and F1-score
9. Compare model performance

## 📊 Models Used
- Logistic Regression
- Decision Tree Classifier

## 📈 Evaluation Metrics
- Precision
- Recall
- F1-Score
- Accuracy
- Confusion Matrix

## 📊 Model Results

### Logistic Regression
- Accuracy: **93%**
- Precision (Approved Loans): **91%**
- Recall (Approved Loans): **91%**
- F1-Score (Approved Loans): **91%**

Logistic Regression provided **balanced and reliable performance**, making it
suitable for financial decision-making where generalization is important.

### Decision Tree
- Accuracy: **98%**
- Precision (Approved Loans): **97%**
- Recall (Approved Loans): **97%**
- F1-Score (Approved Loans): **97%**

The Decision Tree achieved **very high performance**, indicating strong learning
of patterns in the dataset. However, tree-based models may be prone to
**overfitting**, especially on structured financial data.

## 🏆 Final Model Selection
- **Decision Tree** performed best in terms of raw metrics.
- **Logistic Regression** is more interpretable and stable.

👉 For this task, **Decision Tree** is selected as the final model due to
its superior precision, recall, and F1-score.

## ▶ How to Run
1. Open Google Colab
2. Upload `loan_approval.csv`
3. Run all cells sequentially
4. Review classification reports and confusion matrix

## ✅ Conclusion
This project demonstrates an end-to-end pipeline for
**loan approval prediction on imbalanced data**.
By using **SMOTE** and focusing on **precision, recall, and F1-score**,
the models achieved strong performance.
The results show that machine learning can effectively
support financial decision-making while minimizing risk.