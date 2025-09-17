# ml-classification-diabetes-titanic-notebook-03
End-to-end ML classification projects featuring extensive EDA, data cleaning and feature engineering. Includes Diabetes Prediction using KNN &amp; SVM, and Titanic Survival Prediction using KNN, SVM &amp; Logistic Regression with model evaluation and performance comparison.
```
# 🧠 Machine Learning Classification Projects  
Diabetes Prediction & Titanic Survival Prediction

# 📄 Overview
This repository contains two end-to-end machine learning classification projects built in Google Colab:

- Diabetes Prediction – implemented using K-Nearest Neighbors (KNN) and Support Vector Machine (SVM).
- Titanic Survival Prediction – implemented using K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Logistic Regression.

Both notebooks include Exploratory Data Analysis (EDA), data preprocessing, feature engineering, model training, evaluation and comparison of performance metrics.

 📝 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Datasets](#-datasets)
- [Methodology](#-methodology)
- [Results](#-results)
- [How to Run](#-how-to-run)
- [Requirements](#-requirements)
- [License](#-license)

##  Features
- Comprehensive EDA : distributions, correlations, and insights for each dataset.
- Missing value imputation & data cleaning.
- Encoding of categorical features and feature scaling.
- Implementation of multiple classification algorithms.
- Comparison of model performance with metrics & visualizations.





## 📊 Datasets
- Diabetes Dataset – Pima Indians Diabetes Database (publicly available on Kaggle/UCI).
- Titanic Dataset – Titanic: Machine Learning from Disaster (publicly available on Kaggle).

## ⚙️ Methodology

1. Data Loading & Cleaning
   - Handling missing values (`Age`, `Embarked`, etc.).
   - Dropping irrelevant columns (e.g., `Cabin`).
2. Exploratory Data Analysis (EDA)
   - Summary statistics & visualizations.
   - Correlation heatmaps, distribution plots.
3. Feature Engineering
   - Encoding categorical features with `pd.get_dummies`.
   - Scaling numerical features with `StandardScaler`.
4. Modeling
   - Diabetes: KNN, SVM.
   - Titanic: KNN, SVM, Logistic Regression.
5. Model Evaluation
   - Accuracy, confusion matrix, classification report.
   - Comparison of all model performances.


 🏆 Results
- Diabetes Prediction: KNN & SVM performance metrics displayed in the notebook.
- Titanic Survival Prediction: KNN, SVM & Logistic Regression compared side-by-side.

(See notebook outputs for exact scores and graphs.)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/TheConqueror27/ml-classification-diabetes-titanic-notebook-03.git
   cd ml-classification-diabetes-titanic-notebook-03
````

2. Open in Google Colab :

   * Upload `notebooks/diabetes_titanic_notebook.ipynb` to your Google Drive.
   * Run all cells.
     (Ensure you’ve downloaded the datasets and updated the file paths inside the notebook.)

3. Install dependencies locally (optional):

   ```bash
   pip install -r requirements.txt
   ```

---

## 🛠 Requirements

* Python 3.8+
* pandas
* numpy
* scikit-learn
* matplotlib / seaborn (for EDA visuals)

*(You can add a `requirements.txt` file listing these packages.)*


## 📜 License

This project is licensed under the [MIT License](LICENSE) – you’re free to use, modify, and distribute with attribution.

---

## 👤 Author

Soumyadip Chatterjee
Autumn Intern 
IDEAS TIH @ISI KOLKATA
2nd Year, 3rd Semester 
College- GCELT,Kolkata


## 🤝 Contributions

Feedback, issues, and pull requests are welcome!
