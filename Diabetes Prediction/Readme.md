# 🩺 Diabetes Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a person is diabetic or non-diabetic using Machine Learning techniques.

A **Support Vector Machine (SVM)** algorithm is used to classify individuals based on medical attributes such as glucose level, blood pressure, BMI, insulin level, age, and other health-related factors.

The project includes data preprocessing, feature standardization, model training, evaluation, and a predictive system that accepts individual input to generate predictions.

## 🎯 Objectives

- Analyze diabetes-related medical data.
- Perform data preprocessing and feature standardization.
- Train a Machine Learning classification model.
- Evaluate model performance using accuracy score.
- Predict diabetes outcomes for new input data.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - Pandas – Data manipulation and analysis
  - NumPy – Numerical operations
  - Scikit-learn – Machine Learning and model evaluation

## 🤖 Machine Learning Algorithm

**Support Vector Machine (SVM)**

- Algorithm: Support Vector Classifier (SVC)
- Kernel: Linear

SVM is a supervised Machine Learning algorithm used for classification. It identifies an optimal decision boundary that separates different classes.

## 📊 Dataset Description

The dataset contains 769 records and 9 columns.

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose concentration |
| BloodPressure | Blood pressure |
| SkinThickness | Skin thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age of the individual |
| Outcome | 0 = Non-diabetic, 1 = Diabetic |

**Dataset distribution:**
- Non-diabetic: 500 records
- Diabetic: 269 records

## ⚙️ Project Workflow

1. **Data Collection:** Load the diabetes dataset using Pandas.
2. **Exploratory Data Analysis:** Examine dataset dimensions, statistical information, data types, and class distribution.
3. **Data Preprocessing:** Separate independent features and the target variable.
4. **Feature Standardization:** Apply StandardScaler to standardize the input features.
5. **Train-Test Split:** Divide the dataset into 80% training data and 20% testing data using stratified sampling.
6. **Model Training:** Train an SVM classifier with a linear kernel.
7. **Model Evaluation:** Evaluate training and testing accuracy using accuracy_score.
8. **Prediction:** Build a predictive system to classify new individual medical inputs.

## 📈 Model Performance

The model achieved the following accuracy scores:

| Evaluation | Accuracy |
|---|---:|
| Training Accuracy | 78.86% |
| Testing Accuracy | 75.97% |

## 🔍 Sample Prediction

The predictive system accepts eight medical input features:

```python
input_data = (5, 166, 72, 19, 175, 25.8, 0.587, 50)
```

The input is standardized using the trained StandardScaler and passed to the SVM classifier.

The model predicts one of two outcomes:

- **0:** Patient is predicted to be non-diabetic.
- **1:** Patient is predicted to be diabetic.

## 📂 Project Structure

```text
Diabetes-Prediction/
│
├── Diabetes Prediction.ipynb
├── diabetes.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:

```bash
cd Diabetes-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy scikit-learn jupyter
```

4. Ensure that `diabetes.csv` is available in the project directory.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Diabetes Prediction.ipynb` and run all cells.

## 🔮 Future Improvements

- Experiment with additional classification algorithms.
- Improve model performance through hyperparameter tuning.
- Evaluate the model using precision, recall, F1-score, and confusion matrix.
- Develop a web-based interface for user-friendly predictions.
- Deploy the trained model for real-time predictions.

## ⚠️ Disclaimer

This project is developed for educational and learning purposes. Its predictions should not be considered a medical diagnosis or a substitute for professional medical advice.

## 👩‍💻 Author

**Harshitha U**

Aspiring Data Analyst | Aspiring Data Scientist
