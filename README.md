Heart Disease Prediction – Machine Learning Project
s
🎯 Objective

The objective of this project is to predict the presence of heart disease in patients using medical features. Two machine learning models — Logistic Regression and Decision Tree Classifier — are trained and evaluated to compare their performance.

📊 Dataset Used

File Name: heart.csv

Target Column: HeartDisease

1 → Presence of heart disease

0 → No heart disease

Features: Medical and lifestyle attributes such as age, sex, chest pain type, ECG results, exercise angina, etc.

⚠️ Ensure heart.csv is placed in the same folder before running the code.

🛠️ Libraries Used

pandas – data loading and manipulation

seaborn – visualizations and heatmaps

matplotlib – plotting graphs

scikit-learn – machine learning models and evaluation

🔍 Steps Performed
1️⃣ Load Dataset

Dataset is loaded using pandas.read_csv

First 5 rows are displayed

Missing values are checked

2️⃣ Feature & Target Selection

Features (X): All columns except HeartDisease

Target (y): HeartDisease

3️⃣ Handle Categorical Variables

Categorical features are converted into numeric form using one-hot encoding:

Sex

ChestPainType

RestingECG

ExerciseAngina

ST_Slope

This ensures compatibility with machine learning models.

4️⃣ Train–Test Split

Dataset is split into:

80% training data

20% testing data

random_state=42 is used for reproducibility

5️⃣ Feature Scaling

StandardScaler is applied

Required for Logistic Regression to improve performance

🤖 Models Implemented
🔹 Logistic Regression

Trained on scaled features

Predictions made on test data

Evaluated using:

Accuracy

Classification Report

Confusion Matrix

ROC Curve

Feature Importance

🔹 Decision Tree Classifier

Trained on the same dataset

Performance compared using:

Accuracy

Classification Report

📈 Model Evaluation & Visualization
✅ Accuracy Score

Shows how many predictions were correct.

📊 Classification Report

Includes:

Precision

Recall

F1-score

Support

🔲 Confusion Matrix

Visualizes True Positives, True Negatives, False Positives, and False Negatives

Displayed using a Seaborn heatmap

📉 ROC Curve

Shows model’s ability to distinguish between classes

AUC (Area Under Curve) indicates overall performance

⭐ Feature Importance

Based on Logistic Regression coefficients

Displays which medical features most influence heart disease prediction

📌 Key Insights

Logistic Regression performs well for binary classification problems

Decision Tree provides an alternative non-linear approach

Feature scaling significantly improves Logistic Regression results

ROC curve and AUC give a strong measure of model reliability

Feature importance helps understand medical risk factors

✅ Conclusion

This project demonstrates a complete binary classification pipeline, including preprocessing, model training, evaluation, and visualization. It provides a strong foundation for healthcare-related machine learning applications.