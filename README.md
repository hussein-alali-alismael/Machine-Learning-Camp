# Applied Machine Learning Camp

An Arabic-first, hands-on machine-learning camp that starts with Python foundations and progresses to a complete production-style ML pipeline.

The notebooks are designed for learning by doing: each session combines explanations, visual examples, exercises, and executable code.

Telegram Group: https://t.me/machinelearingcamp

## What you will learn

- Python fundamentals, functions, data structures, and clean coding
- NumPy arrays, vectorized thinking, broadcasting, and linear algebra
- Data cleaning and preparation with pandas
- Outlier handling, missing values, text normalization, and exploratory visualization
- Supervised learning: regression, evaluation metrics, and decision trees
- Classification with logistic regression and random forests
- Decision thresholds, precision, recall, and F1
- Unsupervised learning with K-Means clustering
- Feature engineering, cross-validation, model comparison, and artifact management
- Building an end-to-end customer-churn prediction system

## Sessions

| Session | Notebook | Main topics |
|---|---|---|
| 0 | [Python foundations review](Session%200/python_foundations_review.ipynb) | Python syntax, control flow, collections, functions, and practical exercises |
| 1 | [Python and NumPy](Session%201/day1_python_numpy.ipynb) | Advanced Python, NumPy, vectorization, and a neural layer from scratch |
| 2 | [Pandas and data cleaning](Session%202/day2_pandas_data_cleaning.ipynb) | Cleaning messy medical and telecom data, outliers, and visualization |
| 3 | [Supervised learning](Session%203/day3_supervised_learning.ipynb) | Regression, train/test splitting, scaling, metrics, and decision trees |
| 4 | [Classification and clustering](Session%204/day4_classification_clustering.ipynb) | Classification, threshold tuning, medical-risk prediction, and K-Means |
| 5 | [Graduation project](Session%205/day5_graduation_project.ipynb) | End-to-end customer-churn prediction and production artifact bundling |

## Graduation project

The final notebook builds an early-warning system for telecom customer churn:

1. Load and inspect raw customer data.
2. Clean inconsistent values and cap extreme outliers.
3. Engineer features such as support-ticket rate and payment ratios.
4. Scale features and create customer segments with K-Means.
5. Compare multiple classification models using stratified cross-validation.
6. Tune the decision threshold to prioritize recall for at-risk customers.
7. Build an executive visual dashboard.
8. Save the model, scaler, clustering model, and feature definitions together for reuse.

The final challenge applies the same workflow to a clinical heart-risk diagnosis dataset.

## Repository structure

```text
Machine Learning Camp/
├── Session 0/
│   └── python_foundations_review.ipynb
├── Session 1/
│   └── day1_python_numpy.ipynb
├── Session 2/
│   ├── day2_pandas_data_cleaning.ipynb
│   ├── dirty_medical_records.csv
│   ├── telecom_churn_dirty.csv
│   ├── X_day2.npy
│   └── y_day2.npy
├── Session 3/
│   └── day3_supervised_learning.ipynb
├── Session 4/
│   └── day4_classification_clustering.ipynb
├── Session 5/
│   └── day5_graduation_project.ipynb
└── README.md
```

## Getting started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd "Machine Learning Camp"
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**Windows PowerShell**

```powershell
.venv\Scripts\Activate.ps1
```

**macOS/Linux**

```bash
source .venv/bin/activate
```

### 3. Install the learning dependencies

```bash
python -m pip install numpy pandas matplotlib seaborn scikit-learn joblib jupyter
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open the sessions in order, starting with Session 0.

## Recommended prerequisites

- Basic computer usage and file management
- Basic algebra and statistics
- Python is helpful, but Session 0 is designed as a review and starting point

## Language

The instructional content is primarily in Arabic, with English technical terminology and code. This makes the material accessible to Arabic-speaking learners while keeping the workflow aligned with the wider Python and machine-learning ecosystem.

## Instructor

Prepared for the Applied Machine Learning Camp by **Eng. Hussein Alali Alismaeel**.

## License

This project is released under the [Personal Learning License](LICENSE).

Copyright (c) 2026 **Hussein Alali Alismaeel and Domains**. All rights reserved.

The material may be viewed and used for personal, non-commercial learning only.
Publication, redistribution, commercial use, modification, and derivative works
require prior written permission from both copyright holders.
