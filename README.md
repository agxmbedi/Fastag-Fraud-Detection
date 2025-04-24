
# 🚗 FASTag Fraud Detection 🕵️‍♂️

Welcome to the **FASTag Fraud Detection** project – a deep dive into the murky world of digital toll payments in India. Using real-world transaction data, this project reveals patterns, exposes vulnerabilities, and builds a model to detect potential fraud with precision.

## 🔍 Project Overview

With the rise of digital toll collection via FASTag, so have fraudulent activities. This project aims to:

- Explore and clean FASTag transaction data.
- Uncover patterns behind legitimate vs. suspicious activity.
- Train machine learning models to classify potential fraud.

## 📌 Key Features

- 🧼 **Data Cleaning**: Handled null values, confirmed data types, and ensured no duplicate entries.
- 📊 **Exploratory Data Analysis (EDA)**:
  - Identified nulls in FASTag ID (549 missing).
  - Analyzed transaction types, vehicle categories, and toll booth behavior.
- 📈 **Visual Insights**:
  - Visualized transaction amounts, vehicle speeds, and payment discrepancies.
  - Correlation heatmaps helped identify strong predictors of fraud.
- 🧠 **Feature Engineering**:
  - State-wise fraud mapping (KA had highest).
  - Derived critical features like speed, amount paid, and booth location.
- 🤖 **Modeling**:
  - Logistic Regression trained on extracted features.
  - Insights on accuracy and confusion matrix to evaluate performance.

## 🔑 Key Findings

- 🏍️ **Motorcycles were not involved** in any fraud—clean vehicle category.
- 🛣️ Toll booths **104, 105, and 106** showed zero frauds, while **101, 102, 103** had mixed activity.
- ⚠️ **Expressways** had a notably higher fraud percentage than regular roads.
- 🧾 When **Transaction Amount ≠ Amount Paid**, it was a strong fraud indicator.
- 🌍 **Karnataka (KA)** recorded the **highest fraud instances** by state.

## 📁 Dataset & Tools

- Dataset: Provided via Kaggle (confidentiality maintained).
- Tools used: **Pandas, Matplotlib, Seaborn, Scikit-learn**.

## 🧠 What's Next?

- Improve classification using advanced ML models (Random Forest, XGBoost).
- Add real-time anomaly detection.
- Integrate vehicle entry/exit time for deeper behavioral analysis.

## 🚀 Let’s Connect

If you're passionate about data science, cybersecurity, or fintech, let’s talk! Connect with me on [LinkedIn](https://www.linkedin.com).
