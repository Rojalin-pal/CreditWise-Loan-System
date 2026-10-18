# 🏦 CreditWise Loan System

An end-to-end Machine Learning pipeline that predicts loan approval eligibility to minimize financial risk and automate credit assessment.

---

## 📌 Project Overview
CreditWise analyzes historical applicant profiles to predict whether a loan application should be approved or rejected. By evaluating credit history, income, education level, and financial obligations, the system assists lenders in making consistent, data-driven decisions.

## 🛠️ Key Pipeline Stages
- **Data Preprocessing & Imputation**: Handled missing values using `SimpleImputer` for numerical and categorical features.
- **Exploratory Data Analysis (EDA)**: Analyzed relationships between credit scores, income levels, and approval rates.
- **Feature Engineering & Encoding**: Categorical encoding with `LabelEncoder` and `OneHotEncoder`, followed by feature scaling with `StandardScaler`.
- **Model Development & Comparison**:
  - Logistic Regression
  - K-Nearest Neighbors (KNN, $k=13$)
  - Gaussian Naive Bayes
- **Evaluation**: Evaluated using Precision, Recall, F1-Score, and Accuracy. Gaussian Naive Bayes was identified as the optimal model to maximize precision and reduce non-performing loan approvals.

## 💻 Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib

## 📂 Project Structure