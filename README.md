#  HR Attrition Analytics Dashboard  

A Power BI project that explores **employee attrition (turnover)** to uncover key factors, high-risk departments, and actionable insights to improve employee retention.  

![Welcome Page](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/Welcome%20Page.jpeg)

---

##  Project Overview  

This analysis provides a **data-driven understanding** of employee turnover patterns within the organization.  
It combines **Power Query data cleaning**, **interactive dashboards**, and **drill-down visualizations** to help HR teams identify and act upon attrition causes.

---

##  Data Cleaning & Preparation  

Performed in **Power Query (Power BI)** to ensure accuracy and consistency.  

**Key Transformation Steps:**
-  Removed duplicates & handled missing/null values  
-  Corrected data types (e.g., ensuring numeric fields were not stored as text)  
-  Created meaningful categorical **bins** for:
  - Age Groups → *Young Professionals*, *Mid-Career*, *Experienced*  
  - Income Ranges → *Low*, *Medium*, *High*  
  - Tenure Bins → *Early Tenure*, *Mid Tenure*, *Veterans*  
  - Job Satisfaction → *Low*, *Medium*, *High*, *Very High*  
  - Distance from Home → *Near*, *Mid Range*, *Far*  

---

##  Analytical Approach  

| Phase | Objective | Description |
|:------|:-----------|:------------|
| **Identification Phase** | Locate high-attrition departments | Identified which departments (Sales, HR, R&D) had the highest attrition rates using aggregated metrics and visuals. |
| **Investigation Phase** | Diagnose root causes | Explored job-related and demographic factors such as salary, tenure, job satisfaction, and distance from home. |
| **Insight Phase** | Translate findings into action | Derived HR-specific recommendations for improving retention and employee engagement. |

---

## 📊 Dashboard & Key Insights  

The Power BI report includes:  
 An **Overall Company Dashboard**  
**Department-level Dashboards** (Sales, HR, R&D)  
 An **Interactive Decomposition Tree** for root-cause analysis  

### 🔍 **Key Findings**  

![Key Insights](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/Key%20Insights.jpeg)

| Insight Category | Observation | Impact |
|:-----------------|:-------------|:--------|
|  **Departments** | Sales (20.63%) & HR (19.05%) have the highest attrition rates | Require targeted retention strategies |
|  **Demographics** | Younger, single employees with shorter tenures and lower salaries are more likely to leave | Indicates early-career disengagement |
|  **Work-Life Balance** | Employees living farther away and with low job satisfaction show higher turnover | Suggests need for hybrid/flexible options |

---

## Report Pages & Screenshots  

###  **1. Main Dashboard (Overall Company View)**  
Provides an overview of 1,470 employees and the overall attrition rate (16.12%).  
Includes KPIs, departmental treemap, and job role breakdown.

![Main Dashboard](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/Main%20Dashboard.jpeg)

---

### **2. Attrition Analysis (Decomposition Tree)**  
Interactive exploration of attrition rate by dimensions such as department, role, and satisfaction level.  
The **Sales → Sales Representative → Entry Level** path shows **42.11% attrition**, the highest risk group.

![Decomposition Tree](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/Decomposition%20Tree.jpeg)

---

###  **3. Sales Department Deep Dive**  
Department with the highest attrition (20.63%) among 446 employees.  
Explores patterns by age, satisfaction, and monthly income.

![Sales Dashboard - Page 1](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/Sales%20Dashboard%20-%20Page%201.jpeg)  
![Sales Dashboard - Page 2](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/Sales%20Dashboard%20-%20Page%202.jpeg)

---

###  **4. Research & Development Deep Dive**  
Largest department (961 employees) but relatively lower attrition (13.84%).  
Focuses on employee tenure and engagement levels.

![R&D Dashboard - Page 1](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/R%26D%20Dashboard%20-%20Page%201.jpeg)  
![R&D Dashboard - Page 2](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/R%26D%20Dashboard%20-%20Page%202.jpeg)

---

### **5. Human Resources Deep Dive**  
A smaller team (63 employees) yet second-highest attrition (19.05%).  
Explores satisfaction and promotion rates.

![HR Dashboard - Page 1](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/HR%20Dashboard%20-%20Page%201.jpeg)  
![HR Dashboard - Page 2](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/HR%20Dashboard%20-%20Page%202.jpeg)

---

##  Project File  

🔗 **Power BI File:** [`Data Cleaning.pbix`](https://github.com/HafzaBatool-ML/Powerbi-Employee-attrition-analysis/blob/main/Attrition%20Ananlysis/Data%20Cleaning.pbix)

---

##  Summary of KPIs  

| Metric | Value | Description |
|:--------|:------|:------------|
|  **Total Employees** | 1,470 | Company size analyzed |
|  **Overall Attrition Rate** | 16.12% | Percentage of employees who left |
|  **Highest Attrition Department** | Sales (20.63%) | Critical turnover zone |
|  **Second Highest Department** | Human Resources (19.05%) | Needs retention attention |
|  **Common Factor** | Low income & low satisfaction | Primary driver of exits |

---

## Recommendations  

-  **Flexible Work Options** — for employees living far from the office  
-  **Engagement Programs** — boost satisfaction among early-career staff  
-  **Compensation Review** — ensure pay equity and motivation  
-  **Career Development Plans** — improve retention through growth opportunities  

---

##  Author  

**Hafsa Batool**  
BS Mathematics | Namal University  
 *Mianwali, Pakistan*  
 *Power BI | Data Analytics | HR Insights*  

---

 *If you found this project insightful, give it a star on GitHub!*  
