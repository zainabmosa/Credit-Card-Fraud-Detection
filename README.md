# 💳 Credit Card Fraud Detection

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.

The main goal is to build a classification model that can distinguish between **legitimate transactions** and **fraudulent transactions**. Since credit card fraud datasets are usually highly imbalanced, special attention is given to data preprocessing, class imbalance, model training, and evaluation.

## 🎯 Objectives

* Analyze credit card transaction data.
* Explore patterns and characteristics of fraudulent transactions.
* Clean and preprocess the dataset.
* Handle the class imbalance problem.
* Train and compare different Machine Learning models.
* Evaluate model performance using suitable classification metrics.
* Identify the best-performing model for fraud detection.

## 📊 Dataset

The project uses the **Credit Card Fraud Detection Dataset** available on Kaggle.

The dataset contains **284,807 transactions**, including **492 fraudulent transactions**, making it a highly imbalanced classification problem.

The main features include:

* `Time` – Time elapsed between transactions.
* `V1` to `V28` – PCA-transformed numerical features.
* `Amount` – Transaction amount.
* `Class` – Target variable:

  * `0` = Legitimate transaction
  * `1` = Fraudulent transaction

## 🔎 Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand:

* Distribution of legitimate and fraudulent transactions.
* Transaction amount patterns.
* Relationships between features.
* Correlations between variables.
* Differences between fraudulent and legitimate transactions.

Visualizations were used to better understand the data and identify important patterns.

## 🧹 Data Preprocessing

The preprocessing steps included:

1. Checking for missing values.
2. Checking for duplicate records.
3. Exploring the distribution of the target variable.
4. Scaling numerical features where required.
5. Splitting the dataset into training and testing sets.
6. Handling the class imbalance problem.

## ⚖️ Handling Class Imbalance

Fraudulent transactions represent only a very small percentage of the dataset.

Therefore, accuracy alone is not a reliable metric for this project. Techniques such as **SMOTE (Synthetic Minority Over-sampling Technique)** can be used to increase the representation of the minority class and help the model detect fraudulent transactions more effectively.

## 🤖 Machine Learning Models

Several classification models were trained and evaluated, including:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting

The models were compared based on their performance in detecting fraudulent transactions.

## 📈 Model Evaluation

The following evaluation metrics were considered:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **ROC AUC**
* **Confusion Matrix**

Special attention was given to **Recall**, because failing to identify a fraudulent transaction can have a significant impact in a real-world financial system.

## 🏆 Results

The models were compared to determine which approach provided the best balance between detecting fraud and minimizing false positives.

> **Note:** Replace the `—` values with the actual results from your project.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Imbalanced-learn
* Jupyter Notebook / Google Colab


## 💡 Key Findings

The project demonstrates that credit card fraud detection is a challenging classification problem because fraudulent transactions are extremely rare compared with legitimate transactions.

Therefore, relying only on accuracy can be misleading. Metrics such as **Precision, Recall, and F1-Score** provide a better understanding of the model's ability to detect fraud.

## 🔮 Future Improvements

Future improvements could include:

* Testing additional Machine Learning models.
* Improving the handling of class imbalance.
* Deploying the best model as a web application.
* Adding real-time transaction prediction.
* Creating an interactive dashboard for fraud monitoring.

## 👩‍💻 Author

**Zainab Mohamed Moosa**
**Zahra Mohamed Abdulla**

University of Bahrain
Machine Learning Project
