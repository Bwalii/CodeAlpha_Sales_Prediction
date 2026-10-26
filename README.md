# Advertising Sales Prediction & Exploratory Data Analysis

A data science project performing exploratory data analysis (EDA) and statistical summary on advertising budget allocations (TV, Radio, Newspaper) and their impact on product sales across 200 markets.

---

## 📌 Project Overview

This project analyzes how promotional investments across different marketing channels correlate with overall sales. Using descriptive statistics and regression modeling, the analysis evaluates the relative return on investment (ROI) for **TV**, **Radio**, and **Newspaper** advertising.

### Key Objectives
- Perform statistical summary and distribution analysis across all feature variables.
- Detect skewness and outliers across media spending channels.
- Evaluate channel efficiency to guide optimal marketing budget allocation.

---

## 📊 Summary Statistics Insights

Based on 200 observation markets, the primary summary statistics reveal:

* **TV Advertising:** Dominates marketing budgets with an average spend of **\$147.04k** (ranging from \$0.70k to \$296.40k).
* **Radio Advertising:** Maintains a moderate and consistent allocation averaging **\$23.26k** (max \$49.60k).
* **Newspaper Advertising:** Shows a right-skewed distribution where 75% of markets spend **\$45.10k or less**, despite extreme outlier spending up to **\$114.00k**.
* **Sales Output:** Averages **14.02k units** with a standard deviation of **5.22k units**.

---

## 🛠 Tech Stack & Tools

* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning / Analytics:** `scikit-learn`
* **Environment:** Jupyter Notebook / VS Code

---

## 📁 Repository Structure

```text
├── data/
│   └── Advertising.csv       # Dataset containing TV, Radio, Newspaper, and Sales
├── notebooks/
│   └── eda_sales_analysis.ipynb  # Exploratory Data Analysis & Modeling
├── src/
│   └── data_preprocessing.py # Utility scripts for data cleaning
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies
