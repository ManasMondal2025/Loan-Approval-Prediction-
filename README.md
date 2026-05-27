# Loan Eligibility Prediction using Machine Learning

## Overview

This project builds and evaluates multiple machine learning models to predict loan eligibility based on applicant information. The notebook performs complete data analysis and preprocessing, followed by training and comparing several classification algorithms.

The workflow includes:

* Data loading and cleaning
* Exploratory Data Analysis (EDA)
* Feature preprocessing
* Handling missing values and outliers
* Model training and evaluation
* Performance comparison across models

---

## Project Structure

```text
.
├── final.ipynb          # Main Jupyter Notebook
├── README.md            # Project documentation
└── Report.pdf           # Report of the project
```

---

## Features

### Data Preprocessing

* Remove whitespaces from column names
* Handle null/missing values
* Encode categorical variables
* Remove duplicate records
* Remove outliers and infinite values
* Normalize numerical features

### Exploratory Data Analysis

* Histogram distributions
* Pairwise relationship visualization
* Correlation heatmap
* Numerical statistics

### Machine Learning Models

The following models are trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Decision Tree
5. Random Forest
6. Gradient Boosting

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Workflow

### 1. Import Libraries and Dataset

The notebook starts by importing required libraries and loading the loan dataset.

### 2. Data Cleaning

Data inconsistencies such as null values, duplicated rows, and unnecessary variables are handled.

### 3. Exploratory Data Analysis

Visualizations and statistical analysis are performed to better understand the dataset.

### 4. Feature Engineering and Preprocessing

Categorical features are encoded and numerical features are normalized.

### 5. Train-Test Split

The dataset is split into training and testing sets.

### 6. Model Training

Multiple classification algorithms are trained.

### 7. Model Evaluation

Models are compared using:

* Accuracy
* Performance plots
* Training time comparison

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/loan-eligibility-prediction.git
cd loan-eligibility-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
final.ipynb
```

Run all cells to reproduce the results.

---

## Example Use Case

Given applicant details such as:

* Education
* Employment status
* Income
* Loan amount
* Credit history

The trained model predicts whether the loan application is likely to be approved or rejected.

---

## Results

The notebook compares multiple machine learning algorithms and visualizes:

* Model performance
* Accuracy comparison
* Training efficiency

This helps identify the most effective model for loan approval prediction.

---

## Future Improvements

Possible enhancements:

* Hyperparameter tuning
* Cross-validation
* Feature selection
* Deployment using Flask or Streamlit
* Deep learning approaches

---

## License

This project is for educational and learning purposes.

---

## Author

Created by Manas.

give me code
