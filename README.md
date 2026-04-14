#  DDoS Attack Detection using Machine Learning!

## 📌 Overview

This project focuses on detecting **Distributed Denial of Service (DDoS) attacks** using machine learning techniques.
By analyzing network traffic data, the model classifies whether the traffic is **normal or malicious (attack)**.

The goal is to build a **reliable, scalable, and data-driven system** that can assist in early detection of Cyber threats.

---

## 🎯 Problem Statement

DDoS attacks overwhelm systems with massive traffic, making services unavailable to legitimate users.
Traditional rule-based systems fail to detect modern attack patterns.

👉 This project uses **machine learning** to automatically learn and detect such patterns.

--

## 🧠 Approach

We implemented a complete ML pipeline:

1. Data Loading (ARFF dataset)
2. Data Sampling (for efficiency)
3. Feature Selection (important network attributes)
4. Data Preprocessing

   * Encoding categorical features
   * Scaling numerical features
5. Target Transformation (Binary Classification)
6. Train-Test Split (Stratified)
7. Model Training
8. Model Evaluation
9. Model Comparison

---

## 🏗️ Architecture

```
Raw Dataset (ARFF)
        ↓
Data Sampling
        ↓
Feature Selection
        ↓
Data Preprocessing
 (Encoding + Scaling)
        ↓
Train-Test Split
        ↓
Model Training
 (Logistic Regression | Random Forest | SVM)
        ↓
Model Evaluation
 (Accuracy, Precision, Recall, F1)
        ↓
Best Model Selection
        ↓
DDoS Attack Detection
```

---

## 📊 Features Used

* PKT_SIZE
* PKT_RATE
* BYTE_RATE
* NUMBER_OF_PKT
* PKT_DELAY_NODE
* PKT_TYPE

---

## 🤖 Models Implemented

* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📊 Visualizations

* Target Distribution
* Feature Correlation Heatmap
* Confusion Matrix
* Model Performance Comparison

---

## 🧪 Key Observations

* Random Forest provided strong and balanced performance
* SVM performed well after feature scaling
* Logistic Regression worked as a baseline model
* Recall is crucial for detecting attacks (avoiding false negatives)

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/ddos-detection-ml.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook / script

```bash
python main.py
```

---

## 📌 Future Work

* Extend to **multiclass classification** (attack type detection)
* Real-time traffic monitoring system
* Integration with network security tools
* Deep learning-based detection

---

## 💡 Conclusion

This project demonstrates how machine learning can effectively detect DDoS attacks by learning patterns from network traffic data.
It highlights the importance of preprocessing, feature selection, and evaluation metrics in building a robust detection system.

---

## ⭐ If you found this useful, consider giving a star!
