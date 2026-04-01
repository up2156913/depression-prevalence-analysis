# Depression Professional Dataset — IDTA Coursework

Intelligent Data and Text Analytics (IDTA) coursework involving comprehensive analysis of the [Depression Professional Dataset](https://www.kaggle.com/datasets/ikynahidwin/depression-professional-dataset/data) (N = 2,054 samples, 11 attributes).

## Dataset Overview

The dataset explores the relationship between mental health and various demographic, lifestyle, and work-related factors.

| Type | Attributes |
|---|---|
| **Numerical** | Age, Work Pressure, Job Satisfaction, Work Hours, Financial Stress |
| **Categorical** | Gender, Sleep Duration, Dietary Habits, Suicidal Thoughts, Family History, Depression |

## Tasks

| # | Task | Methods |
|---|---|---|
| 1 | **Descriptive Analytics** | Basic statistics for all attributes; 5 visualisations (box plot + 4 relationship plots) |
| 2 | **Classification** | Decision Tree, Random Forest, SVM — predicting Depression |
| 3 | **Regression** | Linear Regression, Random Forest Regressor — predicting Age |
| 4 | **Association Rule Mining** | Apriori algorithm with rule interpretation |
| 5 | **Clustering** | K-Means, Agglomerative Clustering with PCA visualisation |

## Project Structure

```
.
├── depression.ipynb          # Main analysis notebook
├── depression_data.csv      # Dataset (not tracked — download from Kaggle)
├── requirements.txt         # Python dependencies
└── README.md
```

## Setup

```bash
# Clone the repository
git clone https://github.com/up2156913/depression-prevalence-analysis
cd IDTA-Coursework

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook depression.ipynb
```

> **Note:** Download the dataset from [Kaggle](https://www.kaggle.com/datasets/ikynahidwin/depression-professional-dataset/data) and place the CSV file in the project root before running the notebook.

## Author

**Rasheed**
