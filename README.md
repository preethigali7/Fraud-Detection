# Fraud Detection using Machine Learning

## Project Overview

This project focuses on detecting fraudulent financial transactions using Machine Learning techniques. Fraud detection is a critical application in banking and financial systems where identifying suspicious activities helps reduce financial losses and improve transaction security.

The project analyzes transaction patterns and builds a classification model to distinguish between fraudulent and legitimate transactions.

---

## Dataset Information

The dataset contains anonymized financial transaction data.

### Features Include:

- Transaction Time

- Transaction Amount

- PCA-transformed transaction features (V1 to V28)

- Class Label

- 0 → Non-Fraud Transaction

- 1 → Fraudulent Transaction

---

## Technologies Used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Scikit-learn

- Jupyter Notebook

- Git & GitHub

---

## Project Workflow

1. Data Loading

2. Data Cleaning

3. Exploratory Data Analysis (EDA)

4. Fraud Distribution Analysis

5. Feature Scaling

6. Train-Test Split

7. Logistic Regression Model

8. Model Evaluation

9. Business Insights & Recommendations

---

## Exploratory Data Analysis

The project includes:

- Dataset structure analysis

- Statistical summary

- Missing value analysis

- Fraud distribution visualization

- Class imbalance analysis

---

## Fraud Distribution Analysis

The dataset is highly imbalanced, where legitimate transactions significantly outnumber fraudulent transactions.

This imbalance is a major challenge in fraud detection systems and requires careful evaluation using metrics such as:

- Precision

- Recall

- F1-score

instead of relying only on accuracy.

---

## Feature Scaling

The Amount feature was standardized using StandardScaler to improve model performance and ensure proper feature contribution.

---

## Machine Learning Model

### Logistic Regression

Logistic Regression was used as the primary classification model to detect fraudulent transactions.

The dataset was divided into:

- Training Set

- Testing Set

using train\_test\_split() from Scikit-learn.

---

## Model Evaluation

The model was evaluated using:

- Accuracy Score

- Confusion Matrix

- Classification Report

- Precision

- Recall

- F1-score

---

## Results

### Key Findings

- Fraudulent transactions represent only a very small percentage of the dataset.

- The machine learning model successfully identified fraudulent transaction patterns.

- Class imbalance significantly impacts fraud detection performance.

- Recall is an important evaluation metric because missing fraudulent transactions can be risky.

---

## Business Recommendations

- Implement real-time fraud monitoring systems.

- Continuously retrain fraud detection models using updated transaction data.

- Monitor high-risk transactions more aggressively.

- Use advanced machine learning models for improved fraud detection accuracy.

- Combine automated fraud detection systems with manual verification for suspicious transactions.

---

## Business Value

Fraud detection systems help financial institutions:

- Reduce financial losses

- Improve transaction security

- Detect suspicious behavior in real-time

- Improve customer trust

- Support secure digital payment systems

---

## Project Visualizations

The project includes:

- Fraud Distribution Countplot

- Fraud Percentage Pie Chart

- Confusion Matrix

- Classification Report

---

## Conclusion

This project successfully applied Machine Learning techniques to identify fraudulent financial transactions. The analysis demonstrated how predictive models can support fraud prevention systems and improve financial security using data-driven decision-making.

---

## Author

Preethi Gali

---

## GitHub Repository

https://github.com/preethigali7/Fraud-Detection

