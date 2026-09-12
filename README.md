# Personal Finance Behavior Dashboard 📊

A data analysis and visualization project exploring personal finance behavior across 500 records. This project includes data cleaning, exploratory data analysis (EDA), and an interactive dashboard built with Plotly.

##  Live Dashboard
You can view the interactive dashboard here:  
**[Click to open the Live Dashboard](https://DoniaHabib1.github.io/personal-finance-dashboard/dashboard/finance_dashboard.html)**

##  Dataset
The dataset contains 500 records (stratified sample) with features including Monthly Income, Expense, Savings Rate, Credit Score, Debt-to-Income Ratio, and Financial Stress Level.

**[Download the Dataset (CSV)](https://raw.githubusercontent.com/DoniaHabib1/personal-finance-dashboard/main/data/cleaned_personal_finance.csv)**

## 🗂 Project Structure
- `data/`: Contains the cleaned dataset (`cleaned_personal_finance.csv`).
- `notebook/`: Jupyter Notebook with the full data cleaning and analysis pipeline (`personal_finance_analysis.ipynb`).
- `dashboard/`: Interactive HTML dashboard built with Plotly (`finance_dashboard.html`).

##  Key Insights
1. **Savings rate is scenario-agnostic:** Average savings rate is nearly flat (~22%) across Normal, Inflation, and Recession scenarios.
2. **Freelancers out-save salaried earners:** Freelance income earners meet their savings goals more often (13.98%) compared to Salary (6.96%) and Mixed (3.23%).
3. **Credit score is a weak stress signal:** Correlation between credit score and financial stress is very low (~0.1).
4. **No single spending category dominates:** Expense-to-income ratios are evenly spread (77% - 96%), led by Utilities and Rent.
5. **Subscriptions don't predict spending:** Correlation between subscription count and discretionary spending is effectively zero.

##  Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn) for analysis.
- **Plotly** for the interactive dashboard.
- **HTML/CSS/JS** for rendering.

## 📂 How to Use
1. Clone the repo:
   ```bash
   git clone https://github.com/DoniaHabib1/personal-finance-dashboard.git
