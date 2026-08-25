<div align="justify">

# <div align="center">🫀 Logistic Heart Disease Prediction</div>

<div align="center">

_A comprehensive machine learning project using logistic regression to predict heart disease based on clinical and demographic features_

![Heart Disease](https://img.shields.io/badge/Health-Heart%20Disease%20Prediction-red?style=for-the-badge&logo=heart&logoColor=white) ![Machine Learning](https://img.shields.io/badge/ML-Logistic%20Regression-blue?style=for-the-badge&logo=tensorflow&logoColor=white) ![Python](https://img.shields.io/badge/Python-3.7+-brightgreen?style=for-the-badge&logo=python&logoColor=white) ![Accuracy](https://img.shields.io/badge/Accuracy-85%25+-success?style=for-the-badge)

</div>

## 📋 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [🔬 Dataset Information](#-dataset-information)
- [🚀 Features](#-features)
- [🛠️ Technologies Used](#️-technologies-used)
- [📊 Model Performance](#-model-performance)
- [🏗️ Project Structure](#️-project-structure)
- [⚙️ Installation & Setup](#️-installation--setup)
- [📖 Usage](#-usage)
- [🧪 Model Training Process](#-model-training-process)
- [📈 Results & Analysis](#-results--analysis)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👨‍💻 Author](#-author)

## 🎯 Project Overview

Heart disease is one of the leading causes of death worldwide, making early detection and prediction crucial for preventive healthcare. This project implements a **machine learning solution** using **Logistic Regression** to predict the likelihood of heart disease in patients based on various clinical and demographic parameters.

### 🌟 Key Highlights

- **Predictive Healthcare**: Early detection system for heart disease risk assessment
- **High Accuracy**: Achieves 85%+ accuracy on test data
- **Real-world Application**: Based on authentic medical dataset with 303 patient records
- **Interpretable Model**: Logistic regression provides clear feature importance and probability scores
- **Complete Pipeline**: From data preprocessing to model deployment

### 🎯 Objectives

1. **Develop** a reliable machine learning model for heart disease prediction
2. **Analyze** the relationship between various medical factors and heart disease
3. **Create** an interpretable model that medical professionals can understand
4. **Provide** probability scores for risk assessment rather than just binary classification
5. **Demonstrate** the complete ML workflow from data exploration to model evaluation

## 🔬 Dataset Information

### 📊 Dataset Overview

| Attribute          | Value                             |
| ------------------ | --------------------------------- |
| **Total Records**  | 303 patients                      |
| **Features**       | 13 clinical/demographic variables |
| **Target Classes** | 2 (Heart Disease: Yes/No)         |
| **Missing Values** | None (Complete dataset)           |
| **File Format**    | CSV                               |
| **Data Quality**   | High-quality medical data         |

### 🏥 Target Distribution

- **Heart Disease Present (1)**: 165 patients (54.5%)
- **Heart Disease Absent (0)**: 138 patients (45.5%)
- **Balance**: Well-balanced dataset suitable for binary classification

### 📋 Feature Descriptions

| Feature      | Type        | Description                           | Clinical Significance             |
| ------------ | ----------- | ------------------------------------- | --------------------------------- |
| **age**      | Numerical   | Patient age (29-77 years)             | Risk increases with age           |
| **sex**      | Binary      | Gender (1=Male, 0=Female)             | Different risk patterns by gender |
| **cp**       | Categorical | Chest pain type (0-3)                 | Key symptom indicator             |
| **trestbps** | Numerical   | Resting blood pressure (mm Hg)        | Major cardiovascular risk factor  |
| **chol**     | Numerical   | Serum cholesterol (mg/dl)             | High levels increase risk         |
| **fbs**      | Binary      | Fasting blood sugar >120 mg/dl        | Diabetes indicator                |
| **restecg**  | Categorical | Resting ECG results (0-2)             | Heart electrical activity         |
| **thalach**  | Numerical   | Maximum heart rate achieved           | Exercise capacity indicator       |
| **exang**    | Binary      | Exercise induced angina               | Stress test result                |
| **oldpeak**  | Numerical   | ST depression induced by exercise     | ECG stress test measure           |
| **slope**    | Categorical | Slope of peak exercise ST segment     | Exercise test parameter           |
| **ca**       | Numerical   | Number of major vessels colored (0-3) | Coronary angiography result       |
| **thal**     | Categorical | Thalassemia type (1-3)                | Blood disorder indicator          |

## 🚀 Features

### ✨ Core Functionality

- **🔍 Data Exploration**: Comprehensive analysis of heart disease dataset
- **🧹 Data Preprocessing**: Handling of categorical variables and feature scaling
- **🤖 Model Training**: Logistic regression implementation with scikit-learn
- **📊 Model Evaluation**: Multiple metrics including accuracy, precision, recall
- **🎯 Prediction System**: Real-time heart disease risk assessment
- **📈 Visualization**: Data distribution and model performance plots

### 🛡️ Model Capabilities

- **Binary Classification**: Predicts presence/absence of heart disease
- **Probability Estimation**: Provides confidence scores for predictions
- **Feature Importance**: Identifies most significant risk factors
- **Cross-validation**: Robust model validation techniques
- **Interpretability**: Clear understanding of model decisions

## 🛠️ Technologies Used

### 🐍 Core Technologies

| Technology           | Purpose                        | Version |
| -------------------- | ------------------------------ | ------- |
| **Python**           | Primary programming language   | 3.7+    |
| **Pandas**           | Data manipulation and analysis | Latest  |
| **NumPy**            | Numerical computing            | Latest  |
| **Scikit-learn**     | Machine learning library       | Latest  |
| **Matplotlib**       | Data visualization             | Latest  |
| **Seaborn**          | Statistical visualization      | Latest  |
| **Jupyter Notebook** | Interactive development        | Latest  |

### 📦 Dependencies

```python
numpy>=1.19.0
pandas>=1.2.0
scikit-learn>=0.24.0
matplotlib>=3.3.0
seaborn>=0.11.0
jupyter>=1.0.0
```

## 📊 Model Performance

### 🎯 Performance Metrics

| Metric        | Training Data | Testing Data |
| ------------- | ------------- | ------------ |
| **Accuracy**  | ~85-90%       | ~85%+        |
| **Precision** | High          | Consistent   |
| **Recall**    | High          | Consistent   |
| **F1-Score**  | Balanced      | Stable       |

### 📈 Key Performance Indicators

- **✅ High Accuracy**: Consistent 85%+ accuracy across train/test splits
- **⚖️ Balanced Performance**: Good precision-recall balance
- **🎯 Generalization**: Minimal overfitting, stable test performance
- **🔄 Reproducibility**: Consistent results with random state control

## 🏗️ Project Structure

```
Logistic-Heart-Disease-Prediction/
├── 📊 heart_disease_data.csv           # Dataset file
├── 📓 Logistic-Heart-Disease-Prediction.ipynb  # Main notebook
├── 📖 README.md                        # This file
├── 📄 LICENSE                          # License information
└── 📁 docs/                           # Documentation
    ├── 📋 dataset.md                   # Dataset documentation
    └── 🤖 logistic-regression-model.md # Model documentation
```

### 📁 File Descriptions

- **`heart_disease_data.csv`**: Complete dataset with 303 patient records
- **`Logistic-Heart-Disease-Prediction.ipynb`**: Main Jupyter notebook with complete analysis
- **`docs/dataset.md`**: Detailed dataset documentation and feature descriptions
- **`docs/logistic-regression-model.md`**: Comprehensive model documentation
- **`README.md`**: Project overview and instructions
- **`LICENSE`**: License terms and conditions

## ⚙️ Installation & Setup

### 🔧 Prerequisites

- **Python 3.7+** installed on your system
- **Git** for version control
- **Jupyter Notebook** or **JupyterLab**
- **Code Editor** (VS Code, PyCharm, etc.)

### 📥 Quick Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/NhanPhamThanh-IT/Logistic-Heart-Disease-Prediction.git
   cd Logistic-Heart-Disease-Prediction
   ```

2. **Create Virtual Environment** (Recommended)

   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**

   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

5. **Open the Main Notebook**
   - Navigate to `Logistic-Heart-Disease-Prediction.ipynb`
   - Run all cells to see the complete analysis

## 📖 Usage

### 🚀 Quick Start

1. **Open the Jupyter Notebook**

   ```bash
   jupyter notebook Logistic-Heart-Disease-Prediction.ipynb
   ```

2. **Run the Complete Analysis**

   - Execute all cells in sequence
   - Observe data exploration, model training, and evaluation

3. **Make Predictions**

   ```python
   # Example prediction for a new patient
   input_data = (62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2)
   prediction = model.predict([input_data])

   if prediction[0] == 0:
       print('No Heart Disease Detected')
   else:
       print('Heart Disease Risk Detected')
   ```

### 🎯 Making Custom Predictions

To predict heart disease for a new patient, provide the following 13 features in order:

```python
# Feature order: age, sex, cp, trestbps, chol, fbs, restecg,
#                thalach, exang, oldpeak, slope, ca, thal

# Example: 62-year-old female with specific medical parameters
patient_data = (62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2)
risk_prediction = model.predict([patient_data])
confidence_score = model.predict_proba([patient_data])
```

## 🧪 Model Training Process

### 📊 Step-by-Step Workflow

1. **📥 Data Loading**

   - Load heart disease dataset from CSV
   - Initial data inspection and validation

2. **🔍 Exploratory Data Analysis**

   - Statistical summary of features
   - Target variable distribution analysis
   - Missing value assessment

3. **⚙️ Data Preprocessing**

   - Feature-target separation
   - Train-test split (80-20 ratio)
   - Stratified sampling for balanced splits

4. **🤖 Model Training**

   - Logistic Regression initialization
   - Model fitting on training data
   - Parameter optimization

5. **📈 Model Evaluation**

   - Training accuracy assessment
   - Testing accuracy evaluation
   - Performance metric calculation

6. **🎯 Prediction System**
   - Individual patient prediction
   - Probability score generation
   - Risk assessment interpretation

### 🎛️ Model Configuration

```python
# Model Parameters
model = LogisticRegression(
    random_state=42,        # Reproducibility
    max_iter=1000,         # Convergence assurance
    solver='liblinear'     # Optimal for small datasets
)

# Train-Test Split Configuration
X_train, X_test, Y_train, Y_test = train_test_split(
    X, Y,
    test_size=0.2,         # 20% for testing
    stratify=Y,            # Maintain class balance
    random_state=2         # Reproducible splits
)
```

## 📈 Results & Analysis

### 🎯 Model Performance Summary

- **✅ Training Accuracy**: ~85-90% (Indicates good learning)
- **✅ Testing Accuracy**: ~85%+ (Demonstrates generalization)
- **⚖️ Balanced Performance**: No significant overfitting
- **🎯 Consistent Results**: Stable across different random states

### 📊 Key Insights

1. **🫀 Age Factor**: Strong correlation with heart disease risk
2. **👥 Gender Differences**: Distinct risk patterns between males and females
3. **💓 Chest Pain**: Critical symptom for disease prediction
4. **🩺 Clinical Markers**: Blood pressure and cholesterol are significant predictors
5. **⚡ Exercise Metrics**: Heart rate and exercise capacity provide valuable insights

### 🔬 Feature Importance

The logistic regression model identifies the most significant factors:

- Chest pain type (cp)
- Maximum heart rate achieved (thalach)
- Exercise induced angina (exang)
- ST depression (oldpeak)
- Number of major vessels (ca)

## 🤝 Contributing

We welcome contributions to improve this heart disease prediction project!

### 🚀 How to Contribute

1. **🍴 Fork the Repository**

   ```bash
   git fork https://github.com/NhanPhamThanh-IT/Logistic-Heart-Disease-Prediction.git
   ```

2. **🌿 Create Feature Branch**

   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **💾 Commit Changes**

   ```bash
   git commit -m "Add amazing feature"
   ```

4. **📤 Push to Branch**

   ```bash
   git push origin feature/amazing-feature
   ```

5. **🔄 Open Pull Request**

### 🎯 Contribution Areas

- **🔬 Model Improvements**: Advanced algorithms, hyperparameter tuning
- **📊 Visualization**: Enhanced plots and charts
- **📖 Documentation**: Improve explanations and examples
- **🧪 Testing**: Add unit tests and validation
- **🌐 Web Interface**: Create user-friendly web application
- **📱 Mobile App**: Develop mobile prediction interface

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### 📋 License Summary

- ✅ **Commercial Use**: Allowed
- ✅ **Modification**: Allowed
- ✅ **Distribution**: Allowed
- ✅ **Private Use**: Allowed
- ❌ **Liability**: Limited
- ❌ **Warranty**: None

## 👨‍💻 Author

**Nhan Pham Thanh**

- 🐙 **GitHub**: [@NhanPhamThanh-IT](https://github.com/NhanPhamThanh-IT)
- 📧 **Email**: [Contact](mailto:your.email@example.com)
- 💼 **LinkedIn**: [Connect](https://linkedin.com/in/your-profile)
- 🌐 **Portfolio**: [Visit](https://your-portfolio.com)

---

<div align="center">

### 🌟 If you found this project helpful, please give it a star! ⭐

**Made with ❤️ for advancing healthcare through machine learning**

_"Predicting today for a healthier tomorrow"_

[![GitHub stars](https://img.shields.io/github/stars/NhanPhamThanh-IT/Logistic-Heart-Disease-Prediction?style=social)](https://github.com/NhanPhamThanh-IT/Logistic-Heart-Disease-Prediction/stargazers) [![GitHub forks](https://img.shields.io/github/forks/NhanPhamThanh-IT/Logistic-Heart-Disease-Prediction?style=social)](https://github.com/NhanPhamThanh-IT/Logistic-Heart-Disease-Prediction/network)

</div>

</div>
