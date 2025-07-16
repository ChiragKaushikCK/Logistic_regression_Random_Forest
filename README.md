# Logistic_regression_Random_Forest

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
</div>

<h1 align="center">
  <br>
  <a href="https://github.com/your-username/logistic-regression-vs-random-forest"><img src="https://raw.githubusercontent.com/Anandp711/Weather-prediction-using-multiple-models/main/Assets/images/header.png" alt="Logistic Regression vs Random Forest" width="600"></a>
  <br>
  Logistic Regression vs. Random Forest for Weather Prediction 🌦️
  <br>
</h1>

<div align="center">
  <p>
    A comparative analysis of Logistic Regression and Random Forest Classifiers for predicting rainfall, highlighting their strengths and weaknesses.
  </p>
</div>

<br>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#model-performance">Model Performance</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

---

## <a id="about-the-project"></a> 📚 About The Project

This project provides a detailed comparative study between two powerful classification algorithms: **Logistic Regression** and **Random Forest Classifier**. The primary goal is to predict rainfall based on a comprehensive weather dataset. The notebook meticulously walks through data preprocessing, model training, prediction, and rigorous evaluation, offering insights into which model might be more suitable for such a task.

---

## <a id="features"></a> ✨ Features

* **Extensive Data Cleaning**: Handles missing values and drops irrelevant columns to ensure data quality.
* **Categorical Feature Encoding**: Utilizes both `LabelEncoder` and `OneHotEncoder` to transform categorical data into a machine-learning-ready format.
* **Data Splitting**: Divides the cleaned and encoded dataset into training and testing subsets for unbiased model evaluation.
* **Logistic Regression Implementation**: Trains and evaluates a Logistic Regression model, a widely used linear classification algorithm.
* **Random Forest Classifier Implementation**: Trains and evaluates a Random Forest Classifier, an ensemble learning method known for its robustness.
* **Comparative Analysis**: Provides a side-by-side comparison of the accuracy and confusion matrices for both models, highlighting their predictive strengths and weaknesses.

---

## <a id="dataset"></a> 📊 Dataset

The project utilizes the `weatherAUS.csv` dataset, which contains daily weather observations from various Australian weather stations. This dataset is rich with features relevant to rainfall prediction.

**Key Features (after preprocessing):**
* `MinTemp`, `MaxTemp`, `Rainfall`, `Evaporation`, `Sunshine`
* `WindGustSpeed`, `WindSpeed9am`, `WindSpeed3pm`
* `Humidity9am`, `Humidity3pm`, `Pressure9am`, `Pressure3pm`
* `Cloud9am`, `Cloud3pm`, `Temp9am`, `Temp3pm`
* `RainToday` (Binary: Yes/No), `RainTomorrow` (Target Variable: Yes/No)
* **One-Hot Encoded Categorical Features**: `Location`, `WindGustDir`, `WindDir9am`, `WindDir3pm`

---

📈 Model Performance
Here's a summary of the performance for both models:

Logistic Regression
Accuracy Score: Approximately 85.02%

Confusion Matrix:

[[21581  1160]
 [ 3435  2916]]


Random Forest Classifier
Accuracy Score: Approximately 90.04%

Confusion Matrix:

[[21721  1020]
 [ 3360  2991]]
