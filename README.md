# 📊 Job Market Analytics Dashboard

*A Data Cleaning + Tableau Visualization Project*

---

## 🌟 Overview

This project explores global job-posting trends using Python for data cleaning and Tableau for interactive visualizations. It provides insights into salary distribution, company size patterns, geographic hiring trends, gender preferences, and work-type comparisons. The dashboard helps understand recruitment behavior across different countries, roles, and job categories.

---

## 🛠️ Tech Stack

* **Python:** Pandas, NumPy, Regex
* **Tableau Public:** Dashboard creation & interactive charts
* **HTML:** Embedded dashboard webpage
* **CSV Dataset:** Cleaned and transformed for analysis

---

## 🧹 Data Cleaning (Python)

The raw dataset included missing values, text-based salary fields, messy experience data, inconsistent country names, and irregular job titles.
Key processing steps included:

* Converting salary ranges into numeric format
* Extracting numeric experience using regex
* Creating filters (`Experience_Even`, `Valid_JobTitle`, `Posting_Month_Odd`)
* Validating countries and company names
* Exporting a cleaned dataset for Tableau

---

## 📊 Tableau Visualizations

Six interactive sheets were built according to specific task rules:

1. **Preference vs Work Type (Intern)** – Bar chart
2. **Company Size vs Company Name** – Scatter plot
3. **Top 10 Hiring Companies** – Treemap
4. **Global Job Posting Map** – Geographic distribution
5. **Work Type vs Preference** – Stacked bar chart
6. **Salary Distribution by Work Type** – Box-and-whisker plot

All charts were combined into a **single interactive Tableau dashboard**.

## 🌐 Live Dashboard

🔗 *Tableau Public Link:*
https://public.tableau.com/app/profile/bathula.sindhuja/viz/JobMarketAnalyticsDashboard/JobMarketAnalyticsDashboard

🔗 *Hosted Webpage:*
https://job-market-analytics-dashboard.netlify.app/

---

## 📌 Key Insights

* Salary ranges across work types are consistent
* Mechanical Engineer roles show strong demand in specific regions
* Top hiring companies dominate job volumes
* Gender preferences vary across job types
* Geographic distribution clearly shows active hiring clusters

---

## 👩‍💻 Author

Bathula Sindhuja
---
