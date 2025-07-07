# Decision Tree – Heart Disease Classification 🌳🫀

A hands-on case study using **decision trees** to classify patients based on heart disease risk using clinical data.

---

## 🎯 Problem Statement

Early detection of heart disease is crucial for timely treatment. This project builds a decision tree classifier to predict whether a patient has heart disease based on features like age, cholesterol, chest pain type, and more.

---

## 🗂 Dataset Overview

- **Filename**: `heart_v2.csv`
- **Target Variable**: `target`  
  - `0` → No Heart Disease  
  - `1` → Has Heart Disease
- **Features**: Age, sex, resting blood pressure, cholesterol, chest pain type, etc.

---

## 🧰 Tools & Libraries

- Python 3.x (Jupyter Notebook)
- pandas, NumPy — data handling
- matplotlib — data visualization
- scikit-learn — decision tree model, evaluation, and visualization

---

## 🚀 Workflow

1. **Data Exploration & Cleaning**  
   - Load dataset and inspect structure  
   - Check for missing values  
   - Brief exploratory analysis

2. **Model Building**  
   - Train-test split  
   - Train a decision tree classifier  
   - Visualize the tree using `plot_tree` from sklearn

3. **Model Evaluation**  
   - Predict on test set  
   - Evaluate with accuracy, precision, recall, and F1-score  
   - Display results in a summary table

---

## 📈 Key Learnings

- Decision trees are intuitive and interpretable for binary classification.
- Proper tree depth and parameter tuning are essential to prevent overfitting.
- Model performance can be significantly improved using techniques like GridSearchCV.

---

## 🗂 Project Structure

```
├── 2_Heart+Disease+Prediction.ipynb   # Jupyter notebook with full pipeline
├── heart_v2.csv                       # Dataset
└── README.md                          # Project overview (this file)
```

---

*Created by Shivansh – explore the code, tweak parameters, and improve the model performance!*
