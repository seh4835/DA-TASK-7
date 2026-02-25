# DA TASK 7
# 📊 Statistical Business Analysis of Sales Performance and Customer Churn
## 📌 Project Overview

This project applies statistical methods to real-world business datasets to derive actionable insights on sales performance and customer churn. The analysis demonstrates an end-to-end statistical workflow, including descriptive statistics, distribution analysis, correlation analysis, hypothesis testing, confidence interval estimation, and regression modeling. The objective is to support data-driven decision-making for revenue optimization and customer retention strategies.

Datasets Used:

sales_data.csv – Transactional sales data (quantity, price, region, total sales).

customer_churn.csv – Customer attributes and churn indicators (tenure, charges, contract, churn status).

## 🎯 Objectives

Summarize sales performance using descriptive statistics.

Analyze data distributions and validate normality assumptions.

Identify relationships between key business variables using correlation analysis.

Test business hypotheses using inferential statistics (t-tests, ANOVA where applicable).

Estimate uncertainty using 95% confidence intervals.

Model revenue drivers using linear regression.

Translate statistical findings into practical business insights.

## 🧰 Tech Stack

Language: Python 3.8+

Libraries: pandas, numpy, matplotlib, seaborn, scipy, statsmodels

Environment: Jupyter Notebook

## 📁 Repository Structure
Statistical-Business-Analysis/
│
├── statistical_analysis.ipynb     # Main analysis notebook (Day 1–Day 7 workflow)

├── sales_data.csv                # Sales dataset

├── customer_churn.csv            # Customer churn dataset

├── statistical_report.pdf        # Detailed methodology and results report

├── hypothesis_tests_results.txt  # Hypothesis test outputs & interpretations

├── requirements.txt              # Python dependencies

└── README.md                     # Project documentation

## ⚙️ Setup Instructions

Clone the repository

git clone <your-repo-url>
cd Statistical-Business-Analysis

(Optional) Create and activate a virtual environment

python -m venv venv
venv\Scripts\activate   # Windows

Install dependencies

pip install -r requirements.txt

Launch Jupyter Notebook

jupyter notebook

Run the analysis

Open statistical_analysis.ipynb

Execute cells sequentially (Day 1 → Day 7)

## 🧪 Methodology

The notebook is structured into a 7-day analytical workflow:

Day 1 – Descriptive Statistics: Mean, median, mode, standard deviation

Day 2 – Distribution Analysis: Histograms and normality testing

Day 3 – Correlation Analysis: Pearson correlation and heatmap

Day 4 – Hypothesis Testing: One-sample t-test, independent t-tests (region, churn groups)

Day 5 – Confidence Intervals: 95% CI for mean sales

Day 6 – Regression Analysis: OLS regression (Total Sales ~ Quantity + Price)

Day 7 – Business Insights: Interpretation and actionable recommendations

## 📈 Key Outcomes

Identified key revenue drivers (quantity and price) using correlation and regression.

Assessed regional sales differences using hypothesis testing.

Quantified uncertainty around mean sales using confidence intervals.

Highlighted data quality considerations in churn analysis and their impact on statistical testing.

Translated statistical results into practical business recommendations.

## 🖼️ Visuals

The project includes visualizations such as:

Sales distribution histograms

Correlation heatmaps

Regression model summaries

## ✅ Reproducibility

All results are reproducible by:

Installing dependencies from requirements.txt

Running the notebook cells in order

Using the provided datasets without modification
