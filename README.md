# 📧 Phishing Email Detection using Machine Learning

This project builds an end-to-end machine learning pipeline to detect phishing emails using multiple datasets, text preprocessing, TF-IDF vectorization, and Logistic Regression classifier.

---

## 📚 Table of Contents
- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Workflow](#workflow)
- [Installation and Setup](#installation-and-setup)
- [Project Structure](#project-structure)
- [Results](#results)
- [Future Work](#future-work)
- [Contact](#contact)

---
## 📥 Dataset Source

The phishing email datasets used in this project are publicly available on Figshare:

🔗 [Download Dataset (Seven Phishing Email Datasets)](https://figshare.com/articles/dataset/Seven_Phishing_Email_Datasets/25432108)

The combined dataset includes emails from multiple sources like CEAS, Enron, TREC, Nigerian fraud, and others.

## 📋 Project Description

The goal of this project is to detect phishing emails automatically using machine learning.  
The workflow involves loading and combining multiple phishing datasets, cleaning the email text, vectorizing using TF-IDF, training a Logistic Regression model, and evaluating using confusion matrix, precision-recall curve, and ROC curve.

---

## 🚀 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔥 Workflow

1. Load 7 different phishing datasets
2. Preprocess text (lowercase, remove URLs, numbers, punctuation)
3. Combine all datasets
4. Vectorize using TF-IDF (Top 5000 features)
5. Train-Test Split (80%-20%)
6. Train Logistic Regression
7. Evaluate using:
   - Confusion Matrix
   - Precision-Recall Curve
   - ROC Curve
8. Save trained model and vectorizer for future use

---

## ⚙️ Installation and Setup

Clone this repository:

```bash
git clone https://github.com/your-username/phishing-email-detection.git
cd phishing-email-detection
