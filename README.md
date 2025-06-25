# Social Assistance Program Predictive Analysis

This project focuses on predicting deserving recipients of a social assistance program using machine learning. Specifically, it compares the performance of three supervised learning algorithms: **Gaussian Naive Bayes**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machine (SVM)**, based on an annotated dataset.

## 📊 Objective

The goal of this study is to identify which algorithm performs best in accurately predicting eligible beneficiaries of a social assistance program. This is crucial for optimizing aid distribution and ensuring that resources reach the most deserving individuals.

## 🧠 Algorithms Compared

- **Gaussian Naive Bayes (GNB)**  
  Assumes features follow a normal distribution and applies Bayes’ Theorem for classification.

- **K-Nearest Neighbors (KNN)**  
  A distance-based classifier that assigns a class based on the majority vote of the `k` closest data points.

- **Support Vector Machine (SVM)**  
  Constructs a hyperplane in a high-dimensional space to separate different classes with maximum margin.

## 🧾 Dataset

- **Source**: Annotated dataset tailored for predicting eligibility for social assistance.
- **Features**: Includes socio-economic and demographic indicators (e.g., income level, employment status, household size).
- **Target**: Binary classification – Deserving (1) or Not Deserving (0).

## ⚙️ Methodology

1. Data Cleaning and Preprocessing
2. Splitting Dataset into Training and Testing Sets
3. Training the Models (GNB, KNN, SVM)
4. Model Evaluation (Accuracy, Precision, Recall, F1-Score)
5. Comparison and Analysis

## 📈 Results

Model performances are compared to determine the most effective algorithm in terms of:
- Predictive Accuracy
- Generalization on unseen data
- Computation efficiency

_Final evaluation results and discussion are available in the Data_visualization.ipynb section._


