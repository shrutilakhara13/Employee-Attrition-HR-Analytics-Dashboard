# Employee-Attrition-HR-Analytics-Dashboard
# 👩‍💼 Employee Attrition & HR Analytics Dashboard  

## 📊 Overview  
This Power BI dashboard provides an in-depth analysis of **employee attrition trends** using the IBM HR Analytics dataset.  
It identifies the key factors influencing employee turnover, such as department, age, education, and job satisfaction — enabling HR teams to take data-driven actions to improve retention and employee well-being.  

---

## 🧠 Key Insights  
- **Attrition Rate:** 16.1%  
- **Departments with Highest Attrition:** Sales and Research & Development  
- **Age Group Most Affected:** 30–40 years  
- **Average Monthly Income:** ₹6.5K (sample data)  
- **Average Job Satisfaction Score:** 2.73 / 4  
- **Average Work-Life Balance:** 2.76 / 4  

---

## 🧩 Dashboard Features  
- 📈 **KPI Cards** — Total Employees, Average Age, Monthly Income, and Attrition Rate  
- 🧭 **Demographic Insights** — Attrition by Gender, Age Group, and Education Field  
- 🏢 **Department & Role Trends** — Attrition by Department and Job Role  
- 💰 **Salary Analysis** — Monthly Income by Job Level & Attrition  
- 😊 **Employee Well-being Metrics** — Work-Life Balance and Job Satisfaction Gauges  
- 🔍 **Interactive Visuals** — Filter by role, department, and other factors  

---

## 🛠️ Tools & Skills Used  
- **Power BI Desktop** — Dashboard creation and visualization  
- **Power Query** — Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** — Calculated measures like Attrition Rate, Average Salary, and Satisfaction Scores  
- **Data Visualization** — Storytelling through interactive visuals  

---

## 🧮 Key DAX Measures  
```DAX
Attrition Rate =
DIVIDE(
    CALCULATE(COUNTROWS('WA_Fn-UseC_-HR-Employee-Attrition'),
        'WA_Fn-UseC_-HR-Employee-Attrition'[Attrition] = "Yes"),
    COUNTROWS('WA_Fn-UseC_-HR-Employee-Attrition')
)
