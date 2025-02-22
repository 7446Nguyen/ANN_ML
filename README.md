# Optimizing Classification for Cost-Sensitive Decision Making: A Deep Learning Approach

## Overview
This repository contains the final project for **DS 7333: Quantifying the World**, focusing on **cost-sensitive classification using Artificial Neural Networks (ANNs)**. The project aims to build a high-precision machine learning model that minimizes financial losses due to misclassification. The business requirement emphasizes that false positives are significantly more costly than false negatives, guiding the model selection, training, and evaluation.

## Contents
### 1. **Project Report**
- 📄 **Optimizing Classification for Cost-Sensitive Decision Making A Deep Learning Approach.pdf** – The final report detailing the dataset, preprocessing steps, model selection, architecture, training, evaluation, and results.
- The report outlines the financial impact of misclassification and how various ANN models were tuned to optimize precision and recall.

### 2. **Code Implementation**
- 📁 **Notebooks and Scripts** – Python and R scripts for data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.
- Key components:
  - Exploratory Data Analysis
    -📊 View the full EDA report here:  
    👉 [EDA Report]([https://7446Nguyen.github.io/QTW_ML_ANN/docs/ExploratoryDataAnalysis.html](https://htmlpreview.github.io/?https://raw.githubusercontent.com/7446Nguyen/QTW_ML_ANN/refs/heads/main/docs/ExploratoryDataAnalysis.html
)
  - **Data Preparation**:
    - Handling missing values, categorical encoding, feature transformations.
    - Different approaches to dataset modification (raw, imputed, and engineered features).
  - **Model Training & Evaluation**:
    - Logistic regression as a baseline.
    - Deep learning models implemented using TensorFlow/Keras.
    - ANN architectures with multiple layers, dropout layers, and hyperparameter tuning.
    - Model evaluation metrics: precision, recall, and financial cost minimization.

### 3. **Results & Findings**
- Multiple ANN models were tested with varying architectures.
- The **best-performing model** (Model 3) achieved the lowest monetary loss of **$57,270** by optimizing the classification threshold to 67%.
- Cross-validation confirmed model generalization.

## Technologies Used
- 🐍 **Python** (TensorFlow, Keras, NumPy, Pandas, Scikit-Learn, Matplotlib)
- 📊 **R** (tidyverse, caret, ggcorrplot)
- 💻 **Machine Learning & Deep Learning**
  - Logistic Regression
  - Random Forest
  - AdaBoost
  - Naive Bayes
  - KNN
  - SVM
  - Artificial Neural Networks (ANNs) with dropout layers

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/7446Nguyen/QTW_ML_ANN.git
   cd QTW_ML_ANN
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the **Python scripts** for model training and evaluation.

## Authors
- **David Shaw**
- **Jeff Nguyen**
- **David Julovich**

## Acknowledgments
This project was completed as part of **DS 7333: Quantifying the World** at Southern Methodist University's MSDS Program. Special thanks to our instructors and peers for valuable feedback.

---

Let me know if you'd like any modifications or additions! 🚀
