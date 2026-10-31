# Breast Cancer Prediction Using Machine Learning

A machine learning-based binary classification project that predicts whether a breast tumour is **Benign or Malignant** using the Breast Cancer Wisconsin Diagnostic Dataset.

## Overview

Breast cancer is one of the most common forms of cancer worldwide. Early identification and accurate classification of suspicious tumours can support further medical examination and clinical decision-making.

This project explores supervised machine learning techniques to classify breast tumours based on numerical features extracted from digitised images of fine needle aspirates (FNA) of breast masses.

The project implements and compares multiple classification algorithms to understand their performance on a binary classification task.

**Note:** This is an educational machine learning project and is not intended for clinical diagnosis or medical decision-making.

## Dataset

The project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

- **Total samples:** 569
- **Input features:** 30 numerical features
- **Target classes:** 2
  - Benign (B)
  - Malignant (M)

The dataset contains measurements describing characteristics of cell nuclei, including:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

These measurements are represented through mean, standard error and worst-value features.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical computations |
| Pandas | Data manipulation and preprocessing |
| Matplotlib | Data visualisation |
| Seaborn | Exploratory data analysis |
| Scikit-learn | Machine learning algorithms and evaluation |
| PyTorch | Planned deep learning extension |

## Project Structure

```text
Breast_Cancer_Prediction/
│
├── Breast_Cancer_Prediction.ipynb   # Main Jupyter Notebook
├── data/                            # Dataset directory
│   └── data.csv                     # Breast cancer dataset
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies

## Machine Learning Models

The project implements and compares the following supervised learning algorithms:

1. **Logistic Regression** – A linear classification algorithm used for binary prediction.
2. **Decision Tree Classifier** – A tree-based algorithm that learns decision rules from input features.
3. **Random Forest Classifier** – An ensemble learning algorithm that combines multiple decision trees to improve predictive performance.

## Project Workflow

1. **Data Loading:** Load the Breast Cancer Wisconsin Diagnostic Dataset.
2. **Data Preprocessing:** Handle unnecessary columns, prepare features and encode the target variable.
3. **Exploratory Data Analysis:** Analyse feature distributions, correlations and relationships between variables.
4. **Feature Scaling:** Apply standardisation to numerical features.
5. **Model Training:** Train Logistic Regression, Decision Tree and Random Forest classifiers.
6. **Model Evaluation:** Compare model performance using classification metrics.
7. **Prediction:** Classify tumour samples into benign or malignant categories.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help assess classification performance and understand the trade-offs between false positive and false negative predictions.

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/hharshitarajoria/Breast_Cancer_Prediction
```

### 2. Navigate to the project directory

```bash
cd Breast_Cancer_Prediction
```

### 3. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells sequentially.

## Future Improvements

- Implement an Artificial Neural Network using PyTorch.
- Compare traditional machine learning models with deep learning approaches.
- Improve model evaluation using stratified cross-validation and hyperparameter tuning.
- Add model explainability techniques to understand feature contributions.
- Develop an interactive interface for exploring predictions.

## Project Status

**Current status:** Traditional machine learning implementation completed.

**Planned:** PyTorch-based deep learning implementation and comparative evaluation.

## Disclaimer

This project is developed for educational and research purposes only. Its predictions should not be interpreted as medical diagnoses or used as a substitute for professional medical advice.

## Dataset Reference

Breast Cancer Wisconsin (Diagnostic) Dataset:

[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

---

**Author:** Harshita

**Domain:** Machine Learning | Healthcare Analytics | Binary Classification
