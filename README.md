# 📊 Loan Default & Financial Risk Analytics Dashboard

An end-to-end data analysis project evaluating loan performance, applicant demographic risk profiles, and historical financial trends. Built using **Power BI**, **Power Query**, and **DAX**, this project transforms raw financial data into executive-ready interactive dashboards to support risk mitigation and underwriting strategies.

---

## 📸 Dashboard Screenshots

| 1. Loan Default Overview | 2. Demographics & Financial Profile | 3. Financial Risk Metrics |
| :---: | :---: | :---: |
| ("C:\Users\ASUS\Desktop\Visuals\P1.png") | ("C:\Users\ASUS\Desktop\Visuals\P2.png") | ("C:\Users\ASUS\Desktop\Visuals\P3.png") |

---

## 📌 Executive Summary

* **Default Drivers:** Unemployed applicants display the highest default rate (**3.39%**), whereas full-time employed applicants maintain the lowest risk profile (**2.36%**).
* **Portfolio Allocation:** Home loans represent the single largest total loan volume (**~$6.545M**), followed closely by Business and Education financing.
* **Credit Score Insights:** Higher credit score applicants account for significant total loan volume, with **Adults** and **Middle-Aged Adults** holding the largest concentration of high-tier credit allocations.
* **Trend Analysis:** YoY default rate changes experienced significant upward spikes in **2015 (+2.7%)** and **2018 (+1.9%)**, following major downturns in **2014 (-2.6%)** and **2017 (-2.8%)**.

---

## 🛠️ Tech Stack & Methodology

* **Data Cleaning & Transformation (Power Query):**
  * Handled missing values, standardized schema formats, and managed data types.
  * Created custom conditional groupings for dynamic **Age Brackets** (*Teen, Adults, Middle Age Adults, Senior Citizens*) and **Credit Score Bins** (*Low, Medium, High, Very Low*).
* **Data Modeling:**
  * Implemented a **Star Schema** with centralized fact tables for loan transactions connected to key dimension tables (Demographics, Employment, Time Intelligence).
* **Advanced Analytics (DAX):**
  * Implemented key measure logic for YoY Loan Amount Growth, YoY Default Loan Volatility, Median Calculations, and dynamic Default Rate percentages.
