# 🩺 Diabetes Prediction using Ensemble Learning (Voting Classifier)

This project is a **Machine Learning-based predictive model** that determines whether an individual is diabetic or not, based on their health-related features. The project incorporates multiple ML algorithms including **SVM**, **Random Forest**, **Decision Tree**, and **KNN**, and combines their outputs using a **Voting Classifier (Soft Voting)** for enhanced accuracy and generalization.

---

## 📂 Dataset Description

The dataset used is a modified and extended version of the **PIMA Indians Diabetes Dataset**, consisting of **10,000+ patient records** with the following attributes:

### 🔹 Features:

- `gender` (Male/Female/Other)
- `age` (in years)
- `hypertension` (0: No, 1: Yes)
- `heart_disease` (0: No, 1: Yes)
- `smoking_history` (categorical: never, current, former, etc.)
- `bmi` (Body Mass Index)
- `HbA1c_level` (Glycated Hemoglobin)
- `blood_glucose_level` (random glucose reading in mg/dL)
- `diabetes` (Target: 0 = Non-diabetic, 1 = Diabetic)

This dataset provides a realistic base for training and testing a robust classification model.

---

## 🛠️ Project Features

### ✅ Data Preprocessing
- Handled missing values and inconsistencies
- Converted categorical data using Label Encoding
- Feature scaling applied using `StandardScaler`

### 📊 Exploratory Data Analysis (EDA)
- Class distribution and imbalance visualization
- Heatmap showing correlations between features
- Distribution plots for numeric attributes (e.g., BMI, glucose level)

### 🤖 Machine Learning Models Implemented
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **Decision Tree Classifier**
- **K-Nearest Neighbors (KNN)**

Each model is trained individually and evaluated based on accuracy and classification metrics.

### 🧠 Ensemble Learning: Voting Classifier
- A **Soft Voting Classifier** is built using the top-performing models
- Combines probabilistic predictions from multiple models to output the final prediction
- Enhances performance by reducing overfitting and bias

### 📈 Evaluation Metrics
- Accuracy (training and testing)
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- Visual comparison of model performances

---

## 🧪 Libraries and Technologies Used

- **Python**
- **NumPy** – For numerical operations
- **Pandas** – For data manipulation and handling
- **Matplotlib & Seaborn** – For visualization
- **Scikit-learn** – For model building, preprocessing, tuning, and evaluation
  
---

## 🧰 Hyperparameter Tuning

- `GridSearchCV` is used for optimizing model parameters:
  - Example: Tuning `n_neighbors` for KNN, `max_depth` for Decision Tree, etc.
- Helps in improving model performance and generalization

---
