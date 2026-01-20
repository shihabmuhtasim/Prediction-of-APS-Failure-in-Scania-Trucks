# 🚚 APS Failure Prediction – Scania Trucks

## Predictive Maintenance Using Machine Learning

---

## 📌 Project Overview

This project focuses on **predictive maintenance** by developing a machine learning–based system to predict **Air Pressure System (APS) failures** in Scania heavy-duty trucks. APS failures can lead to significant maintenance costs and operational downtime, making early and accurate detection critically important.

Using high-dimensional sensor data collected from truck subsystems, the project aims to distinguish **APS-related failures** from non-APS failures through data preprocessing, feature analysis, and supervised learning techniques. The work is based on a real-world–inspired industrial dataset and follows a complete data mining and machine learning pipeline.

---

## 🧠 Problem Statement

Modern trucks are equipped with hundreds of sensors that continuously generate diagnostic data. However, APS failures are **rare events** and are often buried within noisy, high-dimensional sensor readings. The challenge is to:

- Handle large-scale, imbalanced sensor datasets
- Identify informative features related to APS failures
- Build reliable classification models
- Minimize false positives while maintaining high detection accuracy

The objective of this project is to **predict whether a failure is caused by the Air Pressure System**, enabling proactive maintenance decisions.

---

## 📊 Dataset Description

- High-dimensional sensor dataset containing **hundreds of numerical features**
- Each instance corresponds to a truck event
- Binary target label:
  - **Positive class:** APS-related failure
  - **Negative class:** Failure unrelated to APS
- Dataset characteristics:
  - Missing values
  - Class imbalance
  - Sensor noise

---

## ⚙️ Methodology

The project follows a structured machine learning workflow:

### 1️⃣ Data Preprocessing
- Handling missing values using appropriate imputation strategies
- Feature cleaning and normalization
- Removing non-informative or highly correlated features

### 2️⃣ Exploratory Data Analysis
- Class distribution analysis
- Feature variance inspection
- Identification of dominant sensor patterns

### 3️⃣ Feature Engineering
- Dimensionality reduction where applicable
- Selection of relevant sensor features
- Preparation of data for model training

### 4️⃣ Model Development
- Supervised classification models trained to detect APS failures
- Comparison of multiple algorithms based on performance
- Focus on robustness under class imbalance

### 5️⃣ Model Evaluation
- Use of performance metrics such as:
  - Accuracy
  - Precision
  - Recall
  - Confusion matrix analysis
- Emphasis on reducing false alarms while detecting true APS failures

---

## 🧪 Results & Analysis

The trained models demonstrate the feasibility of using sensor-based machine learning for APS failure prediction. Experimental results show that appropriate preprocessing and feature selection significantly improve classification performance, even in the presence of noisy and imbalanced data.

The project highlights the importance of **data quality**, **model selection**, and **evaluation metrics** in predictive maintenance systems.

---

## ▶️ How to Run the Project

### Requirements
- Python 3.x
- Jupyter Notebook

### Main File
```
Project_main.ipynb
```

### Steps
1. Open the notebook using Jupyter
2. Ensure required Python libraries are installed
3. Run the notebook cells sequentially to reproduce preprocessing, training, and evaluation steps

---

## 📂 Project Structure

```
├── Project_main.ipynb      # Main Jupyter notebook
├── Project Report.pdf     # Detailed project report
├── README.md              # Project documentation
```

---

## 🛠️ Tools & Technologies

- **Language:** Python
- **Libraries:** NumPy, Pandas, scikit-learn, Matplotlib
- **Techniques:** Classification, feature engineering, imbalanced learning
- **Domain:** Predictive maintenance, industrial analytics

---

## 🎯 Key Takeaways

- Practical application of machine learning in industrial diagnostics
- Handling real-world sensor data challenges
- Building interpretable and effective failure prediction models
- End-to-end data mining pipeline implementation

---

**Author:** Mayisha Hossain Bhuiyan  
**Domain:** Machine Learning & Data Mining  

