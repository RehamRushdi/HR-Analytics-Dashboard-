# 💼 HR Analytics Dashboard | Power BI Project

A professional, multi-page HR analytics dashboard built in Power BI to deliver strategic insights into employee demographics, performance, training effectiveness, and attrition patterns. This project was developed as the final task in the **Power BI Workshop by Qafza**, but it significantly exceeds the course expectations in terms of depth, design, and business value.

---

## 📊 Project Overview

This dashboard was created to transform a static HR dataset into a dynamic decision-support system for HR professionals and executives. Through the use of clean visuals, segmentation, and advanced DAX logic, it provides clarity and insight into workforce dynamics and business-critical metrics.

---

## 🎯 Business Goals

- Identify trends in employee performance, satisfaction, and engagement.
- Analyze workforce structure by demographics, pay zones, and employment types.
- Evaluate training effectiveness and cost distribution.
- Detect termination patterns and potential risk groups.
- Enable HR and leadership teams to make **data-driven decisions**.

---

## 📂 Dataset

- **Rows**: 2,845 employees
- **Key Columns**:
  - Demographics: `GenderCode`, `DOB`, `Age`, `MaritalDesc`, `RaceDesc`
  - Structure: `EmployeeType`, `EmployeeClassificationType`, `BusinessUnit`, `DepartmentType`, `Division`, `PayZone`
  - HR Metrics: `EmployeeStatus`, `Performance Score`, `Current Employee Rating`, `Engagement Score`, `Satisfaction Score`, `Work-Life Balance Score`
  - Training: `Training Program Name`, `Training Type`, `Training Outcome`, `Training Cost`, `Training Date`

---

## 🛠 Tools & Technologies

- **Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Power Query Editor (for data cleaning)**  

---

## 🗂 Dashboard Structure

The dashboard is organized into **4 interactive pages**, each with its own theme and slicers for drilling into insights:

### 1️⃣ HR Overview
> Summary KPIs, workforce distribution, gender & age analysis, termination rate, performance by gender

### 2️⃣ Employee Demographics
> Age brackets, marital status, race, employee classification, pay zone distribution by business unit

### 3️⃣ Performance & Engagement
> Deep dive into satisfaction, engagement, performance ratings by department, gender, and marital status

### 4️⃣ Training & Development
> Training types, outcomes, costs, durations, participation by program, time-based training trends

---

## 📈 Key Findings

- **Employee Status**:  
  - 86.4% of employees are active; 13.6% are terminated.
  - Termination is disproportionately higher in **temporary and contract classifications**.

- **Workforce Age**:  
  - Avg age is 49.  
  - Most employees fall into the **45–54** and **55+** brackets.
  - Highest termination % is in **55+** (40.8%) and **25–34** (17.3%) — possible retirement or early career dissatisfaction.

- **Gender & Department**:  
  - Female representation is slightly higher (55.8%).  
  - **Production** department employs the most people (987), followed by **IT/IS** (195).  
  - Executive Office has the lowest headcount but highest work-life balance scores.

- **Performance & Engagement**:  
  - Avg performance score = 3.0  
  - Engagement and satisfaction vary across departments — **Executive Office** shows consistently higher scores, while **Production** and **Sales SE** need attention.  
  - Work-Life Balance is strongest in **Admin Offices** and **Executive Office**.

- **Training Programs**:  
  - Training is almost equally split: 50.05% external, 49.95% internal.  
  - Top 3 most frequent programs: **Communication Skills**, **Project Management**, **Leadership Development**.  
  - However, ~25% of training outcomes are **incomplete** — suggesting follow-up or process gaps.

- **PayZone Analysis**:  
  - Most employees fall into **Zone B** and **Zone C** — mapped to mid-level salary bands.
  - Zone A employees are minimal and appear in lower-pay departments.
  - Custom DAX logic was used to assign numeric and salary-range equivalents.

---

## 🔍 Detailed Insights

### 💼 Employment Category vs Termination %
Using a combined column (`Employee Type + Classification Type`), a clear pattern emerged:
- Temporary and contract employees are **15–16% more likely to be terminated** than full-time permanent staff.
- A custom stacked bar visual shows this segmented by gender, revealing potential policy or fairness issues.

### 📉 Attrition by Age
- **55+ age group accounts for 41% of all terminations**, despite being only 25% of the workforce.
- The **25–34 group also shows high attrition**, possibly due to misalignment of expectations or lack of career development support.

### 🧠 Training Effectiveness
- Despite high participation in key programs, incomplete outcomes hover near **26%**, which raises concerns about training quality or tracking.
- **Average training cost per employee**: $559  
- **Leadership development** and **communication skills** training have highest attendance but mixed outcomes.

---

## 💡 Recommendations

1. **Improve training follow-up** to reduce incompletions and tie outcomes to performance improvements.
2. **Strengthen retention efforts** for employees under 34 and over 55 — these groups have the highest risk.
3. **Review engagement and satisfaction** in departments with high headcount but low scores (e.g., Production).
4. **Audit compensation structure** by comparing PayZone with department and performance levels.
5. **Incorporate exit interviews or surveys** to validate attrition assumptions with qualitative data.

---

## 📸 Dashboard Preview

![Power BI Dashboard](visuals/Overview.jpg)
![Power BI Dashboard](visuals/Employee_Demographics.jpg)
![Power BI Dashboard](visuals/Training_and_Development.jpg)
![Power BI Dashboard](visuals/Performance_and_Engagement.jpg)

---

## 🙋‍♀️ About Me

I'm Reham Mahmoud Rushdi — a data-driven problem solver with a growing passion for business intelligence and analytics.  
Let's connect on [LinkedIn](https://www.linkedin.com/in/your-profile) 🚀

---

