# CMPE 255 – Assignment 1  
## Hands-on Advanced Chatbot Assisted Data Science using ChatGPT

**Name:** Nikita Memane  
**Course:** CMPE 255 – Data Mining  
**Dataset:** Titanic Dataset (Kaggle)

---

## 1. Assignment Objective
The goal of this assignment is to perform a complete data science workflow using **ChatGPT as an AI assistant**. ChatGPT was used to:
- Understand the dataset
- Design an EDA workflow
- Generate and refine code
- Interpret results and observations

The focus of this assignment is on **conceptual understanding, human validation, and responsible AI-assisted analysis**, rather than blind code generation.

---

## 2. Dataset Description
The Titanic dataset contains information about passengers aboard the Titanic, including:
- Demographics (Age, Sex)
- Socio-economic status (Passenger Class, Fare)
- Family relationships (SibSp, Parch)
- Target variable: **Survived** (0 = No, 1 = Yes)

The dataset is commonly used for classification and exploratory data analysis tasks.

---

## 3. ChatGPT-Assisted Workflow
ChatGPT was used throughout the following stages:

### 3.1 Dataset Understanding
ChatGPT helped explain the dataset structure, column meanings, and common data quality issues.

### 3.2 Exploratory Data Analysis (EDA)
ChatGPT suggested a step-by-step EDA workflow including:
- Missing value analysis
- Univariate and bivariate plots
- Correlation analysis
- Feature engineering ideas (e.g., family size)

### 3.3 Code Generation
ChatGPT assisted in generating Python code for:
- Loading the dataset
- Data cleaning and preprocessing
- Visualization using seaborn and matplotlib
- Training a simple baseline classification model

### 3.4 Interpretation
All outputs and suggestions from ChatGPT were manually reviewed, validated, and interpreted before being finalized.

---

## 4. Modeling
A simple classification model (Logistic Regression / Random Forest) was trained to predict passenger survival.
Model performance was evaluated using:
- Accuracy
- Confusion Matrix

The model results aligned with EDA findings, confirming that **Sex** and **Passenger Class** are the most influential features.

---

## 5. Key Observations
- Female passengers had significantly higher survival rates.
- Passengers in higher classes survived more frequently.
- Age and fare also influenced survival indirectly.
- ChatGPT was effective in structuring analysis but required human validation.

---

## 6. Reflection on Using ChatGPT
**What worked well:**
- Clear EDA structure and guidance
- Fast iteration on code and explanations

**Limitations:**
- Generated code required validation
- Some assumptions needed correction

**Conclusion:**
ChatGPT is a powerful assistant for data science when used responsibly with human oversight.

---

## 7. Repository Contents
