# Telecom Customer Churn Prediction

This repository contains code and resources for predicting customer churn in a telecom company.
Customer churn refers to the phenomenon where customers stop doing business with a company, typically measured by the percentage of customers who leave over a specific time period.

## Dataset

The dataset used in this project is from the telecom industry and contains information about customers such as their demographics, services they subscribe to,
and whether they have churned or not. The dataset is provided in the file `WA_Fn-UseC_-Telco-Customer-Churn.csv`.

### Features

- `customerID`: A unique identifier for each customer
- `gender`: The customer's gender (male or female)
- `SeniorCitizen`: Indicates if the customer is a senior citizen (1, 0)
- `Partner`: Indicates if the customer has a partner (Yes, No)
- `Dependents`: Indicates if the customer has dependents (Yes, No)
- `tenure`: The duration in months that the customer has been with the company
- `PhoneService`: Indicates if the customer has phone service (Yes, No)
- `MultipleLines`: Indicates if the customer has multiple telephone lines (Yes, No, No phone service)
- `InternetService`: The type of internet service the customer subscribes to (DSL, Fiber optic, No)
- `OnlineSecurity`: Indicates if the customer has online security services (Yes, No, No internet service)
- `OnlineBackup`: Indicates if the customer uses online backup services (Yes, No, No internet service)
- `DeviceProtection`: Indicates if the customer's devices are insured (Yes, No, No internet service)
- `TechSupport`: Indicates if the customer has technical support (Yes, No, No internet service)
- `StreamingTV`: Indicates if the customer subscribes to streaming TV services (Yes, No, No internet service)
- `StreamingMovies`: Indicates if the customer subscribes to streaming movies services (Yes, No, No internet service)
- `Contract`: The type of customer contract (Month-to-month, One year, Two year)
- `PaperlessBilling`: Indicates if the customer uses paperless billing (Yes, No)
- `PaymentMethod`: The methods by which the customer makes payments (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- `MonthlyCharges`: The monthly fee billed to the customer
- `TotalCharges`: The cumulative amount billed to the customer

## Exploratory Data Analysis (EDA)

The notebook `Telecom_Customer_Churn_Prediction.ipynb` contains detailed exploratory data analysis including:

- Data preprocessing
- Handling missing values
- Visualizing class distribution
- Analyzing numeric attributes
- Analyzing categorical attributes
- Feature importance analysis
- Oversampling techniques for handling class imbalance

## Model Building and Evaluation

The notebook also covers:

- Splitting data into train and test subsets
- Training and evaluating logistic regression, random forest, and gradient boosting models
- Performance evaluation metrics such as accuracy, precision, recall, and F1-score
- Confusion matrix analysis for churn prediction

## Requirements

- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn

## Usage

1. Clone this repository:

```bash
git clone https://github.com/your_username/telecom-customer-churn-prediction.git

## Navigate to the project directory:

```bash
cd telecom-customer-churn-prediction

## Feel Free to make any changes by forking the repository and make sure to give me a star