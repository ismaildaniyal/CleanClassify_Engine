
## 🧠 Project Overview

**SmartClassifier_EDAtoModel** is a complete machine learning pipeline built for a classification problem. It showcases a full workflow from **Exploratory Data Analysis (EDA)** to **model evaluation**, covering data cleaning, visualization, feature engineering, model tuning, and comparison.

---

## 🚀 Key Highlights

### 🔍 Part 1: Exploratory Data Analysis (EDA)
- Handled missing values and outliers using IQR and visualization
- Used boxplots, histograms, and correlation matrices to understand feature behavior
- Compared outlier detection methods and visualized results across target classes

### 🧼 Part 2: Preprocessing & Dataset Splitting
- Encoded categorical variables using label and one-hot encoding
- Compared Min-Max Scaling vs Z-score Normalization on 3 models
- Selected features using correlation-based techniques
- Implemented optimal dataset splitting strategies

### 🤖 Part 3: Model Implementation
- **K-Nearest Neighbors (KNN):** Tuned `k` and tested multiple distance metrics
- **Support Vector Machine (SVM):** Applied various kernels and regularization
- **Decision Tree:** Tuned hyperparameters and visualized trees
- **Logistic Regression:** Evaluated with L1 and L2 regularization

### 📊 Part 4: Model Evaluation & Comparison
- Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Evaluated on imbalanced data
- Compared training time and prediction time for efficiency

---

## 📈 Visualizations Used
- Boxplots
- Pairplots / Scatter Matrix
- Heatmaps
- Class distribution bar plots

---

## 🧪 How to Run

1. Open the Jupyter notebook:  
   `21F-9345.ipynb`
2. Make sure the following libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
