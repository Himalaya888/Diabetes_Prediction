# 🩺 Diabetes Prediction using Machine Learning

This project demonstrates how to build a **Diabetes Prediction System** using the **PIMA Indians Diabetes Dataset** and a **Support Vector Machine (SVM) classifier**. It was developed in **Google Colab** and later exported as a Python script.

## 📌 Project Overview
The goal of this project is to predict whether a person is diabetic or non-diabetic based on health parameters such as:
- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

The dataset is preprocessed, standardized, and then trained using an **SVM with linear kernel**.

## ⚙️ Tech Stack
- Python 3
- NumPy
- Pandas
- Scikit-learn

## 📂 Dataset
- Dataset used: [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- File: `diabetes.csv`

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
````

2. Install the required libraries:

   ```bash
   pip install numpy pandas scikit-learn
   ```
3. Run the script:

   ```bash
   python a1f23f1f-1af8-42d2-9161-c86453d35f0a.py
   ```

## 📊 Model Performance

* Training Accuracy: ~79%
* Testing Accuracy: ~77%
  (*Values may slightly vary depending on train-test split.*)

## 🧪 Example Prediction

The model can predict whether a person is diabetic based on input data. Example:

```python
input_data = (5,166,72,19,175,25.8,0.587,51)  # sample health parameters
```

**Output:**

```
The person is diabetic
```

## 📌 Future Improvements

* Try other ML algorithms (Random Forest, XGBoost, Logistic Regression).
* Hyperparameter tuning for better accuracy.
* Deploy as a Flask/Django web app or Streamlit app.
