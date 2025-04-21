# Heart-Disease-Prediction using ML Concepts and data visualization
This project focuses on predicting the presence of heart disease in patients using a combination of exploratory data analysis (EDA), data visualization, and machine learning algorithms. It is built using Python and Jupyter Notebook, and aims to extract insights from medical data and build predictive models that can assist in early diagnosis.

📊 Dataset Description
We use the Cleveland Heart Disease dataset from the UCI Machine Learning Repository, which includes 303 patient records and 14 attributes, such as:

age: Age of the patient

sex: Gender (1 = male, 0 = female)

cp: Chest pain type

trestbps: Resting blood pressure

chol: Cholesterol level

thalach: Max heart rate achieved

oldpeak: ST depression caused by exercise

exang: Exercise-induced angina

ca, thal: Blood flow-related features

target: Heart disease status (1 = disease, 0 = no disease)

🧪 Project Objectives
Perform exploratory data analysis (EDA) to understand feature distributions and relationships.

Use visualizations (heatmaps, bar plots, pairplots, boxplots) to identify patterns and correlations.

Preprocess the data (null values, encoding, feature scaling).

Build and compare multiple ML models:

Logistic Regression

Random Forest

K-Nearest Neighbors

Support Vector Machine (SVM)

Decision Tree

📈 Visualizations Used
Correlation Heatmap – To find which features are highly related to heart disease

Countplots – To see distributions like gender, chest pain, target labels

Boxplots – To detect outliers in age, cholesterol, and resting BP

Histograms & KDE plots – To explore numerical features

Pairplots – To see pairwise relationships in the data

These help in identifying key patterns that are important for prediction.

🧠 ML Workflow
Data Cleaning – Handle missing values, encode categorical variables

Feature Scaling – Normalize features for better model performance

Model Training – Use scikit-learn to train different models

Model Evaluation – Evaluate using accuracy, confusion matrix, precision, recall, F1 score

Feature Importance – Find which features contribute most to predictions

✅ Key Results
Achieved accuracy between 85–90% with Logistic Regression and Random Forest.

Features like chest pain type, max heart rate, and ST depression were most influential.

Visualizations helped uncover the strong link between certain features and the presence of heart disease.

🛠️ Technologies Used
Python

Jupyter Notebook

pandas, NumPy

seaborn, matplotlib

scikit-learn
