# Case Study 3: Palmoria HR Performance & Compensation Analysis

## 👤 Author  
**Adeniji Elijah Adetomiwa**  
Junior Data Analyst

## Submission Date  
**July 2025**

---

## 📌 Table of Contents
- [📄 Project Description](#project-description)
- [🗃️ Dataset Overview](#dataset-overview)
- [📈 Key Business Questions](#key-business-questions)
- [🛠️ Tools & Workflow](#tools--workflow)
- [📊 Dashboard Pages & Visuals](#dashboard-pages--visuals)
- [📥 Files & Downloads](#sample-files--downloads)
- [🧠 Insights & Observations](#insights--observations)
- [💡 Strategic Recommendations](#strategic-recommendations)
- [📸 Sample Visuals](#sample-visuals)
- [📬 Connect with Me](#connect-with-me)
- [📄 License](#license)

---

## 📄 Project Description

This HR analytics project was developed as a capstone deliverable for the **Digital SkillUp Africa (DSA)** training program. It simulates a real-world scenario where I served as a junior analyst for **Palmoria Group**, tasked with investigating HR trends, rating equity, compensation patterns, and bonus allocation strategy using Microsoft Power BI.

The dashboard is interactive, multi-layered, and designed to help management gain deeper insight into internal workforce dynamics.

---

## 🗃️ Dataset Overview

### 1️⃣ **Employee Dataset (`PalmoraHR.xlsx`)**
Contains employee-level records including:
- Name, Gender, Location, Department
- Salary, Performance Rating (Very Poor to Very Good)

### 2️⃣ **Bonus Rules Dataset (`BonusMatrix.xlsx`)**
Bonus percentages vary by **Department + Rating**.
This dataset was unpivoted and mapped using composite keys to calculate conditional bonus payouts per employee.

---

## 📈 Key Business Questions

| Page | Questions Answered |
|------|--------------------|
| 1️⃣ Workforce Profile | What’s the gender and departmental spread across regions? |
| 2️⃣ Compensation Overview | How fairly are salaries distributed by gender and region? |
| 3️⃣ Performance & Ratings | Are ratings consistent across departments and demographics? |
| 4️⃣ Bonus Allocation | Who earned bonuses? Are payouts equitably distributed? |

---

## 🛠️ Tools & Workflow

- **Power BI Desktop**  
- Power Query: Data cleaning and transformation  
- DAX: Custom measures and calculated columns  
- Data modeling: Composite keys, many-to-one joins  
- Visuals: KPIs, funnel, waterfall, filled maps, matrix, gauge

---

## 📊 Dashboard Pages & Visuals

### 🔵 Page 1 – Workforce Profile
- Total Employees
- Gender Split by Region
- Donut Chart, Matrix Table, Filled Map

### 🟡 Page 2 – Compensation Overview
- Avg Salary
- Compliance with $90K Rule
- Gender Pay Gaps
- Salary Bands
- Funnel + Waterfall Charts

### 🟣 Page 3 – Performance & Ratings
- Avg Rating Company-wide
- Ratings by Gender/Department
- Matrix: Ratings by Dept × Gender
- Key Influencer Visual

### 🔴 Page 4 – Bonus Allocation
- Bonus Amounts & % of Eligible Employees
- Total Compensation (Salary + Bonus)
- Bonus by Department, Region, and Rating
- Top 5 Bonus Earners
- Gauge & Waterfall Visuals

---

## 📥 Files & Downloads

- 📁 [`PalmoraHR_Cleaned.xlsx`](datasets/PalmoraHR_Cleaned.xlsx)  
- 📁 [`BonusMatrix_Unpivoted.xlsx`](datasets/BonusMatrix_Unpivoted.xlsx)  
- 📊 [`HR_Analysis_Dashboard.pbix`](files/HR_Analysis_Dashboard.pbix)

---

## 🧠 Insights & Observations

- ⚠️ Over **25% of employees** earn below the company’s $90K salary benchmark
- 📉 **Gender-based performance rating gaps** appear in Engineering, Legal, and Sales
- 💰 **Highest bonuses** are concentrated in Product Management and R&D
- 📍 The **South region** received the largest bonus payouts, surpassing 30% of the total
- 🧮 Only **~82%** of employees received a bonus — mostly linked to “Good” or “Very Good” ratings

---

## 💡 Strategic Recommendations

- 🔍 Re-evaluate salary fairness in Support and Marketing teams
- 📏 Standardize performance review criteria across departments
- 🌍 Reassess regional bonus allocations relative to actual performance
- 🎯 Showcase Top Performers monthly to boost team morale and transparency
- 💼 Explore structured mentorship for low-performing departments

---

## 📸 Sample Visuals

| Page | Visual |
|------|--------|
| Workforce | ![Workforce View](images/workforce-profile.png) |
| Compensation | ![Salary Funnel](images/salary-compliance.png) |
| Ratings | ![Performance Matrix](images/performance-matrix.png) |
| Bonuses | ![Bonus Overview](images/bonus-summary.png) |

---

## 📬 Connect with Me

- 📧 **Email**: [adenijielijahad@gmail.com](mailto:adenijielijahad@gmail.com)  
- 💼 **LinkedIn**: [linkedin.com/in/adenijielijah](https://linkedin.com/in/adenijielijah)  
- 🌐 **Portfolio**: [elijahadetomiwa.github.io](https://elijahadetomiwa.github.io)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

_🧠 Built with DAX, Power BI, and a passion for data storytelling._

