# 📊 Case Study 3: Palmoria HR Performance & Compensation Analysis

## 👤 Author  
**Adeniji Elijah Adetomiwa**  
Junior Data Analyst

## 📅 Submission Date  
**July 2025**

---

## 📌 Table of Contents
- [📄 Project Description](#project-description)
- [🗃️ Dataset Overview](#dataset-overview)
- [📈 Key Business Questions](#key-business-questions)
- [🛠️ Tools & Workflow](#tools--workflow)
- [📊 Dashboard Pages & Visuals](#dashboard-pages--visuals)
- [📥 Sample Files & Downloads](#sample-files--downloads)
- [🧠 Insights & Observations](#insights--observations)
- [💡 Strategic Recommendations](#strategic-recommendations)
- [📸 Sample Visuals](#sample-visuals)
- [📬 Connect with Me](#connect-with-me)

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
- Total Employees: 946
- Gender Split by Region and Department
- Donut Chart, Matrix Table, Filled Map

### 🟡 Page 2 – Compensation Overview
- Avg Salary: $74K
- Salary Compliance with $90K Threshold
- Gender Pay Gap Metrics
- Salary Bands by Department
- Funnel and Waterfall Charts

### 🟣 Page 3 – Performance & Ratings
- Avg Rating: 2.83
- Rating Distribution by Gender & Department
- Top Rated Employees
- Ratings by Region & Influencer Visual

### 🔴 Page 4 – Bonus Allocation
- Total Bonus Paid: $21,990
- Bonus Eligibility: 92% of Employees
- Bonus by Region, Department, Rating
- Top Earners & Compensation Totals
- Gauge and Waterfall Visuals

---

## 📥 Sample Files & Downloads

- 📁 [`PalmoraHR_Cleaned.xlsx`](datasets/PalmoraHR_Cleaned.xlsx)  
- 📁 [`BonusMatrix_Unpivoted.xlsx`](datasets/BonusMatrix_Unpivoted.xlsx)  
- 📊 [`HR_Analysis_Dashboard.pbix`](files/HR_Analysis_Dashboard.pbix)

---

## 🧠 Insights & Observations

### 🔵 Page 1 – Workforce Profile
- 👥 Palmoria employs 946 people across Lagos, Abuja, and Kaduna.
- ⚖️ Gender split is nearly balanced: 49% Male, 47% Female, 4% Undisclosed.
- 👩‍💼 Strong female presence in Legal, HR, and Marketing.
- 🧑‍💻 Engineering and Product remain male-dominated.
- 📍 Kaduna shows consistent gender balance; undisclosed gender highest in Services and R&D.

### 🟡 Page 2 – Compensation Overview
- 💵 Average salary is $74K; 69% earn below the $90K threshold.
- 📉 Gender pay gap of 3.55% (Men: $75K | Women: $72K).
- 📍 Kaduna shows the smallest pay gap; Marketing and Engineering show widest gaps.
- 🚫 Nearly 48% of underpaid employees are male, but 47.9% have undisclosed gender data.

### 🟣 Page 3 – Performance & Ratings
- 📊 Avg company rating is 2.83.
- 🧑‍🤝‍🧑 Males average 3.10 vs. females at 2.98; Services rate lowest at 2.73.
- 🏛️ Engineering holds the highest average score at 3.14.
- 🏅 90 employees are top-rated ("Very Good").
- 🌍 Ratings distributed evenly across Lagos, Kaduna, Abuja (≈ 33% each).

### 🔴 Page 4 – Bonus Allocation
- 💰 Total bonus paid: $21,990.
- ✅ 92% of employees received a bonus.
- 👑 Top earner: Cara Havers — over $8,200 in bonus.
- 📍 Kaduna & Abuja lead in bonus volume (36%+); Lagos received 26%.
- 🏛️ Training and Engineering departments lead in bonus share.

---

## 💡 Strategic Recommendations

### 🔵 Page 1 – Workforce Profile
- 📋 Standardize gender disclosure in HR records.
- 👩‍🔬 Promote women in Engineering and Product roles.
- 🔍 Conduct localized diversity audits by region.
- 🧼 Improve data hygiene to reduce “Undisclosed” fields.

### 🟡 Page 2 – Compensation Overview
- ⚖️ Prioritize equity reviews in Marketing, Engineering, Support.
- 📈 Adjust salaries for underpaid roles with consistent high ratings.
- 👀 Investigate departments with high pay gaps despite similar roles.
- 🧾 Make salary data completeness mandatory in HR processes.

### 🟣 Page 3 – Performance & Ratings
- 📏 Standardize rating rubrics across departments.
- 💬 Calibrate manager evaluations via feedback training.
- 🧑‍🎓 Model practices from high-performing Engineering teams.
- 👥 Promote peer recognition for female and underrepresented talent.

### 🔴 Page 4 – Bonus Allocation
- 🧭 Ensure Abuja & Kaduna bonus weights align with actual performance, not geography.
- 📊 Combine performance data with bonus visuals to reveal causality.
- 🏅 Spotlight high earners to drive engagement and fairness culture.
- ⚖️ Review location-based allocation strategy to encourage balance.

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

_Crafted with 💼 and 📊 using Power BI, DAX & storytelling flair._
