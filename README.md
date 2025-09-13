# 🔧 Predictive Maintenance: Machine Failure Prediction

This project implements a **Predictive Maintenance Machine Learning pipeline** using the [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/ml/datasets/AI4I+2020+Predictive+Maintenance+Dataset).  
The goal is to **predict machine failures** and classify potential risks, enabling proactive maintenance decisions.

---

## 📌 Features

- **Data Exploration & Cleaning**
  - Loads dataset, checks for missing values, and provides descriptive statistics.
- **Feature Engineering**
  - Temperature difference
  - Power calculation (Torque × RPM)
  - Overstrain metric
  - Tool wear risk zones
  - Speed categories
  - Efficiency ratio
- **Visualization**
  - Failure distribution
  - Feature correlations
  - Boxplots & histograms
  - ROC, PR curves, confusion matrix
- **Model Training**
  - Random Forest
  - Gradient Boosting
  - Logistic Regression
  - SVM
  - Handles class imbalance with **SMOTE**
- **Evaluation**
  - Accuracy, F1, ROC-AUC
  - Cross-validation scores
  - Precision-Recall curves
- **Prediction**
  - Accepts new input data and predicts machine failure probability with risk level.

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/predictive-maintenance.git
cd predictive-maintenance
pip install -r requirements.txt
