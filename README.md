# 📊 Databel Customer Churn Analysis

End to end Excel analysis identifying why Databel, a telecom provider, is losing customers and what to do about it.

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Type](https://img.shields.io/badge/Type-Data%20Analysis%20%7C%20Dashboard-blue)

---

# 📌 Executive Summary

Databel, a telecom company, was losing a significant share of its customer base and needed to understand **why customers were leaving and which segments were most at risk**. This project analyzes a dataset of **6,687 customers**, of which **1,796 churned an overall churn rate of 26.9%.**

Using Microsoft Excel, the dataset was cleaned, transformed, and explored to uncover the demographic, behavioral, and contractual drivers behind churn. The analysis was then consolidated into an interactive Excel dashboard that lets stakeholders slice churn by state, contract type, age group, payment method, and data usage.

**Key finding:** Churn is heavily concentrated among **senior, month-to-month customers on unlimited data plans who barely use their data** a segment that is highly price-sensitive and easily lured away by competitor offers.

<img width="821" height="373" alt="Customer Churn Analysis Dashboard" src="https://github.com/user-attachments/assets/d2429268-a821-458b-95ec-18cb2d13aed7" />



---

# ❓ Business Problem

Databel's leadership noticed a steady decline in its subscriber base but lacked a clear, data backed explanation of the underlying causes. Without this insight, the company could not:

- Identify which customer segments were most likely to churn
- Prioritize retention efforts and budget effectively
- Understand whether churn was driven by price, service quality, competitors, or plan structure

**Objective:** Analyze Databel's customer data to identify the key drivers of churn and deliver clear, actionable, visual insights that the business team can use to reduce customer attrition.

---

# 🛠 Methodology

The analysis followed a structured, end-to-end workflow entirely in Excel:

1. **Data Formatting** – Standardized and formatted both raw data sheets (headers, data types, consistent labeling) to prepare them for analysis.
2. **Data Cleaning** – Identified and removed duplicate records to ensure each customer was represented once.
3. **Churn Calculation** – Calculated the overall churn rate and flagged churned vs. retained customers.
4. **Churn Reason Investigation** – Broke churn down by **Churn Category** (Competitor, Attitude, Dissatisfaction, Price, Other) and specific **Churn Reason** to find the leading causes.
5. **Churn Category Deep-Dive** – Analyzed each churn category further to understand its weight and drivers relative to total churn.
6. **Demographic Analysis** – Segmented churn by age group (Senior / Under 30 / Other), gender, and state to uncover which customer profiles churn most.
7. **Behavioral & Plan Analysis** – Examined churn against contract type, data plan (unlimited vs. limited), and average monthly data usage.
8. **Dashboard Design** – Built an interactive, multi-panel Excel dashboard (with slicers/filters) to let stakeholders explore the findings dynamically.

<img width="1536" height="1024" alt="DATA DIAGRAM" src="https://github.com/user-attachments/assets/e96a3325-5278-444a-ac63-559f421354ea" />


---

# 🧠 Skills Demonstrated

- **Data Cleaning & Preparation** – formatting, standardization, duplicate removal
- **Exploratory Data Analysis (EDA)** in Excel
- **Pivot Tables & Pivot Charts** for multi-dimensional churn breakdowns
- **Formulas & Functions** (e.g., COUNTIFS, SUMIFS, AVERAGEIFS) for churn rate and segment calculations
- **Data Visualization** – charts, conditional formatting, and KPI cards
- **Interactive Dashboard Design** – slicers, filters, and a unified single-view report
- **Business/Analytical Storytelling** – translating raw numbers into actionable insight

---

# 📈 Results

| Metric | Value |
|---|---|
| Total Customers | 6,687 |
| Churned Customers | 1,796 |
| **Overall Churn Rate** | **26.9%** |

### Key Insights

- **👴 Seniors churn at nearly double the rate of others** — Senior customers churn at **38.2%**, compared to **24.3%** for non-seniors.
- **📍 California has the highest churn rate** among all states, standing well above the national average, followed by states like OH, PA, MD, and NE.
- **📅 Contract type is the single strongest churn driver** — Month-to-Month customers churn at **46.3%**, versus **11.3%** for One-Year and just **2.8%** for Two-Year contracts. Customers on Two-Year plans are the most loyal segment by a wide margin.
- **📶 Low-usage customers on unlimited plans churn the most** — customers who use **less than 5GB** of data but are subscribed to an **unlimited data plan** churn at **~35%**, notably higher than low-usage customers on limited plans (~13%). This points to customers questioning the value of a plan they aren't using.
- **🏆 Competitor activity is the #1 named reason for leaving** — "Competitor made better offer" and "Competitor had better devices" together account for the largest share of named churn reasons, followed by dissatisfaction with support ("Attitude of support person") and pricing concerns.

<img width="410" height="300" alt="churn by age group" src="https://github.com/user-attachments/assets/e6bc01da-9165-46a1-be02-a77f903535c8" /> 

<img width="410" height="300" alt="Churn By Data usage" src="https://github.com/user-attachments/assets/1063a9c6-5952-4103-bb5f-3f184aeb5468" />





---

# 💡 Business Recommendations

1. **Incentivize contract upgrades.** Since Month-to-Month customers churn at over 16x the rate of Two-Year customers, offer targeted discounts, device upgrades, or loyalty perks to convert Month-to-Month subscribers to annual or two-year plans.
2. **Launch a senior retention program.** Given seniors churn at 38%+, create simplified plans, senior-specific support lines, and proactive check-ins for this segment before they consider leaving.
3. **Re-evaluate the unlimited data plan value proposition for low-usage customers.** Customers using under 5GB but paying for unlimited data are prime candidates for right-sizing outreach — offer a cheaper tier or bundle add-ons so they feel they're getting value, rather than losing them to a competitor's cheaper plan.
4. **Prioritize retention efforts in California and other high-churn states.** Investigate local market conditions (competitor presence, network quality, pricing) in CA, OH, PA, MD, and NE, and consider region-specific retention campaigns.
5. **Strengthen the competitive win-back strategy.** Since "competitor offers" and "competitor devices" are the leading named churn reasons, build a competitive intelligence process to track rival pricing/device promotions and respond with matching offers or exclusive perks for at-risk customers.
6. **Invest in customer support quality.** "Attitude of support person" is a recurring churn reason — coaching, quality monitoring, and support-satisfaction surveys could meaningfully reduce this category of churn.

---

# 📂 Project Contents

- `Customer_Churn_Analysis_Project_File.xlsx` — Full Excel workbook containing the cleaned dataset, pivot analysis, churn calculations, and interactive dashboard.

<!-- 📸 ADD SCREENSHOT HERE: Thumbnail/preview image of the workbook or dashboard for the repo -->

---

## 🧰 Tools Used

- Microsoft Excel (Data Cleaning, Pivot Tables, Formulas, Charts, Dashboard/Slicers)

---

# 👤 Author

**Muhammad Hassan** — Final-Year BSCS Student
Feel free to connect or reach out with feedback/questions.

<!-- 📸 ADD LINK/BADGES HERE: LinkedIn, portfolio, or email -->
