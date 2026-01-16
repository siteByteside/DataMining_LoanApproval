# Predictive Model for Loan Approval Project

This repository contains a comprehensive data science project focused on predicting loan approval outcomes. The project was 

developed as a final assessment for my Data Mining & Visualization course, demonstrating a full machine learning pipeline from 

raw data to model evaluation.


## 💡 `Project Overview`

The primary goal of this project is to automate the loan eligibility process based on customer details provided during the online 

application process. This is a classic classification problem with significant implications for financial risk management.


## 📌 `Key Features of the Analysis`:

* **Handling Class Imbalance**: Used `RandomOverSampler` to address the minority class, ensuring the model is not biased towards one outcome.
* 
* **Statistical Exploration** : Performed `Chi-Square Tests` to determine associations between categorical features (e.g., Gender, Education) and Loan Status.
* 
* **Model Comparison**        : Evaluated multiple algorithms, including **Decision Trees**, **Random Forest**, and **Multinomial Naive Bayes**.
* 
* **Optimization**            : Conducted hyperparameter tuning using **GridSearchCV** to maximize model performance.
* 
* **Model Interpretation**    : Analyzed **Feature Importance** to understand which factors (e.g., Credit History, Applicant Income) most heavily influence loan approval.

## 📊 `Dataset`

The dataset includes applicant profiles such as:

* **Demographics**: Gender, Marital Status, Education, Dependents.

* **Financials**: Applicant & Co-applicant Income, Loan Amount, Loan Term.

* **Credit History**: A crucial record of past credit performance.

* **Target**: `Loan_Status` (Approved/Y or Rejected/N).


## 🧾 `Results`

After tuning, the Random Forest model provided the most balanced performance across Accuracy, Precision, and Recall. The analysis 

highlighted Credit History as the most significant predictor of loan eligibility.

## 🔧 `Tools Used`

* **Python Libraries**: `pandas`, `numpy`, `scikit-learn`, `imbalanced-learn`, `scipy`, `matplotlib`, `seaborn`

* **Environment**: Jupyter Notebook



