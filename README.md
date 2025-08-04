# 🔐 Network Intrusion Detection System using Machine Learning

A Machine Learning-based Network Intrusion Detection System (NIDS) capable of identifying and classifying cyber-attacks like DoS, Probe, R2L, and U2R from normal network traffic. Built with Python and deployed on IBM Cloud Lite.

---

## 📌 Problem Statement

With increasing cyber threats, traditional rule-based systems often fail to detect sophisticated and evolving network intrusions. This project aims to develop a robust machine learning model to classify network traffic into normal and attack categories for proactive cybersecurity.

---

## 🎯 Objectives

- Detect and classify different types of network attacks using ML algorithms.
- Provide real-time alerts for early intrusion detection.
- Deploy the model using IBM Cloud Lite for scalability and accessibility.

---

## 📊 Dataset

- **Source:** [Kaggle - Network Intrusion Detection Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)
- **Features Used:** `duration`, `protocol_type`, `service`, `flag`, `src_bytes`, `dst_bytes`, and more.
- **Classes:** Normal, DoS, Probe, R2L, U2R

---

## 🛠️ Technologies Used

- Python 3.x  
- IBM Cloud Lite (Watson Studio & Deployment)
- Jupyter Notebook  
- Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  

---

## 🔍 System Architecture

1. **Data Preprocessing:**  
   - Handling missing values  
   - Encoding categorical features  
   - Normalization  

2. **Model Training:**  
   - Algorithms used: Random Forest, Decision Tree, SVM  
   - Train-test split: 80/20  
   - Evaluation: Accuracy, Precision, Recall, F1-score, Confusion Matrix  

3. **Deployment:**  
   - Model exported and deployed via IBM Watson Machine Learning  
   - API/GUI support for real-time intrusion prediction  
  
