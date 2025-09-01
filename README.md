# Logistic Regression Prediction on Framingham Heart Disease Dataset

## 📌 Project Overview

This project applies **Logistic Regression** to the **Framingham Heart Study dataset** to predict the **10-year risk of developing Coronary Heart Disease (CHD)**. The dataset contains demographic, behavioral, and clinical attributes of participants.

The analysis includes:

* Data cleaning and exploration
* Visualization of key variables
* Logistic regression model fitting
* Interpretation of significant predictors

## 📂 Dataset

**Source:** [Kaggle - Framingham Heart Study Dataset](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)

* **Rows:** \~4,240
* **Columns:** 16 (15 predictors + target)

### 🔑 Variables

* `male`: Binary, participant’s gender (1 = male, 0 = female)
* `age`: Age in years
* `education`: Education level (years)
* `currentSmoker`: Binary, 1 if current smoker
* `cigsPerDay`: Number of cigarettes smoked daily
* `BPmeds`: Binary, on blood pressure medication
* `prevalentStroke`: Binary, history of stroke
* `prevalentHyp`: Binary, hypertension history
* `diabetes`: Binary, diabetes status
* `totChol`: Total cholesterol
* `sysBP`: Systolic blood pressure
* `diaBP`: Diastolic blood pressure
* `BMI`: Body Mass Index
* `heartRate`: Heart rate
* `glucose`: Blood glucose level
* **Target:** `TenYearCHD` (1 = CHD within 10 years, 0 = no CHD)

## ⚙️ Requirements

To run the notebook, install the following packages:

```bash
pip install numpy pandas seaborn plotly scikit-learn statsmodels
```

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Download the dataset (`framingham.csv`) from Kaggle and place it in your working directory.
3. Open the notebook and run step by step:

   * **Step 1:** Import required libraries
   * **Step 2:** Load dataset
   * **Step 3:** Perform Exploratory Data Analysis (EDA)
   * **Step 4:** Visualize data
   * **Step 5:** Build Logistic Regression model
   * **Step 6:** Evaluate model performance

## 📊 Analysis Workflow

### 1. Data Exploration

* Checked dataset dimensions and column names
* Reviewed descriptive statistics
* Handled missing values

### 2. Data Visualization

* Distribution of age, cholesterol, and blood pressure
* Smoking status vs CHD
* Correlation heatmap of predictors

### 3. Logistic Regression

* Fitted logistic regression model using **statsmodels** and **scikit-learn**
* Evaluated significance of predictors (p-values, confidence intervals)
* Assessed model accuracy, recall, and confusion matrix

### 4. Interpretation

At **5% significance level (α = 0.05)**, the following predictors were significant:

* `prevalentStroke`
* `diabetes`

This suggests these factors strongly contribute to the 10-year CHD risk in the dataset.


## 📈 Model Evaluation

Metrics used:

* **Accuracy**
* **Recall**
* **Confusion Matrix**

(Refer to notebook outputs for detailed results.)

## 👩🏽‍💻 Author

**Consolas HODONOU**
*Data Analyst & MSc Student in Biostatistics (LABEF/UAC, Benin)*

✨ *This project highlights how logistic regression can be applied in health research for disease risk prediction.*


Would you like me to also include a **"Results & Key Insights"** section with formatted plots and metrics directly summarized from your notebook, so the README stands on its own even without running the notebook?
