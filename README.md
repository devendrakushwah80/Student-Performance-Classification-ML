# 🎓 Student Performance Classification using Machine Learning

## 📌 Project Overview
This project aims to predict a student’s **final academic grade** using demographic, academic, and behavioral features.  
A complete **machine learning classification pipeline** is built with proper preprocessing, model training, and evaluation.

The implementation strictly follows the steps performed in the notebook  
`Student_Performance_Classifier.ipynb`.

---

## 📂 Dataset Description
The dataset contains information related to students’ background and performance, including:

- Demographic details (age, gender, school type)
- Parental education
- Study habits and attendance
- Internet access and travel time
- Subject-wise scores (Math, Science, English)

### 🎯 Target Variable
- `final_grade` (Categorical)

### ❌ Feature Removed
- `overall_score`  
  Removed to prevent **data leakage**, as it is directly derived from subject scores.

---

## 🔧 Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧪 Methodology

### 1️⃣ Data Loading & Exploration
- Loaded dataset using Pandas
- Checked shape, missing values, and data types
- Identified categorical and numerical features

---

### 2️⃣ Data Preprocessing

#### 🔹 Categorical Features
- Encoded using `OneHotEncoder`

#### 🔹 Numerical Features
- Scaled using `StandardScaler`

#### 🔹 Preprocessing Pipeline
- Used `ColumnTransformer` to apply transformations efficiently
- Ensured clean and reproducible preprocessing

---

### 3️⃣ Train–Test Split
- Dataset split into training and testing sets
- Ensured unbiased model evaluation

---

### 4️⃣ Model Selection
- **RandomForestClassifier** was used

**Why Random Forest?**
- Handles non-linear patterns
- Robust to noise
- Performs well with mixed feature types

---

### 5️⃣ Model Evaluation
The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-score

---

## 📊 Results
- Strong classification performance
- Balanced predictions across grade categories
- Effective handling of categorical and numerical data
- No data leakage in the pipeline

---

## 📁 Project Structure
├── Student_Performance_Classifier.ipynb
├── Student_Performance.csv
├── README.md
├── requirements.txt


---

## 🚀 Key Learnings
- End-to-end ML pipeline construction
- Proper encoding and scaling
- Avoiding data leakage
- Interpreting classification metrics
- Using ensemble models for classification tasks

---

## 🔮 Future Scope
- Hyperparameter tuning
- Feature importance analysis
- Trying boosting-based classifiers
- Cross-validation

---

## 👨‍💻 Author
**Devendra Kushwah**  
Machine Learning | Data Science | Statistical Learning
