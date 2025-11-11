# Insurance-sales-analysis-project
Project on data analysis and data science exploring insurance sales via SQL/python analysis. Predictive model formed and Tableau dashboard.

# Insurance Sales Analysis & Predictive Model

**An end-to-end data project demonstrating analytics, forecasting, and data science.**

---

## Part 1: Data & Insights Analyst Dashboard

Identified key performance metrics and provide a forecast for business planning.

### Live Tableau Dashboard
You can view and interact with the full, live dashboard here:

**[https://public.tableau.com/app/profile/annamaria.benakova/viz/InsuranceSalesAnalysis_17628361290880/InsuranceSalesAnalysis](https://public.tableau.com/app/profile/annamaria.benakova/viz/InsuranceSalesAnalysis_17628361290880/InsuranceSalesAnalysis)**

![Screenshot of Tableau Dashboard](YOUR-SCREENSHOT-LINK-HERE) 
*(I'll show you how to add this screenshot in a moment)*

### Key Insights from the Dashboard:
* **Performance vs. Target:** All regions significantly exceeded their quarterly targets, with Region A showing the strongest performance at over 560% of its goal.
* **Top Products:** `SEDAN` and `HBACK` are the two most popular vehicle types, making up the vast majority of all policies.
* **Sales Forecast:** The time-series model predicts stable sales, fluctuating around the 990,000 premium level for the next 6 months.

---

## Part 2: Data Science Predictive Model

Machine learning model was built to predict the likelihood of a customer filing a claim.

* **Business Problem:** Help the business identify high-risk customers to manage risk and resources.
* **Model:** I used a **Random Forest Classifier** to predict if a customer would 'File a Claim' (Yes/No) based on their region, vehicle type, credit score, and vehicle age.
* **Result:** The model achieved **XX.X% Accuracy** *(Check your classification report for this number!)* in predicting claims.

---

## Technical Details

* **Tools Used:** Python (Pandas, Scikit-learn, Statsmodels), SQL (via SQLAlchemy), Tableau
* **Analysis:** You can see the full, commented Python code (including data cleaning, SQL queries, forecasting, and model building) in the `analysis.ipynb` notebook in this repository.
