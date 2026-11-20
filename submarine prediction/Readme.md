# 🚢 Sonar Rock vs Mine Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on classifying underwater objects as either **Rock (R)** or **Mine (M)** using Machine Learning.

The system uses sonar signal data collected from underwater objects and applies a Logistic Regression algorithm to classify whether the detected object is a rock or a mine.

The model learns patterns from sonar signal measurements and predicts the class of previously unseen sonar data.

## 🎯 Project Objectives

- Analyze sonar signal data.
- Understand the distribution of rock and mine samples.
- Separate input features and target labels.
- Train a Machine Learning classification model.
- Evaluate model performance using accuracy score.
- Predict underwater object categories using new sonar measurements.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - NumPy – Numerical operations
  - Pandas – Data manipulation and analysis
  - Scikit-learn – Machine Learning model development and evaluation

## 📊 Dataset Description

The project uses the `sonar_data.csv` dataset.

- Total records: 208
- Total columns: 61
- Input features: 60 sonar signal measurements
- Target variable: 1 class label

| Class | Description | Records |
|---|---|---:|
| M | Mine | 111 |
| R | Rock | 97 |

Each record contains 60 numerical features representing sonar signal measurements.

The final column represents the target class:
- **M:** Mine
- **R:** Rock

## 🤖 Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised Machine Learning classification algorithm used to predict categorical outcomes.

In this project:
- Input: 60 sonar signal measurements.
- Output: Rock (R) or Mine (M).

The model learns the relationship between sonar measurements and their corresponding classes to classify new underwater signals.

## ⚙️ Project Workflow

1. **Data Collection:** Load the sonar dataset using Pandas.
2. **Data Exploration:** Examine sample records and class distribution.
3. **Feature Selection:** Separate the 60 input features from the target column.
4. **Train-Test Split:** Divide the dataset into 50% training data and 50% testing data using stratified sampling.
5. **Model Initialization:** Create a Logistic Regression classifier.
6. **Model Training:** Train the model using the training dataset.
7. **Model Evaluation:** Calculate training and testing accuracy using accuracy_score.
8. **Prediction:** Provide new sonar measurements to predict whether the detected object is a rock or a mine.

## 📈 Model Evaluation

The model performance is evaluated using accuracy score.

Two evaluations are performed:

- Training Accuracy: Measures how accurately the model predicts the training data.
- Testing Accuracy: Measures how accurately the model predicts unseen testing data.

## 🔍 Sample Prediction

The notebook uses 60 sonar measurements as input to predict the underwater object's class.

```python
prediction = model.predict(input_data_reshaped)
print(prediction)
```

Possible outputs:

- **M:** Mine
- **R:** Rock

## 📂 Project Structure

```text
Sonar-Rock-vs-Mine-Prediction/
│
├── Submarine prediction.ipynb
├── sonar_data.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:

```bash
cd Sonar-Rock-vs-Mine-Prediction
```

3. Install the required libraries:

```bash
pip install numpy pandas scikit-learn jupyter
```

4. Ensure `sonar_data.csv` is available in the project directory.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Submarine prediction.ipynb` and run all cells.

## 🔮 Future Improvements

- Experiment with other classification algorithms.
- Improve model performance through hyperparameter tuning.
- Evaluate the model using precision, recall, F1-score, and confusion matrix.
- Develop a web-based interface for sonar signal classification.
- Deploy the trained model for real-time predictions.

## ⚠️ Disclaimer

This project is developed for educational and learning purposes. Predictions are based on the provided sonar dataset and should not be treated as a substitute for professional underwater object identification systems.

## 👩‍💻 Author

**Harshitha U**

Aspiring Data Analyst | Aspiring Data Scientist
