## 🩺 Diabetes Prediction using Ensemble Learning

This project is a Machine Learning-based predictive system that determines whether an individual is diabetic or not, based on health-related features. The solution explores multiple ML algorithms and finally combines Random Forest and XGBoost into an Ensemble Model with hyperparameter tuning to achieve higher accuracy and robustness.

## 📂 Dataset Description

The dataset is an extended version of the PIMA Indians Diabetes Dataset, containing 10,000+ patient records with the following attributes:

🔹 Features

gender (Male/Female/Other)
age (in years)
hypertension (0 = No, 1 = Yes)
heart_disease (0 = No, 1 = Yes)
smoking_history (categorical: never, current, former, etc.)
bmi (Body Mass Index)
HbA1c_level (Glycated Hemoglobin)
blood_glucose_level (mg/dL)
diabetes (Target: 0 = Non-diabetic, 1 = Diabetic)
This dataset provides a realistic foundation for training and evaluating predictive healthcare models.

## 🛠️ Project Features
✅ Data Preprocessing
Handled missing values and inconsistencies
Encoded categorical variables using Label Encoding
Applied feature scaling with StandardScaler

## 📊 Exploratory Data Analysis (EDA)
Visualized class imbalance
Correlation heatmap of features
Distribution analysis for BMI, HbA1c, and glucose levels

## 🤖 Machine Learning Models Implemented
Support Vector Machine (SVM)
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
XGBoost Classifier
Each model was trained individually and evaluated using accuracy, precision, recall, and F1-score.

## 🧠 Ensemble Learning
Built a Voting Classifier combining Random Forest and XGBoost
Used Soft Voting to aggregate probabilistic outputs
Reduced overfitting and improved generalization compared to single models

## 📈 Evaluation Metrics
Accuracy (train & test)
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
Performance comparison charts for all models

## 🧪 Libraries and Technologies Used

Python
NumPy – Numerical operations
Pandas – Data handling
Matplotlib & Seaborn – Visualization
Scikit-learn – Preprocessing, model building, and evaluation
XGBoost – Gradient boosting algorithm

## 🧰 Hyperparameter Tuning

Applied GridSearchCV for fine-tuning model parameters
Example: n_estimators, max_depth, min_samples_split for Random Forest
Example: learning_rate, n_estimators, max_depth for XGBoost
Improved model performance and ensured better generalization

---



---
