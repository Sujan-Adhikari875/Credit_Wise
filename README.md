# Credit_Wise
# Loan Approval Prediction

## About the Project

This project focuses on predicting whether a loan application will be approved based on applicant information such as income, credit history, employment status, loan amount, and other demographic details.

I built this project to practice the complete machine learning workflow—from data cleaning and exploratory data analysis to feature engineering, model training, and evaluation. The goal was not only to achieve good prediction performance but also to understand which factors have the biggest impact on loan approval decisions.

---

## What I Learned

Through this project, I gained hands-on experience with:

* Handling missing values
* Exploratory Data Analysis (EDA)
* Data preprocessing and encoding
* Feature scaling
* Feature engineering
* Training and evaluating machine learning models
* Comparing different classification algorithms

---

## Dataset

The dataset contains information about loan applicants, including:

* Gender
* Marital Status
* Dependents
* Education
* Employment Status
* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit History
* Property Area
* Loan Approval Status (Target Variable)

---

## Project Workflow

### 1. Data Cleaning

The dataset contained missing values in both numerical and categorical columns. These values were handled using appropriate imputation techniques to prepare the data for modeling.

### 2. Exploratory Data Analysis

I explored the data using various visualizations to better understand:

* Feature distributions
* Outliers
* Relationships between variables
* Loan approval trends

### 3. Data Preprocessing

The preprocessing stage included:

* Encoding categorical features
* Feature scaling
* Preparing data for machine learning models

### 4. Feature Engineering

To improve model performance, I created additional features such as:

* Debt-to-Income Ratio
* Log-transformed income features
* Squared financial indicators

### 5. Model Training

I trained and compared multiple machine learning algorithms:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes

### 6. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall

The performance comparison helped identify which model worked best for this dataset.

---

## Key Insights

Some interesting observations from the analysis:

* Credit history plays a major role in loan approval decisions.
* Income-related features have a strong influence on approval rates.
* Feature engineering helped improve predictive performance.
* Simple models such as Logistic Regression can perform surprisingly well on structured tabular data.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

```text
Loan-Approval-Prediction/
│
├── loan_approval.ipynb
├── README.md
├── requirements.txt
└── dataset/
```

---

## Future Improvements

There are several areas where this project can be extended:

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Random Forest and XGBoost models
* Model deployment using Streamlit
* Explainable AI using SHAP values

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/Sujan-Adhikari875/Credit_Wise.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open and run:

```bash
loan_approval.ipynb
```

---

## Final Thoughts

This project was a great opportunity to strengthen my understanding of machine learning workflows and predictive modeling. It helped me practice working with real-world tabular data and reinforced the importance of preprocessing and feature engineering in building effective models.

Feedback and suggestions are always welcome.
