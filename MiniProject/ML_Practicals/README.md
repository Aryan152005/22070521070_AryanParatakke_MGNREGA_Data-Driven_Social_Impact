# Machine Learning Practicals - MGNREGA Data Analysis

This directory contains comprehensive Python files for different machine learning techniques using the MGNREGA dataset. Each file is structured with clearly separated code cells that can be easily copied and pasted into Jupyter notebooks.

## 📁 Files Overview

### 1. **01_Simple_Linear_Regression.py**
- **Objective**: Predict Total Expenditure based on Number of Workers
- **Key Techniques**: 
  - Simple linear regression
  - Correlation analysis
  - Outlier detection and treatment
  - Statistical significance testing
  - Model evaluation and visualization
- **Use Case**: Understanding the linear relationship between workers and expenditure

### 2. **02_Multiple_Linear_Regression.py**
- **Objective**: Predict Total Expenditure using multiple variables
- **Key Techniques**:
  - Multiple linear regression
  - Feature selection using VIF
  - Multicollinearity detection
  - Cross-validation
  - Feature importance analysis
- **Use Case**: Comprehensive expenditure prediction with multiple factors

### 3. **03_Backward_Elimination.py**
- **Objective**: Feature selection using statistical significance (p-value)
- **Key Techniques**:
  - Backward elimination algorithm
  - Statistical significance testing
  - Model optimization (AIC, Adjusted R²)
  - Step-by-step feature removal
- **Use Case**: Creating parsimonious models with only significant features

### 4. **04_Data_Preprocessing.py**
- **Objective**: Comprehensive data preprocessing techniques
- **Key Techniques**:
  - Missing value handling
  - Outlier detection and treatment
  - Feature scaling and normalization
  - Encoding categorical variables
  - Data transformation techniques
- **Use Case**: Preparing data for machine learning algorithms

### 5. **05_Clustering.py**
- **Objective**: Group districts/states by MGNREGA performance
- **Key Techniques**:
  - K-Means clustering
  - Hierarchical clustering
  - Elbow method for optimal clusters
  - Silhouette analysis
  - Cluster visualization
- **Use Case**: Identifying similar performing regions for targeted interventions

### 6. **06_Classification.py**
- **Objective**: Classify districts as High/Medium/Low performance
- **Key Techniques**:
  - Logistic Regression
  - Random Forest Classifier
  - Support Vector Machine (SVM)
  - Model comparison and evaluation
  - Confusion matrices and classification reports
- **Use Case**: Automated performance categorization for decision making

## 🚀 How to Use These Files

### Method 1: Copy-Paste to Jupyter Notebook
1. Open Jupyter Notebook/Lab
2. Create a new notebook
3. Copy each cell (marked with `# CELL X:`) from the Python files
4. Paste into separate notebook cells
5. Run each cell sequentially

### Method 2: Run as Python Scripts
1. Ensure you're in the ML_CA1 directory
2. Activate virtual environment: `venv\Scripts\activate`
3. Run: `python ML_Practicals/01_Simple_Linear_Regression.py`

## 📊 Dataset Information

- **Source**: MGNREGA (Mahatma Gandhi National Rural Employment Guarantee Act) data
- **Size**: ~302,000 records with 36 columns
- **Time Period**: 2018-2019 to 2023-2024 financial years
- **Key Variables**: Expenditure, Workers, Wages, Households, etc.

## 🔧 Prerequisites

Make sure you have the following packages installed in your virtual environment:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels scipy
```

## 📈 Expected Outcomes

Each practical will provide:
- **Comprehensive Analysis**: Detailed statistical analysis and visualizations
- **Business Insights**: Actionable recommendations based on findings
- **Model Performance**: Evaluation metrics and validation results
- **Professional Visualizations**: Publication-ready charts and graphs

## 🎯 Learning Objectives

After completing these practicals, you will understand:
- Linear regression techniques (simple and multiple)
- Feature selection methods (backward elimination)
- Data preprocessing best practices
- Unsupervised learning (clustering)
- Supervised learning (classification)
- Model evaluation and interpretation
- Business application of ML techniques

## 📝 Notes

- Each file is self-contained with proper documentation
- Code cells are clearly separated for easy notebook conversion
- All visualizations include proper titles, labels, and styling
- Business insights and recommendations are provided for each analysis
- Professional formatting with emojis and clear section headers

## 🔍 File Structure

```
ML_Practicals/
├── README.md                           # This file
├── 01_Simple_Linear_Regression.py      # Simple linear regression analysis
├── 02_Multiple_Linear_Regression.py    # Multiple linear regression analysis
├── 03_Backward_Elimination.py          # Backward elimination feature selection
├── 04_Data_Preprocessing.py            # Data preprocessing techniques
├── 05_Clustering.py                    # Clustering analysis
└── 06_Classification.py                # Classification analysis
```

## 🎓 Academic Use

These practicals are designed for:
- Machine Learning courses
- Data Science assignments
- Statistical analysis projects
- Government data analysis
- Social impact studies

Each file provides comprehensive analysis suitable for academic submissions with proper methodology, results, and conclusions.

---

**Happy Learning! 📚✨**

