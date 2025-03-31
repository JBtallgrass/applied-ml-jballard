# Wine Dataset - Machine Learning Analysis

## 📌 Overview

This project explores the **Wine Dataset** using **Random Forest Classification** and various machine learning techniques. The goal is to analyze the dataset, preprocess the data, train a classification model, tune hyperparameters, and evaluate model performance. Additionally, we perform feature importance analysis and visualize decision boundaries.

## 📂 Dataset Information

The **Wine dataset** consists of chemical properties of wines and their corresponding class labels. It is commonly used for classification tasks in machine learning.

### **Features (X)**

- `alcohol`
- `malic_acid`
- `color_intensity`
- `total_phenols`
- `flavanoids`

### **Target Variable (y)**

- `class` (0, 1, 2) - representing different types of wine

## 🚀 Project Workflow

### **1️⃣ Data Preprocessing**

- Load the dataset using `sklearn.datasets.load_wine()`

- Convert it into a Pandas DataFrame

- Handle missing values (if any)

- Perform **stratified splitting** for balanced class distribution

### **2️⃣ Exploratory Data Analysis (EDA)**

- Visualizing feature distributions using histograms

- Scatter matrix plots to observe feature relationships

- Checking class distribution before and after stratified splitting

### **3️⃣ Model Training & Evaluation**

- Use **Random Forest Classifier** as the primary model

- Train the model on the **training set**

- Make predictions on the **test set**

- Evaluate performance using:
  - **Accuracy Score**
  - **Classification Report** (Precision, Recall, F1-score)

### **4️⃣ Hyperparameter Tuning (Grid Search)**

- Optimize the model by tuning:

  - `n_estimators`: Number of trees
  - `max_depth`: Maximum depth of trees
  - `min_samples_split`: Minimum samples per split
  - `min_samples_leaf`: Minimum samples per leaf
- Use `GridSearchCV` for hyperparameter tuning

### **5️⃣ Feature Importance Analysis**

- Identify which features contribute the most to classification
- Visualize feature importance using bar plots

### **6️⃣ Decision Boundary Visualization**

- Reduce dimensionality using **PCA (Principal Component Analysis)**
- Plot 2D representations of the dataset
- Visualize class separation in feature space

## 📊 Results

- **Baseline Random Forest Model Accuracy**: ~XX%
- **Optimized Random Forest Model Accuracy**: ~XX%
- **Feature Importance Ranking:**
  - 1️⃣ `feature_x`
  - 2️⃣ `feature_y`
  - 3️⃣ `feature_z`

## 🛠️ Dependencies

Ensure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🏁 Running the Project

```python
# Load and preprocess the dataset
python wine_analysis.py
```

## 🎯 Next Steps

- Experiment with other classification models like **XGBoost**

- Perform **cross-validation** to ensure robust evaluation

- Expand feature engineering for better insights

---

✅ **Author**: Jason A. Ballard]  
📅 **Date**: March 2025

