# 🤖 AI/ML Engineering Internship Tasks
**DevelopersHub Corporation — AI/ML Engineering Intern**

This repository contains completed tasks from the AI/ML Engineering Internship program at DevelopersHub Corporation.

---

## 📁 Task 1: Exploring and Visualizing a Simple Dataset

### 🎯 Objective
Explore and visualize a well-known dataset to understand data distributions, feature relationships, and apply basic machine learning classification.

### 📊 Dataset Used
- **Iris Dataset** (from `sklearn.datasets`)
- 150 samples, 4 features: sepal length, sepal width, petal length, petal width
- 3 target classes: Setosa, Versicolor, Virginica

### 🧠 Models Applied
- **Logistic Regression** (for classification)
- **PCA (Principal Component Analysis)** for dimensionality reduction and visualization

### 📈 Key Results & Findings
- Visualized feature distributions using histograms and KDE plots
- Created scatter plots using PCA-reduced components to show class separation
- Box plots revealed significant differences in petal features across species
- Logistic Regression successfully classified Iris species with high accuracy

---

## 📁 Task 3: Heart Disease Prediction

### 🎯 Objective
Build a machine learning model to predict whether a patient has heart disease based on clinical features, enabling early diagnosis and medical decision support.

### 📊 Dataset Used
- **Heart Disease Prediction Dataset** (CSV)
- Features include: Age, Max HR (Heart Rate), cholesterol levels, chest pain type, and more
- Target: `Heart Disease` — Presence (1) or Absence (0)

### 🧠 Models Applied
- **Logistic Regression**
- **Random Forest Classifier**
- Data preprocessing: Label Encoding, StandardScaler

### 📈 Key Results & Findings
- Age distribution and Max HR were key indicators of heart disease
- Correlation heatmap revealed strong relationships between clinical features and the target
- Random Forest outperformed Logistic Regression in classification accuracy
- Classification report and confusion matrix used to evaluate model performance

---

## 📁 Task 6: House Price Prediction

### 🎯 Objective
Predict house prices based on real-estate property features using regression techniques, useful for buyers, sellers, and real-estate analysts.

### 📊 Dataset Used
- **Housing Dataset** (CSV)
- Features: Area, Bedrooms, Bathrooms, Stories, Parking, Main Road access, Guest Room, Basement, Hot Water Heating, Air Conditioning, Preferred Area, Furnishing Status
- Target: `Price`

### 🧠 Models Applied
- **Linear Regression**
- Preprocessing: Label Encoding for binary columns (Yes/No → 1/0), One-Hot Encoding for `furnishingstatus`
- Feature scaling with **StandardScaler**

### 📈 Key Results & Findings
- Area and number of bathrooms showed the strongest positive correlation with price
- Correlation heatmap revealed multicollinearity among some features
- Linear Regression model evaluated using MSE (Mean Squared Error) and R² Score
- EDA revealed right-skewed price distribution, suggesting presence of luxury properties

---

## 🛠️ Technologies Used
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (sklearn)
- Google Colab / Jupyter Notebook

