# Case Study 3: Palmoria HR Performance & Compensation Analysis

## Author  
**Adeniji Elijah Adetomiwa**  
Junior Data Analyst

## Submission Date  
**July 2025**

---

## Table of Contents
- [Project Description](#project-description)
- [Dataset Overview](#dataset-overview)
- [Key Business Questions](#key-business-questions)
- [Tools & Workflow](#tools--workflow)
- [Dashboard Pages & Visuals](#dashboard-pages--visuals)
- [Insights & Observations](#insights--observations)
- [Connect with Me](#connect-with-me)

---

## Project Description

This HR analytics project was developed as a capstone deliverable for the **Digital SkillUp Africa (DSA)** training program. It simulates a real-world scenario where I served as a junior analyst for **Palmoria Group**, tasked with investigating HR trends, rating equity, compensation patterns, and bonus allocation strategy using Microsoft Power BI.

The dashboard is interactive, multi-layered, and designed to help management gain deeper insight into internal workforce dynamics.

---

## Dataset Overview

### 1. **Employee Dataset**
Contains employee-level records including:
- Name, Gender, Location, Department
- Salary, Performance Rating (Very Poor to Very Good)

[Employee Dataset](https://github.com/DataGuy-Eterniti/Palmoria-HR-Performance-Compensation-Analysis/blob/main/Palmoria%20Group%20emp-data.csv)

### 2. **Bonus Rules Dataset**
Bonus percentages vary by **Department + Rating**.
This dataset was unpivoted and mapped using composite keys to calculate conditional bonus payouts per employee.

[Bonus Rule Dataset](https://github.com/DataGuy-Eterniti/Palmoria-HR-Performance-Compensation-Analysis/blob/main/Palmoria%20Group%20Bonus%20Rules.xlsx)

---

## Key Business Questions

| Page | Questions Answered |
|------|--------------------|
| 1. Workforce Profile | What’s the gender and departmental spread across regions? |
| 2. Compensation Overview | How fairly are salaries distributed by gender and region? |
| 3. Performance & Ratings | Are ratings consistent across departments and demographics? |
| 4. Bonus Allocation | Who earned bonuses? Are payouts equitably distributed? |

---

## Tools & Workflow

- **Power BI Desktop** [Power BI](https://www.microsoft.com/en-us/download/details.aspx?id=5849)
  - Power Query: Data cleaning and transformation  
  - DAX: Custom measures and calculated columns  
  - Data modeling: Composite keys, many-to-one joins  
  - Visuals: KPIs, funnel, waterfall, filled maps, matrix, gauge

---

## Dashboard Pages & Visuals

### 🔵 Workforce Profile
- Total Employees: 946
- Gender Split by Region and Department
- Donut Chart, Matrix Table, Filled Map

![Palmora Analysis P1 Workforce Profile](https://github.com/user-attachments/assets/390d0ebb-d891-4332-b06b-9a2fcf823a3c)


### 🟡 Compensation Overview
- Avg Salary: $74K
- Salary Compliance with $90K Threshold
- Gender Pay Gap Metrics
- Salary Bands by Department
- Funnel and Waterfall Charts

![Palmora Ana P2 Salary equity and Compliance](https://github.com/user-attachments/assets/af6459e8-9619-403d-bbe8-22568b5c51eb)

![Palmora ana P2b Salary equity and compliance](https://github.com/user-attachments/assets/2d6357fe-27d6-4665-8ff2-d42d01f40c1f)


### 🟣 Performance & Ratings
- Avg Rating: 2.83
- Rating Distribution by Gender & Department
- Top Rated Employees
- Ratings by Region & Influencer Visual

![Palmora Performance and rating P3](https://github.com/user-attachments/assets/5018f819-f2af-4b0b-9134-8deb60f2b74c)

### 🔴 Bonus Allocation
- Total Bonus Paid: $21,990
- Bonus Eligibility: 92% of Employees
- Bonus by Region, Department, Rating
- Top Earners & Compensation Totals
- Gauge and Waterfall Visuals

![Palmora P4 Bonus  Compensation](https://github.com/user-attachments/assets/c0e752d6-3413-4d69-b925-2595d433050b)

![Kaduna Bonus Paid P4a](https://github.com/user-attachments/assets/1ab559a3-30d4-47bd-938c-fdd1b3625a7d)

![Abuja bonus paid p4b](https://github.com/user-attachments/assets/40fdee9b-e097-41a0-bed5-952c5e646618)


![Lagos bonus paid 4c](https://github.com/user-attachments/assets/ea61edc8-0ec6-4def-8416-75ec8302502c)

---

## Insights & Observations

### Insights
The **Workforce Profile** analysis reveals that **Palmoria employs 946 people** across **Lagos, Abuja, and Kaduna** and Gender split is nearly balanced: 49% Male, 47% Female, 4% Undisclosed with a strong female presence in Legal, HR, and Marketing. Also **Engineering and Product** remain male-dominated, Kaduna shows consistent gender balance; undisclosed gender highest in Services and R&D.

The **Compensation Overview** shows that **Average salary is $74K**; **69% earn below the $90K threshold**, Gender pay gap of 3.55% (Men: $75K | Women: $72K), Kaduna shows the smallest pay gap; Marketing and Engineering show widest gaps and nearly 48% of underpaid employees are male, but 47.9% have undisclosed gender data.

**Performance & Ratings analysis** is a testament that **Avg company rating is 2.83** with disposition into Males average 3.10 vs. females at 2.98; Services rate lowest at 2.73.
  - Engineering holds the highest average score at 3.14.
  - 90 employees are top-rated ("Very Good").
  - Ratings distributed evenly across Lagos, Kaduna, Abuja (≈ 33% each).

Finally the **Bonus Allocation** analysis 
  - The Total bonus paid: $21,990 and 92% of employees received a bonus with Top earner: Cara Havers — over $8,200 in bonus.
  - Kaduna & Abuja lead in bonus volume (36%+); Lagos received 26%.
  - Training and Engineering departments lead in bonus share.

---

## Strategic Recommendations

**According to the Workforce Profile** I recommend Standardization of gender disclosure in HR records, promotion of women in Engineering and Product roles, localized diversity audits by region should be conducted and improve data hygiene to reduce “Undisclosed” fields.

In addition **For Compensation Compliance** there should be prioritization of equity reviews in Marketing, Engineering, Support.
    - Adjust salaries for underpaid roles with consistent high ratings.
    - Investigate departments with high pay gaps despite similar roles.
    - Make salary data completeness mandatory in HR processes.

**Performance & Ratings** shows that the management need to:
- Standardize rating rubrics across departments.
- Calibrate manager evaluations via feedback training.
- Model practices from high-performing Engineering teams.
- Promote peer recognition for female and underrepresented talent.

Bonus Allocation
- Ensure Abuja & Kaduna bonus weights align with actual performance, not geography.
- Combine performance data with bonus visuals to reveal causality.
- Spotlight high earners to drive engagement and fairness culture.
- Review location-based allocation strategy to encourage balance.

---

## 📬 Connect with Me

- 📧 **Email**: [adenijielijah2003@gmail.com](mailto:adenijielijah2003@gmail.com)  
- 🌐 **Whatsapp**: [+2348080121362](+2348080121362)


---

_Crafted with 💼 and 📊 using Power BI, DAX & storytelling flair._
