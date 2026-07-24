# 📊 HR Analytics EDA

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Phik](https://img.shields.io/badge/Phik-Correlation-green)

---

## 📌 Project Overview

This project presents a complete **Exploratory Data Analysis (EDA)** of the HR Analytics dataset.

The objective is to identify candidate characteristics associated with **job change intention** (`target = 1`) and demonstrate practical data analysis techniques using **Python**, **Pandas** and data visualization libraries.

---

## 🎯 Business Goal

Companies invest significant resources in employee training and recruitment.

Understanding **which candidates are more likely to leave for a new job** helps HR departments:

- reduce employee turnover;
- improve hiring strategies;
- optimize training investments;
- better understand workforce behavior.

---

## 📂 Dataset

The dataset contains information about job candidates, including:

- City Development Index
- Education Level
- Major Discipline
- Relevant Experience
- Years of Experience
- Company Type
- Company Size
- Training Hours
- Last Job Change

### Target

| Value | Description |
|-------:|-------------|
| 0 | Candidate is **not** looking for a new job |
| 1 | Candidate is looking for a new job |

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Phik
- Jupyter Notebook

---

## 📊 Analysis Performed

✔ Data overview

✔ Data types inspection

✔ Missing values analysis

✔ Target distribution analysis

✔ Categorical feature analysis

✔ Numerical feature analysis

✔ Feature grouping using `cut()` and `qcut()`

✔ Target Rate calculation

✔ Crosstab analysis

✔ Pivot Table analysis

✔ Phik correlation matrix

✔ Detailed relationship analysis

---

## 📈 Main Findings

- Candidates from **less developed cities** have a higher probability of looking for a new job.
- **Relevant work experience** is associated with job change intention.
- `experience` and `last_new_job` demonstrate noticeable relationships with the target.
- `training_hours` has only a weak relationship with the target.
- Phik correlation successfully identified the most informative features for further investigation.

---

## 📁 Project Structure

```text
hr-analytics-eda
│
├── data
│   ├── aug_train.csv
│   ├── aug_test.csv
│   └── sample_submission.csv
│
├── images
│
├── notebook
│   └── hr_analytics_eda.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/en1gma357/hr-analytics-eda.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook

```bash
jupyter notebook notebook/hr_analytics_eda.ipynb
```

---

## 📚 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Missing Value Analysis
- Feature Engineering
- Correlation Analysis
- Target Rate Analysis
- Statistical Summaries
- Data Visualization
- Business Insight Generation

---

## 📬 Author

**Mikhail**

Junior BI / Data Analyst

GitHub: https://github.com/en1gma357