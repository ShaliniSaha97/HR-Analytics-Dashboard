# 💼 HR Analytics Dashboard — Power BI

> A professional, multi-page **HR Analytics Dashboard** built in **Microsoft Power BI** to visualize workforce data, analyze salary trends, monitor employee tenure, and derive actionable HR insights.


---

## 🖥️ Dashboard Preview


### Page 1 — HR Analytics Overview

<img width="1326" height="780" alt="HR Analytics Dashboard - Overview" src="https://github.com/user-attachments/assets/7d6ad598-0b28-4a1f-b135-8e58521e5fc7" />



### Page 2 — Salary & Workforce Analysis

<img width="1321" height="781" alt="Salary Workforce Analysis" src="https://github.com/user-attachments/assets/38c9d4de-7c53-452a-b99d-31c33cc471fa" />


---


## 🌟 Project Highlights

- 🏢 **Total Employees:** 161 across multiple departments and job titles
- 💰 **Average Salary:** ₹54.23K with detailed role-wise breakdown
- 📅 **Average Age:** 35 years | Average Tenure: 6 years
- 🏖️ **Total Leave Balance:** 3K tracked across genders
- 📈 wo-Page Interactive Dashboard with slicers and filters

---


## 📋 Table of Contents


- Project Overview
- Dashboard Pages
- Key Metrics & KPIs
- Key Insights
- Recommendations
- Tools & Skills Used
- Data Fields
- Project Files
- How to Use
- About the Author
---


## 📌 Project Overview

This **HR Analytics Dashboard** was built as a complete end-to-end Power BI project to help HR managers and business leaders:

- Monitor **workforce composition** across gender, age group, and education
- Analyze **salary distribution** by job title and gender
- Understand **hiring trends** and **tenure patterns**
- Identify key **retention risks** and areas for policy improvement

The dashboard is structured across **two pages,** each serving a distinct analytical purpose — an operational overview and a deep-dive salary & workforce study.

---

## 📂 Dashboard Pages

### 🔷 Page 1 — HR Analytics Overview

The main operational dashboard featuring:

| Visual | Description |
|--------|-------------|
| **KPI Cards** | Total Employees, Avg Salary, Avg Age, Avg Tenure, Total Leave Balance |
| **Avg Salary by Job Title** | Horizontal bar chart ranking roles from highest to lowest pay |
| **Joining Trend by Month** | Line chart tracking monthly hiring activity across the year |
| **Tenure Analysis** | Bar chart showing employee count distribution across tenure years |
| **Employees by Age Group** | Treemap segmenting the workforce into age brackets (26–30, 31–35, 36–40, 41+) |
| **Education Qualification Distribution** | Bar chart showing Bachelor's, High School, Diploma, and Master's holders |
| **Gender Donut Chart** | Visual split: 88 Male (54%) vs 73 Female (46%) |
| **Slicers** | Filter by Year of Join, Job Title, Education Qualification, Age Group |

---

### 🔶 Page 2 — Salary & Workforce Analysis

A deeper analytical view with gender-based comparisons:

| Visual | Description |
|--------|-------------|
| **Gender-wise Salary Table** | Cross-tab of Female vs Male avg salary for each job title |
| **Sum of Leave Balance by Gender** | Bar chart — Female: 1,395 vs Male: 1,248 |
| **Avg Salary by Employee Tenure** | Column chart showing salary progression from 3 to 9 years of tenure |
| **Key Insights Panel** | Auto-generated text summary of key findings |
| **Recommendations Panel** | Actionable HR strategy suggestions |

---

## 📊 Key Metrics & KPIs

| Metric | Value |
|--------|-------|
| Total Employees | **161** |
| Average Salary | **₹54,231** |
| Average Age | **35 years** |
| Average Tenure | **6 years** |
| Total Leave Balance | **3,000** |
| Male Employees | **88 (54.7%)** |
| Female Employees | **73 (45.3%)** |

### Salary by Job Title (Top 5)

| Job Title | Avg Salary |
|-----------|-----------|
| Product Manager | ₹82,825 |
| Research Scientist | ₹77,567 |
| Marketing Manager | ₹73,530 |
| Marketing Specialist | ₹62,170 |
| Research Analyst | ₹57,813 |

### Salary Growth by Tenure

| Tenure (Years) | Avg Salary |
|----------------|------------|
| 3 | ₹49K |
| 4 | ₹45K |
| 5 | ₹52K |
| 6 | ₹55K |
| 7 | ₹55K |
| 8 | ₹61K |
| 9 | ₹73K |

---

## 💡 Key Insights

From the **Key Insights** panel on Page 2:

- 🎂 **Highest employee concentration** is in the **31–35 age group**
- 📆 **September had the highest hiring activity** across all months
- 👨 **Male employees hold 45% of the workforce** (with a slight majority overall)
- 💼 **Top 3 roles contribute most** to total payroll costs
- 👩 **Female employees have slightly higher leave balances** than male counterparts
- 🕐 **Most employees remain with the company for 5–7 years**
- ⚠️ **Retention sharply declines after 8 years** of tenure
- 🎓 **Bachelor's degree holders dominate** the workforce (49 employees)

---

## ✅ Recommendations

From the **Recommendations** panel on Page 2:

1. 🔒 **Focus on retention after 8+ years of tenure** — introduce long-service rewards or growth paths
2. 📅 **Maintain hiring momentum in Q1 & Q4** — optimize recruitment cycles around peak months
3. 🎓 **Encourage higher education upskilling programs** — subsidize Master's-level education to raise workforce capability

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Usage |
|-------------|-------|
| **Microsoft Power BI Desktop** | Dashboard design and report building |
| **Power Query** | Data cleaning and transformation |
| **DAX (Data Analysis Expressions)** | KPI calculations (Avg Salary, Avg Age, Avg Tenure) |
| **Data Modeling** | Relationships between tables |
| **HR Analytics** | Domain knowledge for meaningful KPI selection |
| **Data Visualization** | Chart selection, layout, and color design |

---

## 🗃️ Data Fields

The dataset contains the following key columns:

| Field | Description |
|-------|-------------|
| `Employee_ID` | Unique identifier for each employee |
| `Gender` | Male / Female |
| `Age` | Employee age (used to derive Age Group) |
| `Job_Title` | Role/designation of the employee |
| `Salary` | Annual salary |
| `Tenure` | Years with the company |
| `Education` | Highest qualification (Bachelor's, Master's, Diploma, High School) |
| `Leave_Balance` | Remaining leave days |
| `Join_Month` | Month of joining the company |
| `Year_of_Join` | Year of joining |

---

## 📁 Project Files

```
📦 HR-Analytics-Dashboard-PowerBI

 ┣ 📊 HR_Analytics_Dashboard.pbix                         → Main Power BI dashboard file
 ┣ 🖼️ hr-overview.png                                     → Page 1 dashboard screenshot
 ┣ 🖼️ hr-salary.png                                        → Page 2 dashboard screenshot
 ┗ 📄 README.md                                           → Project documentation (this file)
```

---

## 🚀 How to Use

1. **Clone or download** this repository
   ```bash
   git clone https://github.com/your-username/HR-Analytics-Dashboard-PowerBI.git
   ```

2. **Open** the `HR_Analytics_Dashboard.pbix ` file in **Power BI Desktop**
   - Download Power BI Desktop free at: [powerbi.microsoft.com](https://powerbi.microsoft.com/desktop)

3. **Explore Page 1** — Use the slicers on the left to filter by:
   - Year of Join
   - Job Title
   - Education Qualification
   - Age Group

4. **Navigate to Page 2** — Click the "Page 2" tab at the bottom for salary and gender analysis

5. **Hover over charts** for detailed tooltips and drill-through data

---




## 👩‍💻 About the Author

**Shalini Saha**  
*Data Analyst | Power BI | Excel | SQL*

💬 Passionate about transforming raw HR data into meaningful workforce insights  
🔗 [LinkedIn](https://www.linkedin.com/in/shalini-saha-b127b428b/) | [GitHub](https://github.com/ShaliniSaha97/)


---

> ⭐ *If you found this project helpful or interesting, please consider starring the repository!*
>
> 📬 *Feel free to open an issue or reach out for feedback, collaboration, or questions.*



