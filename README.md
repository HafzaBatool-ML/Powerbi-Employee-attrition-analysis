# HR Attrition Analytics Dashboard

This Power BI project analyzes employee attrition (turnover) to identify key factors and high-risk departments. The goal is to provide actionable insights for the HR department to help improve employee retention.

![Welcome Page](Welcome%20Page.jpeg)

---

## Data Cleaning and Preparation

Before analysis, the raw data was cleaned and transformed using **Power Query** in Power BI. Key steps included:

* Handling missing or null values.
* Correcting data types (e.g., ensuring numerical columns were not stored as text).
* Removing duplicate entries.
* **Creating Bins (Groups):** To simplify analysis of continuous data, new categorical columns (bins) were created for:
    * **Age Groups** (e.g., 'Young Professionals', 'Mid Career', 'Experienced')
    * **Income Ranges** (e.g., 'Low Income', 'Medium Income', 'High Income')
    * **Tenure Bins** (e.g., 'Mid Tenure', 'Early Tenure', 'Veterans')
    * **Job Satisfaction Levels** (e.g., 'Low', 'Medium', 'High', 'Very High')
    * **Distance From Home** (e.g., 'Near', 'Mid range', 'Far')

---

## 📈 Dashboard & Key Insights

The final report includes an overall summary dashboard, detailed deep dives for each department, and an interactive decomposition tree to explore the root causes of attrition.

### Key Findings from the Analysis

![Key Insights](image_e8016d.jpg)

* **High-Risk Departments:** **Sales** (20.63%) and **Human Resources** (19.05%) departments experience the highest attrition rates.
* **Demographic Factors:** Employees who are **younger**, **single**, have **shorter tenures**, and **lower salaries** are more likely to leave.
* **Work-Life Factors:** Employees living **farther from the workplace** and those with **low job satisfaction** tend to show higher attrition.

---

##  Report Pages & Screenshots

Here is a breakdown of the different pages in the report.

### 1. Main Dashboard (Overall View)

This page provides a high-level summary of the entire company (1,470 employees) and the overall attrition rate (16.12%). It also features a treemap and charts showing attrition by department and job role.

![Main Dashboard](image_e7fdc8.jpg)

### 2. Attrition Analysis (Decomposition Tree)

This interactive visual breaks down the overall attrition rate. The analysis clearly shows that **Sales** > **Sales Representative** > **Entry Level** is the highest-risk path, with a 42.11% attrition rate for that specific group.

![Decomposition Tree](image_e80091.png)

### 3. Sales Department Deep Dive

As the department with the highest attrition (20.63%), this dashboard explores the specific factors for its 446 employees.

![Sales Dashboard - Page 1](image_e800d1.jpg)
![Sales Dashboard - Page 2](image_e800b4.jpg)

### 4. Research & Development Deep Dive

This department has the largest number of employees (961) but a relatively lower attrition rate (13.84%).

![R&D Dashboard - Page 1](image_e8012c.jpg)
![R&D Dashboard - Page 2](image_e800ee.jpg)

### 5. Human Resources Deep Dive

While a small department (63 employees), HR has the second-highest attrition rate at 19.05%.


![HR Dashboard - Page 1](image_e8010c.jpg)
![HR Dashboard - Page 2](image_e8014f.jpg)
