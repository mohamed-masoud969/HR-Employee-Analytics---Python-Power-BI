# 📊 CRM Employee Dashboard - Power BI Project

![Show Project](https://app.powerbi.com/reportEmbed?reportId=9c8f6ada-ae08-4334-8c4f-b746f6b271d1&autoAuth=true&ctid=3c7a4dad-22f9-460f-9b04-70b4ea89f49f)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

## 📁 Overview

This project presents an interactive and professional **CRM Employee Dashboard** built using **Power BI** and **Power Query**.  
It aims to analyze employee data across multiple HR dimensions including demographics, performance, satisfaction, and training outcomes.

---

## 🎯 Objectives

- Analyze employee distribution and demographics.
- Monitor performance and satisfaction levels.
- Evaluate training participation and ROI.
- Provide executive recommendations based on data.

---

## 📄 Dashboard Structure (3 Pages)

### 🔹 Page 1: **Employee Overview**
- Total Active Employees
- Gender, Age Band, Race, Marital Status
- Department & Business Unit Distribution
- Years of Service Banding
- New Hire Trends

### 🔹 Page 2: **Performance & Satisfaction**
- Avg. Performance Score
- Avg. Satisfaction Score
- Work-Life Balance & Engagement
- Performance by Department
- Correlation with Years of Service

### 🔹 Page 3: **Training Analysis**
- Total Trained Employees
- Avg. Training Duration & Cost
- Training Type Distribution
- Satisfaction after Training
- Training Gap by Department

---

## 🧮 Key KPIs & Measures (DAX)

| KPI | Description |
|-----|-------------|
| `Avg Years of Service` | Calculates average tenure using `DATEDIFF` |
| `% Training Completed` | Measures successful training completions |
| `Avg Satisfaction After Training` | Focus on post-training satisfaction |
| `Employee Count by Status` | Dynamic count using slicers |
| `YoY % Change` | Time Intelligence via Calculation Group |

---

## 🗃️ Data Modeling

- Applied **Star Schema Design** using:
  - `FactEmployeeMetrics`
  - Dimension Tables: `DimJob`, `DimDate`, `DimTraining`, etc.
- Implemented relationships on keys like `Employee ID`, `Start Date`, and `Department`.

---

## 🧪 Power BI Techniques Used

- ✅ Power Query Data Transformation
- ✅ DAX Calculated Columns & Measures
- ✅ KPI Cards, Line/Bar/Donut Charts, Slicers
- ✅ Time Intelligence (YoY, Monthly Trends)
- ✅ Field Parameters & Calculation Groups
- ✅ Display Folders for organized measures

---

## 📈 Recommendations Derived

- Admin Offices department needs training and engagement focus.
- Long-tenured employees have higher performance and satisfaction.
- Current training programs need quality improvement, not just quantity.
- Communication Skills are overrepresented; diversify training content.

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `CRM_Employee_Dashboard.pbix` | Power BI dashboard file |
| `README.md` | This documentation |
| `Data_Sample.xlsx` | Sample anonymized data |
| `Report_Summary.pdf` | Final executive report |

---

## 🙌 Author

**Mohamed Masoud**  
Junior Data Analyst | Power BI Enthusiast  
📫 GitHub: [@mohamed-masoud969](https://github.com/mohamed-masoud969)

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).

---

## 💬 Feedback & Collaboration
Feel free to fork this repo, suggest improvements, or connect on LinkedIn.  
I’m always open to feedback and data-related collaboration!
