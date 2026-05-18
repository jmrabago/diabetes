# 🩺 Diabetes Risk Prediction — U.S. National Health Survey (2023)

A complete **end-to-end machine learning project** developed as the Final Master’s Project (PFM) for the Master’s in Data Science at CEUPE. The goal is to build a classification model capable of predicting diabetes risk based on health and lifestyle variables collected through a large-scale national survey in the United States.

-----

## 📌 Project Overview

|Item       |Detail                                                             |
|-----------|-------------------------------------------------------------------|
|**Type**   |Binary Classification                                              |
|**Domain** |Healthcare / Public Health                                         |
|**Dataset**|U.S. Behavioral Risk Factor Surveillance System (BRFSS) — 2023     |
|**Format** |SAS → CSV (converted as part of the project)                       |
|**Tools**  |Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, Jupyter Notebook|

-----

## 🗂️ Repository Structure

```
diabetes/
│
├── Conversion_sas_a_csv.ipynb     # SAS to CSV format conversion
├── PFM_limpieza.ipynb             # Data cleaning and preprocessing
├── PFM_EDA.ipynb                  # Exploratory Data Analysis (EDA)
├── PFM_Separacion_Dataset.ipynb   # Train/test split and class balancing
└── PFM_ModeladoDatos.ipynb        # Model training, evaluation and comparison
```

-----

## 🔬 Methodology

The project follows a structured data science pipeline:

### 1. 📥 Data Acquisition & Conversion

- Source: BRFSS 2023 annual health survey (SAS `.xpt` format)
- Converted to CSV and filtered to retain only the most clinically relevant features

### 2. 🧹 Data Cleaning

- Handled missing values, encoded categorical variables
- Removed redundant or highly correlated features
- Normalized numerical variables for model compatibility

### 3. 📊 Exploratory Data Analysis (EDA)

- Distribution analysis of target variable (diabetes diagnosis)
- Correlation matrix and feature importance exploration
- Visualization of key health indicators by diabetic status

### 4. ✂️ Dataset Splitting & Class Balancing

- Stratified train/test split to preserve class proportions
- Applied balancing techniques to address class imbalance in the target variable

### 5. 🤖 Modeling & Evaluation

- Trained and compared multiple classification models
- Evaluated using Accuracy, Precision, Recall, F1-Score, and ROC-AUC
- Selected the best-performing model based on clinical relevance metrics

-----

## 📈 Key Features Used

Health and lifestyle variables including:

- BMI and physical activity levels
- Blood pressure and cholesterol status
- Smoking and alcohol consumption habits
- General health self-assessment
- Age group and demographic information

-----

## 🛠️ Technologies

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)

-----

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/jmrabago/diabetes.git
cd diabetes
```

1. Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

1. Open notebooks in order:

```
1. Conversion_sas_a_csv.ipynb
2. PFM_limpieza.ipynb
3. PFM_EDA.ipynb
4. PFM_Separacion_Dataset.ipynb
5. PFM_ModeladoDatos.ipynb
```

-----

## 👤 Author

**José Manuel Rábago Fernández**
Biomedical Engineer | Data Scientist
[LinkedIn](https://linkedin.com/in/jmrabago) · [GitHub](https://github.com/jmrabago)

-----

> *Final Master’s Project — Master’s in Data Science, CEUPE (2024–2025)*