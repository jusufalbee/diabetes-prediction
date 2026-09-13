# 🩺 Diabetes Prediction System using Support Vector Machine (SVM)

This machine learning project predicts whether a patient has diabetes based on specific medical indicators. The model is built using a **Support Vector Machine (SVM)** classifier trained on the historical **PIMA Indians Diabetes Dataset**.

---

## 📊 Dataset Overview

The dataset consists of **768 patient records** with **8 medical features** and 1 target label:

* **Pregnancies**: Number of times pregnant.
* **Glucose**: Plasma glucose concentration (2 hours in an oral glucose tolerance test).
* **BloodPressure**: Diastolic blood pressure (mm Hg).
* **SkinThickness**: Triceps skin fold thickness (mm).
* **Insulin**: 2-Hour serum insulin (mu U/ml).
* **BMI**: Body Mass Index ($\text{weight in kg} / (\text{height in m})^2$).
* **DiabetesPedigreeFunction**: Diabetes pedigree function (genetic score).
* **Age**: Age in years.
* **Outcome** *(Target)*: `1` for Diabetic, `0` for Non-Diabetic.

---

## ⚙️ Workflow Steps

1. **Exploratory Data Analysis (EDA)**: Inspecting data dimensions, summary statistics, and target class distributions.
2. **Data Preprocessing**: Standardizing features using Scikit-Learn's `StandardScaler` to optimize SVM performance.
3. **Data Splitting**: Splitting data into **Training Set (80%)** and **Test Set (20%)** using *Stratified Sampling* to preserve class proportions.
4. **Model Training**: Fitting a **Support Vector Classifier (SVC)** using a linear kernel.
5. **Model Evaluation**: Evaluating accuracy on both training and test sets.
6. **Inference Pipeline**: Building a prediction routine for new single-instance patient data.

---

## 🚀 Model Performance

* **Training Accuracy**: ~78.66%
* **Test Accuracy**: ~77.27%

---

## 🛠️ How to Run

### 1. Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install numpy pandas scikit-learn
