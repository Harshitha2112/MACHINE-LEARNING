# 💼 Employee Salary Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting employee salaries based on their years of experience using Machine Learning.

A **Linear Regression** algorithm is implemented to understand the relationship between work experience and salary. The model is trained using historical salary data and predicts the expected salary for a given number of years of experience.

## 🎯 Project Objectives

- Analyze the relationship between years of experience and salary.
- Perform data preprocessing and cleaning.
- Train a Machine Learning regression model.
- Evaluate model performance using the R² score.
- Predict employee salaries based on experience.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - Pandas – Data manipulation and analysis
  - Matplotlib – Data visualization
  - Scikit-learn – Machine Learning model development and evaluation

## 📊 Dataset Description

The project uses `Salary_dataset.csv`.

| Feature | Description |
|---|---|
| YearsExperience | Number of years of work experience |
| Salary | Employee salary |

The dataset is used to train the regression model to identify the relationship between experience and salary.

## 🤖 Machine Learning Algorithm

**Linear Regression**

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

In this project:
- Independent Variable (X): Years of Experience
- Dependent Variable (Y): Salary

The model learns the relationship between these variables and predicts salary based on experience.

## ⚙️ Project Workflow

1. **Data Collection:** Load the salary dataset using Pandas.
2. **Data Exploration:** Display sample records and understand the dataset.
3. **Data Cleaning:** Remove the unnecessary `Unnamed: 0` column and check for missing values.
4. **Feature Selection:** Select YearsExperience as the independent variable and Salary as the dependent variable.
5. **Train-Test Split:** Split the dataset into 80% training data and 20% testing data.
6. **Model Training:** Train a Linear Regression model using the training dataset.
7. **Model Evaluation:** Evaluate the model using the R² score.
8. **Data Visualization:** Visualize the relationship between experience and salary using a scatter plot and regression predictions.
9. **Salary Prediction:** Predict the salary for a given number of years of experience.

## 📈 Model Evaluation

The model performance is evaluated using the **R² (Coefficient of Determination) Score**.

R² measures how well the regression model explains the variation in the target variable.

The actual R² score is calculated when the notebook is executed.

## 🔍 Sample Prediction

The notebook predicts the salary for an employee with 6 years of experience.

```python
model.predict([[6]])
```

The trained Linear Regression model returns the predicted salary.

## 📂 Project Structure

```text
Employee-Salary-Prediction/
│
├── Employee Salary Prediction.ipynb
├── Salary_dataset.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:

```bash
cd Employee-Salary-Prediction
```

3. Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn jupyter
```

4. Ensure `Salary_dataset.csv` is available in the project directory.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Employee Salary Prediction.ipynb` and run all cells.

## 🔮 Future Improvements

- Evaluate the model using additional regression metrics such as MAE, MSE, and RMSE.
- Visualize the regression line using the complete dataset.
- Experiment with additional regression algorithms.
- Develop a web application for interactive salary prediction.
- Deploy the trained model for real-time predictions.

## ⚠️ Disclaimer

This project is developed for educational and learning purposes. Predicted salaries are estimates based on the dataset and should not be considered guaranteed salary offers.

## 👩‍💻 Author

**Harshitha U**

Aspiring Data Analyst | Aspiring Data Scientist
