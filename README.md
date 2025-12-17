# 🧠 EEG Signal Classification using Machine Learning

An end-to-end machine learning project that classifies **EEG (Electroencephalogram) signals** by applying data preprocessing, feature extraction, and supervised learning techniques. This project demonstrates how machine learning can be effectively used in **biomedical signal analysis** and **healthcare analytics**.

---

## 📌 Project Overview

Electroencephalography (EEG) records electrical activity of the brain and is widely used in applications such as **brain–computer interfaces (BCI)**, **neurological disorder detection**, and **cognitive state analysis**.

In this project, EEG data is transformed into meaningful numerical features and used to train machine learning models for classification tasks.

---

## ⚙️ Key Features

- End-to-end EEG data processing pipeline  
- Feature extraction from raw EEG signals  
- Supervised machine learning model training  
- Model evaluation using standard performance metrics  
- Fully implemented in Python using Jupyter Notebook  

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-102230?logo=scikit-learn&logoColor=F7931E)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

---

## 🔄 Machine Learning Workflow

### 1️⃣ Data Loading & Exploration
- Loaded EEG dataset
- Analyzed structure, features, and target labels

### 2️⃣ Data Preprocessing
- Cleaned noisy or missing values  
- Normalized and scaled EEG features  
- Prepared data for model training  

### 3️⃣ Feature Extraction
Extracted statistical features from EEG signals such as:
- Mean  
- Standard deviation  
- Variance  
- Other signal-based characteristics  

### 4️⃣ Model Training
- Trained supervised machine learning classifiers  
- Split data into training and testing sets  

### 5️⃣ Model Evaluation
Evaluated model performance using:
- Accuracy score  
- Confusion matrix  
- Classification report  

---
## 📊 Model Performance Summary

| Model               | Accuracy | Class 1 Recall | Class 1 F1 | Weighted F1 |
|--------------------|----------|----------------|------------|-------------|
| Logistic Regression | 78%      | 15%            | 0.27       | 0.71        |
| SVM                | 76%      | 8%             | 0.14       | 0.67        |
| KNN                | 86%      | 46%            | 0.63       | 0.84        |
| Random Forest      | 92%      | 69%            | 0.82       | 0.91        |

--- 

## 📊 Results

The evaluated machine learning models showed varying performance in EEG signal classification, highlighting the importance of model selection for imbalanced biomedical datasets.

Among all models, **Random Forest achieved the best performance**, with an **accuracy of 92%** and a **weighted F1-score of 0.91**, demonstrating strong overall classification capability. It also showed improved detection of the minority class with a **recall of 69%** for Class 1.

The **K-Nearest Neighbors (KNN)** model achieved an **accuracy of 86%**, providing moderate performance but lower minority-class recall compared to Random Forest.

In contrast, **Logistic Regression (78% accuracy)** and **Support Vector Machine (76% accuracy)** struggled with minority-class identification, exhibiting recall values below **15%**, despite reasonable overall accuracy.

These results indicate that **ensemble-based approaches such as Random Forest are more effective for EEG signal classification**, particularly in class-imbalanced scenarios.

---

## 🧪 Use Cases

- Brain–Computer Interface (BCI) systems  
- EEG-based neurological research  
- Cognitive state and signal pattern analysis  
- Healthcare analytics using machine learning  

---

## ▶️ How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/SreeDharaniReddy/EEG-Classification.git
