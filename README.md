# Credit-Card-Fraud-Detection-Analysis:
- Machine learning system for credit card fraud detection using multiple algorithms, SMOTE sampling, and comprehensive data analysis with interactive visualizations.

# Overview:
- This project implements an advanced fraud detection system for credit card transactions using machine learning techniques. The system addresses the critical challenge of identifying fraudulent transactions in highly imbalanced datasets, where fraud cases represent less than 0.2% of all transactions.

# Key Features:
- **Multiple ML Algorithms**: Logistic Regression, Random Forest, XGBoost, Neural Networks
- **Advanced Sampling Techniques**: SMOTE oversampling to handle class imbalance
- **Comprehensive Data Analysis**: Statistical analysis and feature importance evaluation
- **Interactive Visualizations**: Plotly-based dashboards and matplotlib charts
- **Performance Metrics**: ROC-AUC, Precision-Recall curves, F1-scores
- **Feature Engineering**: PCA analysis and correlation studies
- **Model Comparison**: Side-by-side evaluation of multiple algorithms

  # Dataset:
The project uses the **Credit Card Fraud Detection Dataset** from Kaggle:
- **Total Transactions**: 284,807
- **Fraudulent Transactions**: 492 (0.173%)
- **Features**: 30 (28 PCA-transformed + Time + Amount)
- **Target**: Binary classification (0: Normal, 1: Fraud)

  # Data Challenges Addressed:
- **Extreme Class Imbalance**: 99.83% normal vs 0.17% fraud transactions
- **Feature Privacy**: PCA-transformed features require specialized analysis
- **Temporal Patterns**: Time-based transaction analysis
- **Amount Variations**: Wide range of transaction amounts

# Prerequisites:
- Python 3.8 or higher
- Jupyter Notebook or Google Colab
- Git

# Setup Instructions:
**Clone the repository**
   ```bash
   git clone https://github.com/Alibek-07/Credit-Card-Fraud-Detection-Analysis.git
   cd Credit-Card-Fraud-Detection-Analysis

# Author:
**Alibek Dadajonov**  
GitHub: [Alibek-07](https://github.com/Alibek-07)

---

# License:
This project is open-source under the MIT License.

