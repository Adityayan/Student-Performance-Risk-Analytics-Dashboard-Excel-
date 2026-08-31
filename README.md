# Student-Performance-Risk-Analytics-Dashboard-Excel-

An Excel dashboard analysing 25,000+ student records to uncover which factors- study hours, attendance, study method, parental education — most influence academic performance, and to flag at-risk students for early intervention. Built using Pivot Tables, dynamic charts, Slicers, conditional formatting, and formula-driven risk scoring (IF/IFS, XLOOKUP) on top of a cleaned raw dataset.

## 📊 Project Overview

The Student Performance & Risk Analytics Dashboard is an interactive Excel project that analyses 25,000+ student records to understand what drives academic performance and flag students at risk of failing.

The dashboard turns raw student-level data into actionable insights through data cleaning, calculated risk metrics, pivot tables, and dynamic visualisations — helping identify which students need early intervention and which factors matter most.

## 🎯 Project Objectives
Identify the strongest drivers of academic performance — study hours, attendance, study method, parental education — and quantify their relationship to final scores.
Flag at-risk students using a formula-driven risk score based on attendance and grade thresholds.
Compare performance across subjects (math, science, English) to spot subject-specific weak points.
Analyse performance by school type and demographics to surface equity gaps worth investigating.
Examine the effectiveness of study methods (coaching, group study, online videos, textbook, notes) against outcomes.
Provide an interactive dashboard with slicers so a non-technical viewer can filter and explore without touching raw data.

##  🛠 Tools & Technologies Used
------------------------------------------------------------------------------------
|Tool                   |	Purpose                                                   |
|-----------------------|-----------------------------------------------------------|
|Microsoft Excel        |	Data cleaning, analysis, dashboard build                  |
|Pivot Tables	          | Aggregation by category (study method, school type, grade)|
|Pivot Charts           |	Visualisation of trends and comparisons                   |
|IF / IFS, XLOOKUP      |	Risk flagging and category lookups                        |
|Conditional Formatting |	Visual flagging of at-risk students                       |
|Slicers	              | Interactive filtering                                     |

## 📂 Dataset
**Total Records:** ~25,000 students
**Columns:** 16 — demographics (age, gender, school_type, parent_education), behavior (study_hours, attendance_percentage, internet_access, travel_time, extra_activities, study_method), and outcomes (math/science/english/overall score, final_grade)
**Data quality note:** raw data contained duplicate student_id entries, handled during cleaning — see Data Cleaning section below.

## 📈 Dashboard Features
**KPI Overview:** Average overall score, % of students flagged at-risk, overall pass rate.
**Performance by Study Method:** Average scores compared across coaching, group study, textbook, online videos, notes, mixed.
**Attendance vs. Score:** Relationship between attendance percentage and outcomes.
**Grade Distribution:** Breakdown of final grades (a–f) by school type and parental education.
**Risk Flag View:** Conditionally formatted table highlighting at-risk students.
**Interactive Filters:** Slicers for gender, school type, and study method.

## 📁 Project Structure
```
student-performance-dashboard/ 
│
├── 📁 Raw_data/
│   └── student_performance.csv
├── 📁 Dashboard/
│       └── student_performance_working.xlsx   # Main file: dashboard, pivot tables, cleaned data
│
├── 📁 Images/
│   ├── dashboard_preview.png                # Main dashboard screenshot
│   └── filtered_view.png                    # Example of slicers in use
│
├── README.md                                # This file
```

## 🚀 How to Use
```
1️⃣ Download or clone the repository 
2️⃣ Open student_performance_dashboard.xlsx 
3️⃣ Use the slicers on the Dashboard sheet to filter by gender, school type, or study method 
4️⃣ Explore the Risk Flag view to see which students are highlighted
```
## 📌 Future Improvements
- Rebuild the risk score with a weighted formula instead of a single threshold
- Add a Power BI version for richer interactivity
- Bring in a second term's data to test whether risk flags predict actual outcomes

## 👤 Author

Adityayan Bhardwaj, Data Analyst (Fresher) | M.Sc. Physics, transitioning into data analytics. Comfortable across Excel, SQL, Power BI/Tableau, and Python.

## ⚖️ License

Free to use and adapt for learning purposes, with credit to the original author.
