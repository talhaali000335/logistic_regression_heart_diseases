# <div align="center">Heart Disease Dataset Documentation</div>

<div align="justify">

## Overview

This project utilizes a comprehensive heart disease dataset that contains medical and demographic information from 303 individuals. The dataset is designed for binary classification tasks to predict the presence or absence of heart disease in patients based on various clinical and demographic features.

## Dataset Characteristics

- **Dataset Size**: 303 records (patients)
- **Number of Features**: 14 attributes (13 independent variables + 1 target variable)
- **Data Quality**: Complete dataset with no missing values
- **File Format**: CSV (Comma-Separated Values)
- **File Name**: `heart_disease_data.csv`
- **Target Distribution**:
  - Heart Disease Present (1): 165 patients (54.5%)
  - Heart Disease Absent (0): 138 patients (45.5%)

## Feature Descriptions

### 1. Age (`age`)

- **Type**: Numerical (Integer)
- **Description**: Age of the patient in years
- **Range**: Typically between 29-77 years
- **Clinical Significance**: Age is a significant risk factor for heart disease, with risk generally increasing with age

### 2. Sex (`sex`)

- **Type**: Categorical (Binary)
- **Values**:
  - `1`: Male
  - `0`: Female
- **Clinical Significance**: Gender plays a role in heart disease risk, with different patterns observed between males and females

### 3. Chest Pain Type (`cp`)

- **Type**: Categorical (Multi-class)
- **Values**:
  - `0`: Asymptomatic
  - `1`: Atypical angina
  - `2`: Non-anginal pain
  - `3`: Typical angina
- **Clinical Significance**: Different types of chest pain can indicate varying levels of heart disease risk

### 4. Resting Blood Pressure (`trestbps`)

- **Type**: Numerical (Integer)
- **Unit**: mm Hg (millimeters of mercury)
- **Description**: Resting blood pressure measured upon hospital admission
- **Normal Range**: Typically 120/80 mm Hg or lower
- **Clinical Significance**: High blood pressure is a major risk factor for cardiovascular disease

### 5. Serum Cholesterol (`chol`)

- **Type**: Numerical (Integer)
- **Unit**: mg/dl (milligrams per deciliter)
- **Description**: Serum cholesterol level in the patient's blood
- **Healthy Range**: Generally below 200 mg/dl
- **Clinical Significance**: High cholesterol levels contribute to atherosclerosis and increase heart disease risk

### 6. Fasting Blood Sugar (`fbs`)

- **Type**: Categorical (Binary)
- **Values**:
  - `1`: Fasting blood sugar > 120 mg/dl (indicates diabetes)
  - `0`: Fasting blood sugar ≤ 120 mg/dl (normal)
- **Clinical Significance**: Diabetes significantly increases the risk of cardiovascular disease

### 7. Resting Electrocardiographic Results (`restecg`)

- **Type**: Categorical (Multi-class)
- **Values**:
  - `0`: Normal
  - `1`: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression > 0.05 mV)
  - `2`: Showing probable or definite left ventricular hypertrophy by Estes' criteria
- **Clinical Significance**: ECG abnormalities can indicate underlying heart conditions

### 8. Maximum Heart Rate Achieved (`thalach`)

- **Type**: Numerical (Integer)
- **Unit**: Beats per minute (bpm)
- **Description**: Maximum heart rate achieved during exercise stress testing
- **Normal Range**: Varies by age; generally calculated as 220 minus age
- **Clinical Significance**: Lower maximum heart rate may indicate poor cardiovascular fitness or underlying heart disease

### 9. Exercise Induced Angina (`exang`)

- **Type**: Categorical (Binary)
- **Values**:
  - `1`: Yes (exercise induced angina present)
  - `0`: No (no exercise induced angina)
- **Clinical Significance**: Chest pain triggered by exercise is a strong indicator of coronary artery disease

### 10. ST Depression (`oldpeak`)

- **Type**: Numerical (Float)
- **Unit**: Depression in mm
- **Description**: ST depression induced by exercise relative to rest
- **Clinical Significance**: ST depression during exercise testing can indicate coronary artery disease

### 11. Slope of Peak Exercise ST Segment (`slope`)

- **Type**: Categorical (Multi-class)
- **Values**:
  - `0`: Downsloping
  - `1`: Flat
  - `2`: Upsloping
- **Clinical Significance**: The slope pattern helps in interpreting the exercise stress test results

### 12. Number of Major Vessels Colored by Fluoroscopy (`ca`)

- **Type**: Numerical (Integer)
- **Range**: 0-3
- **Description**: Number of major coronary vessels (0-3) colored by fluoroscopy
- **Clinical Significance**: More vessels with significant blockage indicate more severe coronary artery disease

### 13. Thalassemia (`thal`)

- **Type**: Categorical (Multi-class)
- **Values**:
  - `1`: Normal
  - `2`: Fixed defect
  - `3`: Reversible defect
- **Clinical Significance**: Thalassemia results help assess blood flow to the heart muscle

### 14. Target Variable (`target`)

- **Type**: Categorical (Binary)
- **Values**:
  - `1`: Heart disease present (diagnosed with heart disease)
  - `0`: Heart disease absent (no heart disease)
- **Description**: This is the target variable that the machine learning model aims to predict

## Data Quality Assessment

### Completeness

- **Missing Values**: 0 (zero missing values across all features)
- **Data Integrity**: All 303 records contain complete information for all 14 attributes
- **Quality Score**: Excellent - no data preprocessing required for missing values

### Data Types

- **Numerical Features**: 5 features (age, trestbps, chol, thalach, oldpeak)
- **Categorical Features**: 9 features (sex, cp, fbs, restecg, exang, slope, ca, thal, target)
- **Mixed Data Types**: The dataset contains both continuous numerical values and discrete categorical values

## Statistical Summary

### Target Variable Distribution

The dataset shows a relatively balanced distribution of the target variable:

- **Positive Cases** (Heart Disease): 165 patients (54.5%)
- **Negative Cases** (No Heart Disease): 138 patients (45.5%)
- **Balance Ratio**: Approximately 1.2:1, which is excellent for machine learning model training

### Key Insights

1. **No Data Preprocessing Required**: The dataset is clean with no missing values
2. **Balanced Classes**: The target variable is well-balanced, reducing the need for sampling techniques
3. **Comprehensive Features**: Includes demographic, clinical, and diagnostic test results
4. **Real-world Clinical Data**: Features represent actual medical measurements and assessments used in clinical practice

## Usage in Machine Learning

This dataset is particularly well-suited for:

- **Binary Classification**: Predicting heart disease presence/absence
- **Logistic Regression**: As demonstrated in this project
- **Feature Importance Analysis**: Understanding which factors most strongly predict heart disease
- **Medical Research**: Analyzing relationships between various risk factors and heart disease

## Data Source and Reliability

The heart disease dataset is a widely-used benchmark dataset in the machine learning community, originally compiled from several medical institutions. It represents real patient data and has been validated for research purposes, making it an excellent choice for developing and testing heart disease prediction models.

## Ethical Considerations

When working with this medical dataset, it's important to consider:

- **Privacy**: All patient data has been anonymized
- **Medical Disclaimer**: Predictions should not replace professional medical diagnosis
- **Bias Awareness**: Results should be interpreted considering potential demographic biases in the original data collection

</div>
