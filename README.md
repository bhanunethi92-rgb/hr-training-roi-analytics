
# HR Training ROI & Skill Gap Intelligence Dashboard

## 📌 Project Overview
An end-to-end HR Analytics project analyzing whether employee training programs deliver measurable ROI, identifying skill gaps, and recommending Build vs Buy strategies for talent development.

## 🏢 Target Companies
Deloitte | Accenture | TCS | Infosys | Wipro

## ❓ Business Problem
- Is the company's training budget being spent effectively?
- Which departments deliver the best training ROI?
- Which employees are at skill gap risk?
- Should the company train internally or hire externally?

## 🔧 Tools Used
- Python (Pandas, Seaborn, Scikit-learn)
- SQL (SQLite)
- Power BI
- Jupyter Notebook
- GitHub

## 📊 Project Phases
| Phase | Description |
|-------|-------------|
| Phase 1 | Data Cleaning & Preparation |
| Phase 2 | Exploratory Data Analysis (7 insights) |
| Phase 3 | SQL Analysis (5 business queries) |
| Phase 4 | Training ROI + Build vs Buy Analysis |
| Phase 5 | Skill Gap Prediction (Random Forest) |
| Phase 6 | Power BI Dashboard (4 pages) |

## 💡 Key Findings
- More training ≠ better performance (correlation: 0.0-0.2)
- Employees with zero training have 27.78% attrition rate
- Sales department has highest training spend but lowest ROI
- HR department delivers highest ROI per training session
- Managers give best performance return per training
- 4 out of 5 skill gaps cheaper to fill internally than hiring

## 📁 Project structure
hr-training-roi-analytics/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_sql_analysis.ipynb
│   ├── 04_roi_analysis.ipynb
│   └── 05_skill_gap_model.ipynb
│
├── sql/
│   └── hr_queries.sql
│
├── dashboard/
│   ├── HR_Training_ROI_Dashboard.pbix
│   └── hr_analytics_data.xlsx
│
└── README.md
## 🎯 Business Recommendations
1. Reduce Sales training frequency — lowest ROI
2. Increase Manager training — highest performance per session
3. Ensure zero employees receive no training — highest attrition risk
4. Train internally for Data Analyst, Sales Manager, Research Scientist roles
5. Hire externally only for HR Specialist role
=======
# hr-training-roi-analytics
End-to-end HR Analytics project analyzing Training ROI, Skill Gap prediction and Build vs Buy recommendations using Python, SQL and Power BI

