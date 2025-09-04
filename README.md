# HR Analytics Dashboard

## 📌 Overview
In this project, I used **Power BI** to create an interactive **HR Analytics Dashboard** that helps organizations track and analyze their workforce.  
The dashboard provides insights into employee demographics, performance, attrition, and satisfaction levels, enabling data-driven HR decisions.

---

## 📊 Dataset
The dataset contains employee information including:
- Demographics (age, gender, marital status, ethnicity)  
- Employment details (department, job role, tenure, business travel, overtime)  
- Performance metrics (satisfaction levels, ratings, work-life balance)  
- Attrition (active vs. inactive employees, attrition rate)  

---

## 📈 Dashboard Features

### 1. **Overview Page**
- Total Employees, Active Employees, Inactive Employees  
- Attrition Rate (%)  
- Employee Hiring Trends  
- Active Employees by Department & Job Role  

### 2. **Demographics Page**
- Employee distribution by **Age & Gender**  
- Employees by **Marital Status**  
- Employees by **Ethnicity and Average Salary**  
- Youngest & Oldest Employee indicators  

### 3. **Performance Tracker Page**
- Job Satisfaction, Environment Satisfaction, Relationship Satisfaction  
- Manager Ratings & Self Ratings  
- Work-Life Balance  
- Drill-through for individual employee performance tracking  

### 4. **Attrition Page**
- Attrition Rate by **Department & Job Role**  
- Attrition by **Business Travel Frequency**  
- Attrition by **Overtime Requirement**  
- Attrition by **Tenure** and **Hire Date**  

---

## 🔗 Data Modeling
- **Star Schema** with fact and dimension tables:  
  - FactPerformanceRating (performance, satisfaction, ratings)  
  - DimEmployee (employee info: age, department, travel, etc.)  
  - DimDate (hire date, attrition date, etc.)  
  - DimRatingLevel (rating categories)  
  - DimSatisfactionLevel (satisfaction categories)  
  - DimEducationLevel (education categories)  

This structured model ensures efficient queries, easy DAX calculations, and scalable reporting.

---

## 💡 Insights
- Majority of employees are in **Technology & Sales departments**.  
- Higher attrition rates occur in employees with **frequent travel** and **overtime requirements**.  
- **Job satisfaction and work-life balance** strongly impact attrition.  
- Age group **20-29** dominates the workforce.  

---

## 📷 Dashboard Preview
![HR Analytics Dashboard](your_cover_image_link_here)

---

## 🚀 Tools Used
- **Power BI** → Dashboard creation  
- **Power Query** → Data preparation  
- **DAX** → KPIs and measures  
