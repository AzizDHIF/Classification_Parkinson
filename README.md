
---

# 🧠 Parkinson Disease Classification & Clustering

This repository presents a data science project focused on **Parkinson’s disease detection and analysis** using machine learning techniques.

---

## 🎯 Project Objective

Parkinson’s disease is a chronic neurodegenerative disorder that primarily affects the motor system, leading to:

* Tremors
* Muscle rigidity
* Postural instability
* Slowness of movement

Early diagnosis is crucial to improve patients’ quality of life and slow disease progression.

👉 The goal of this project is to develop an **AI-based decision support system** for:

1. **Binary classification** → Predict whether a patient has Parkinson’s disease
2. **Unsupervised analysis** → Identify disease severity levels using clustering

---

## 🧠 Methodology

The project is divided into two main parts:

---

### 🔹 1. Supervised Learning — Disease Classification

* **Task:** Binary classification (0 = Healthy, 1 = Parkinson’s)

* **Input:** Biomedical features extracted from patients

* **Approach:**

  * Data preprocessing and cleaning
  * Feature selection
  * Training multiple classification models

* **Goal:** Accurately predict the presence of Parkinson’s disease

---

### 🔹 2. Unsupervised Learning — Severity Analysis

* **Task:** Clustering patients based on similarities

* **Approach:**

  * Application of clustering algorithms (e.g., K-Means, etc.)
  * Grouping patients into clusters representing potential severity levels

* **Goal:**

  * Identify **patient profiles**
  * Estimate **disease progression stages**

---

## ⚙️ Techniques Used

* Data preprocessing and normalization
* Supervised learning models (classification)
* Unsupervised learning (clustering)
* Model evaluation and comparison

---

## 📁 Repository Structure

* **`ClassificationParkinson.ipynb`** — Main notebook containing:

  * Data preprocessing
  * Classification models
  * Clustering analysis
  * Results and visualizations

* **`RAPPORT.pdf`** — Detailed report including:

  * Methodology
  * Experimental results
  * Interpretation and discussion

* **`README.md`** — Project documentation

---

## 📊 Results

* Successful implementation of a **binary classification system** for Parkinson detection
* Identification of **patient clusters** reflecting potential severity levels
* Insights into patterns within biomedical data

👉 Full analysis and results are available in **`RAPPORT.pdf`**

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* Libraries:

  * `pandas`
  * `numpy`
  * `scikit-learn`
  * `matplotlib` / `seaborn`

---

## 🚀 Future Improvements

* Use advanced models (XGBoost, LightGBM, deep learning)
* Improve feature engineering on biomedical signals
* Validate results on larger and more diverse datasets
* Integrate explainability tools (SHAP, LIME) for medical interpretation

---

## 📌 Conclusion

This project demonstrates the application of **machine learning in healthcare**, combining classification and clustering techniques to assist in the **early diagnosis and analysis of Parkinson’s disease**.

---

💡 *This type of project is highly relevant for AI in healthcare, showcasing both technical skills and real-world impact.*

---


