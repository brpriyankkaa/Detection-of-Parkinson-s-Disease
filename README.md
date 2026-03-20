#  Parkinson’s Disease Detection using Machine Learning

> Leveraging voice-based biomarkers and machine learning to detect Parkinson’s disease with high accuracy.

---

## 📌 Overview

Parkinson’s disease is a progressive neurological disorder that affects movement and speech.  
This project explores how **machine learning models** can analyze voice-derived features to detect patterns associated with Parkinson’s disease.

By combining multiple datasets and applying advanced preprocessing techniques, this project demonstrates how data-driven approaches can assist in early detection.

---

## 🗂️ Datasets Used

- **Disease Classification (DC)**  
- **Multiple Sound Recording (MSR)**  
- **Telemonitoring (TE)**  

Each dataset provides unique voice-based features such as jitter, shimmer, and harmonic ratios.

---

## ⚙️ Tech Stack

-  Python  
-  Pandas, NumPy  
-  Scikit-learn  
-  PCA, LDA (Dimensionality Reduction)  
-  Matplotlib, Seaborn  

---

## 🧪 Methodology

### 1. Data Preprocessing
- Cleaned and standardized datasets  
- Handled inconsistencies across multiple sources  
- Selected overlapping features for compatibility  

### 2. Feature Engineering
- Identified highly correlated features  
- Applied **PCA** and **LDA** to reduce dimensionality  

### 3. Model Building
- Implemented **Neural Network (MLPClassifier)**  
- Experimented with multiple configurations  
- Applied feature scaling for stable training  

### 4. Dataset Fusion
- Combined MSR and TE datasets  
- Used **13 common acoustic features**  
- Increased training diversity  

---

## 🔍 Key Insights

- Voice features like **jitter and shimmer are highly correlated**  
- Dimensionality reduction significantly improves efficiency  
- Combining datasets improves generalization  
- Proper evaluation metrics are crucial in imbalanced datasets  

