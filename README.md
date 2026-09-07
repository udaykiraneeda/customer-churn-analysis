# Customer Churn Analysis

End-to-end analysis of telecom customer churn using **Python (Pandas)** for data cleaning, **Matplotlib/Seaborn** for exploratory data analysis, and **SQL (SQLite)** for aggregate querying.

## 📊 Dataset
Telco customer churn dataset — 7,043 customer records with features like contract type, tenure, monthly charges, and churn status.

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn (visualization)
- SQLite (SQL querying)
- Jupyter Notebook

## 🔍 Workflow
1. **Data Loading & Cleaning** — handled missing/invalid values, converted data types, removed non-predictive columns
2. **Exploratory Data Analysis** — visualized churn distribution, churn by contract type, tenure, and monthly charges
3. **SQL Analysis** — loaded cleaned data into SQLite and answered business questions using SQL queries
4. **Key Findings & Recommendations** — summarized actionable insights for the business

## 📈 Key Findings
- Overall churn rate: **26.58%**
- **Month-to-month contracts** have significantly higher churn than one/two-year contracts
- **Lower-tenure customers** (especially under 1 year) churn at a much higher rate
- Churned customers tend to have **higher average monthly charges**

## 💡 Business Recommendation
Prioritize retention offers (discounts, contract upgrade incentives) for month-to-month, low-tenure, high-monthly-charge customers, as this segment carries the highest churn risk.

## 📁 Files
- `customer_churn_analysis.ipynb` — full analysis notebook

## Author
Eeda Uday Kiran
[LinkedIn](https://linkedin.com/in/eeda-uday-kiran-72306a341) | [GitHub](https://github.com/udaykiraneeda)
