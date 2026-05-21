# 🎓 Student Attrition & Academic Success Analysis (Tableau)

## 📌 Project Overview
This project features an interactive, 4-page Business Intelligence solution built using **Tableau** to analyze, track, and diagnose student attrition risks alongside academic success vectors. Designed for institutional leadership and student success teams, the dashboard breaks down historical academic records into a comprehensive narrative. By synthesizing demographic profiles, economic backgrounds, and multi-semester academic performance, this tool enables administrators to identify early-warning triggers and optimize retention frameworks.

## 🛠️ Tools & Technologies
* **BI Platform:** Tableau Desktop / Tableau Public
* **Data Dimension Slicing:** Demographics, Financial Aid Metrics, Parental Backgrounds, and Course Enrolment Types.
* **Dashboard Design:** Multi-page interactive tabs (Executive Dashboard, Demographics, Socio-Economic, Academic Performance).
* **Documentation:** Markdown

---

## 🔍 In-Depth Analytical Insights (From the Dashboard Pages)

### 📂 Page 1: Executive Dashboard (Cohort Overview)
* **High-Level Attrition Baseline:** Out of a total cohort of **4,424 students**, the institution achieves a **50.70% Graduation Rate (2,243 Graduates)**. However, a significant **32.12% Attrition Rate (1,421 Dropouts)** highlights a critical baseline requirement for targeted early intervention. Active student progression sits at **17.18% (760 Enrolled)**.
* **The Tuition & Scholarship Impact:** * The data reveals that **Scholarship Holders** have a vastly superior retention profile. Students backed by financial aid represent the lowest proportion of dropouts.
  * Delinquency in tuition payments is a definitive early indicator of student exit—maintaining up-to-date tuition payments is strongly correlated with graduation.

### 📂 Page 2: Demographic Insights
* **Gender & Marital Asymmetry:** When filtering the cohort by demographic variables, **male students exhibit a noticeably higher dropout rate** compared to their female peers. 
* **Age at Enrollment Risk:** The dashboard charts reveal that non-traditional, older students (enrolling at age 25+) carry a higher risk profile for dropping out compared to standard direct-from-school enrollments, likely due to balancing external adult responsibilities.

### 📂 Page 3: Socio-Economic Factors
* **Parental Background & Financial Nuances:** This page cross-references student completion rates with socio-economic background data (such as parental occupation and educational level). 
* **External Pressures:** The visualization demonstrates that students from families with lower-income occupational statuses or whose parents did not achieve higher education require higher levels of institutional onboarding and counseling support to achieve successful graduation.

### 📂 Page 4: Academic Performance (1st vs. 2nd Semester Trends)
* **The Credit Velocity Gap:** The core analytical visual contrasts **Semester 1 vs. Semester 2** metrics side-by-side, tracking Curricular Units Enrolled, Evaluated, and Approved.
* **The First-Year "Red Zone":** Dropouts show a steep, catastrophic drop-off in the number of *Approved Curricular Units* by the end of Semester 2, even if their Semester 1 enrollment numbers matched their peers. This highlights a clear operational window: students failing to secure credit approvals in their second semester must trigger automated academic alerts.

---

## 🏗️ Visual Architecture & Interaction Flow
The workbook is built with a uniform, executive layout featuring intuitive structural controls:
* **Central Navigation Tabs:** Left/Top-aligned navigation panels allowing users to seamlessly toggle between the **Executive, Demographic, Socio-Economic, and Academic** views.
* **Dynamic Slicers:** Universal, interactive filter panels controlling attributes like `Gender`, `Marital Status`, `Scholarship Holder (Yes/No)`, and `Tuition Fees Up to Date (Yes/No)`.
* **Comparative Visuals:** Dual-axis bar charts and horizontal distribution blocks tracking academic metrics and grade point averages (GPAs) simultaneously.

---
