# Diabetes-Prediction-Machine-Learning-Project
# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

A simple end-to-end machine learning project that predicts whether a person has diabetes (binary classification) using a Support Vector Machine (SVM).  
The model is trained on diagnostic measurements and achieves **77.7% accuracy** on the test set.

---

## 📁 Dataset

- **File:** `diabetes.csv`  
- **Target column:** `Outcome`  
  - `1` = Diabetic  
  - `0` = Non-diabetic  
- **Feature columns:**
  - Pregnancies  
  - Glucose  
  - BloodPressure  
  - SkinThickness  
  - Insulin  
  - BMI  
  - DiabetesPedigreeFunction  
  - Age  

---

## 🧰 Tech Stack

- **Language:** Python  
- **Libraries:**  
  - `pandas` – data manipulation  
  - `numpy` – numerical operations  
  - `scikit-learn` – ML algorithms & evaluation (`StandardScaler`, `train_test_split`, `svm`, `accuracy_score`)  
- **Environment:** Jupyter Notebook  

---

## 🔄 Project Workflow

1. **Data Loading** – Load `diabetes.csv` into a pandas DataFrame.  
2. **Data Analysis** – Initial exploration (shape, NA values, summary).  
3. **Data Standardization** – Scale features with `StandardScaler`.  
4. **Train/Test Split** – 80/20 split with fixed random seed.  
5. **Model Training** – Train SVM classifier.  
6. **Evaluation** – Check accuracy on both training and test sets.  
   - ✅ **Test Accuracy:** `77.7%`  
