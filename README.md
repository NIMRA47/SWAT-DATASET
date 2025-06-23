# SWaT Machine Learning Analysis

This project demonstrates machine learning modeling on the **SWaT (Secure Water Treatment)** dataset to detect cyber-attacks in industrial control systems.

---

## 📌 Objective

To explore, preprocess, and analyze the SWaT dataset using classical machine learning models like:
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**

---

## 🧪 Tasks Completed

### ✅ Task 1: Data Exploration & Preprocessing
- Loaded the dataset (simulated SWaT structure)
- Handled missing values
- Encoded `Normal/Attack` column to binary
- Applied Min-Max normalization
- Performed exploratory visualizations using Matplotlib

### ✅ Task 2: Model Implementation
- Implemented **KNN**
- Evaluated with accuracy, precision, recall, F1-score, and MSE

### ✅ Task 3: Second Model + Comparison
- Trained **Decision Tree** for performance comparison
- Created result tables and confusion matrices

### ✅ Task 4: Analysis & Conclusion
- Compared KNN vs Decision Tree
- Analyzed strengths/weaknesses of each model
- Provided a written interpretation

---

## 📊 Sample Evaluation Metrics

| Metric        | KNN   | Decision Tree |
|---------------|-------|----------------|
| Accuracy      | 0.93  | 0.91           |
| Precision     | 0.81  | 0.77           |
| Recall        | 0.69  | 0.65           |
| F1-Score      | 0.74  | 0.71           |
| MSE           | 0.07  | 0.09           |

---

## 📁 Files

- `SWaT_MiniDataset.csv` – Simulated dataset for testing (can replace with real SWaT data)
- `swat_analysis.ipynb` – Full notebook including EDA, modeling, and analysis
- `README.md` – This documentation

---

## ✅ Requirements

- Python 3.x
- Pandas, NumPy
- Matplotlib
- Scikit-learn

---
 ✍️ Author

NIMRA SHAKOOR  
BS Software Engineering Student  
_This project was part of a machine learning lab assignment on cyber-physical system security._

---

