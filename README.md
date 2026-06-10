# Heart Disease Analysis Across Regions

## Project Overview

This project investigates heart disease risk factors using patient data collected from four different regions: Cleveland, Hungary, Switzerland, and VA.

The main objective was to identify important predictors of heart disease, evaluate the impact of missing values on model performance, compare disease prevalence across regions, and explore hidden structures within the data using clustering techniques.

---

## Dataset

The dataset contains information from **920 patients** and includes:

- Demographic information (age, sex)
- Clinical measurements (cholesterol, blood pressure, maximum heart rate)
- Diagnostic indicators (chest pain type, exercise-induced angina, thalassemia, etc.)
- Region of origin
- Heart disease diagnosis (target variable)

Target variable:

- **0** = No Heart Disease
- **1** = Heart Disease

---

## Project Structure

### 1. Data Understanding

- Variable type identification
- Numerical vs categorical features
- Initial exploratory analysis
- Correlation analysis

### 2. Population Comparison

- Comparison of patient characteristics across regions
- Disease prevalence analysis
- Regional differences in risk factors

### 3. Data Cleaning

- Detection of hidden missing values
- Replacement of physiologically impossible values
- Missing value analysis
- Comparison of multiple imputation strategies

### 4. Predictive Modeling

- Logistic Regression
- Feature preprocessing
- Model comparison
- ROC-AUC evaluation

### 5. Stability Across Regions

- Investigation of whether relationships remain consistent across populations
- Comparison of regional disease patterns
- Regional model evaluation

### 6. Clustering Analysis

- K-Means clustering
- Elbow Method
- Patient subgroup identification
- Cluster interpretation

### 7. Interpretation of Regional Differences

- Statistical interpretation of findings
- Discussion of biological and non-biological explanations

---

## Methods and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Logistic Regression
- K-Means Clustering

---

## Key Findings

- Significant differences in heart disease prevalence were observed across regions.
- Several variables showed meaningful relationships with heart disease diagnosis.
- Missing value handling strategies influenced model performance.
- Logistic Regression achieved strong predictive performance.
- Clustering revealed distinct patient profiles with different disease risks.

---

## Repository Structure

```
Data/
│
├── heart.csv
├── heart_cleaned.csv

Notebooks/
│
├── 01_data_understanding.ipynb
├── 02_population_comparison.ipynb
├── 03_data_cleaning.ipynb
├── 04_modeling.ipynb
├── 05_stability_across_regions.ipynb
├── 06_unknown_structure.ipynb
├── 07_interpreting_differences.ipynb
```

---

## Author

Javid Nurulu

Data Science Student – University of Augsburg
