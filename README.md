# Credit Risk Modeling

A machine learning project for predicting customer credit risk using the German Credit dataset. The project includes exploratory data analysis, preprocessing, model comparison, hyperparameter tuning, and deployment using Streamlit.

## Project Overview

This project aims to classify customers into risk categories based on demographic and financial information.

The workflow includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature encoding
* Training multiple machine learning models
* Hyperparameter tuning using GridSearchCV
* Model evaluation and comparison
* Saving the best model
* Building an interactive Streamlit application

## Dataset

Dataset used: German Credit Dataset

Features include:

* Age
* Sex
* Job
* Housing
* Saving accounts
* Checking account
* Credit amount
* Duration

Target:

* Risk (Good / Bad)

## Models Used

* Decision Tree
* Random Forest
* Extra Trees Classifier
* XGBoost

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Joblib
* Streamlit

## Run Locally

Clone the project:

```bash
git clone https://github.com/your-username/Credit-Risk-Modeling.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run app.py
```

## Results

The project compares multiple machine learning algorithms and selects the best-performing model based on accuracy.

