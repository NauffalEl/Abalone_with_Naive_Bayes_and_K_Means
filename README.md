# 🐚 Abalone Classification & Clustering Project

This project explores the **Abalone dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/1/abalone) using two powerful machine learning techniques:

1. **Classification Model** 🏷️ → Predicts abalone age using **Naive Bayes**
2. **Clustering Model** 🔍 → Groups abalones using **K-Means**

---

## 📌 Project Overview

**Why Abalone?**
The number of rings in an abalone’s shell determines its age, but measuring rings manually is tedious. This project automates the process using **machine learning**, providing an efficient and accurate alternative.

---

## 🚀 Implemented Models

### 🏷️ 1. Naive Bayes Classification
- **Purpose:** Predicts abalone age based on physical measurements.
- **Accuracy:** ⚡ 98%
- **Performance Metrics:**
  - **Precision:**
    - Class 0: 1.00
    - Class 1: 0.95
    - Class 2: 0.98
  - **Recall:**
    - Class 0: 0.95
    - Class 1: 1.00
    - Class 2: 1.00
  - **F1-Score:**
    - Class 0: 0.98
    - Class 1: 0.97
    - Class 2: 0.99
- **Confusion Matrix:**
  ```
  [[354  13   4]
   [  0 239   0]
   [  0   0 226]]
  ```

---

### 🔍 2. K-Means Clustering
- **Purpose:** Groups abalones into clusters based on physical attributes.
- **Optimal Clusters (k):** 🎯 2
- **Cluster Summary:**
  
  | Cluster | Mean Length | Mean Diameter | Mean Rings |
  |---------|-------------|--------------|------------|
  | **0** | 0.6128 | 0.4816 | 11.33 |
  | **1** | 0.4214 | 0.3227 | 8.32 |

---

## 📊 Dataset Details
The dataset consists of **physical measurements** of abalones, including:
- **Sex:** (M = Male, F = Female, I = Infant)
- **Length** 📏
- **Diameter** 📐
- **Height** 📏
- **Whole Weight** ⚖️
- **Shucked Weight** 🦪
- **Viscera Weight** 🏋️‍♂️
- **Shell Weight** 🏠
- **Rings** (target variable for age prediction)

---

## 🛠️ Prerequisites
Make sure you have the following installed:
- Python **3.8+** 🐍
- Jupyter Notebook 📓
- pip (Python package manager) 🔧

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone git@github.com:fazza-abiyyu/Classification-Models-for-Abalone-using-Naive-Bayes-and-K-Means.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Classification-Models-for-Abalone-using-Naive-Bayes-and-K-Means
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Abalone_dengan_Naive_Bayes_dan_K_Means.ipynb
   ```

---

## 🎯 Key Takeaways
✅ **Naive Bayes** is highly effective for classification with structured datasets.  
✅ **K-Means** provides meaningful clustering insights based on abalone features.  
✅ Automating age estimation can enhance efficiency in marine biology research.  

---

🚀 **Let’s dive into machine learning and explore the world of abalones together!** 🐚

