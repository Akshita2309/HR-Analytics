# 📊 HR Analytics Dashboard: Employee Attrition Insights

An interactive Power BI dashboard built to explore employee attrition across departments — uncovering who is leaving, why, and where the risk is highest.

## Short Description / Purpose

The HR Analytics Dashboard is a visually engaging and analytical Power BI report designed to help HR teams and business leaders understand employee attrition patterns across the Human Resources, Research & Development, and Sales departments. It highlights attrition by age, education, salary, tenure, and job role, giving decision-makers a fast, data-driven view of workforce turnover.

## Tech Stack

The dashboard was built using the following tools and technologies:<br>
- 📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
- 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
- 🧠 DAX (Data Analysis Expressions) – Used for calculated measures such as Attrition Rate, Average Income, and Years in Company.<br>
- 📝 Data Modeling – Relationships established between employee, department, and attrition tables to enable cross-filtering and aggregation.<br>
- 📁 File Format – .pbix for development and .png for dashboard previews.

## Data Source

Source: HR Employee Attrition dataset (employee-level records).

Data on ~1,470 employees across Human Resources, Research & Development, and Sales departments, including details on age, education, income, job role, salary slab, and years at the company.

## Features / Highlights

- **Business Problem**
Employee attrition is costly — replacing talent drains time, money, and institutional knowledge. Yet HR teams often lack a quick, visual way to answer questions like:
Which age groups and job roles are leaving the most?
Is attrition linked to salary level or tenure?
Which departments need retention strategies most urgently?

- **Goal of the Dashboard**
To deliver an interactive tool that:
Enables HR and leadership to explore attrition trends across departments.
Supports retention strategy and workforce planning decisions.
Uncovers patterns in age, education, income, and tenure linked to attrition.

- **Walkthrough of Key Visuals**
-	**Key KPIs (Top)**
Count of Employees: 1.47K
Attrition: 237
Attrition Rate: 16.12%
Average Age: 37
Average Income: 6.5K
Years in Company: 7.0
-	**Department Filter Panel**
Tabs let users filter the dashboard by Human Resources, Research & Development, or Sales.
-	**Attrition by Age & Gender (Stacked Bar)**
Splits attrited employees by gender (Male: 140, Female: 79) across age bands.
-	**Attrition by Education (Donut Chart)**
Breaks down attrition by education field — Life Sciences (38%), Medical (27%), Marketing (15%), Technical Degree (14%), Other (5%).
-	**Attrition by Age (Bar Chart)**
Shows attrition concentrated in the 26-35 age group (116), followed by 18-25 (44) and 36-45 (43).
-	**Job Role Breakdown Table**
A matrix of attrition counts by job role, broken out by rating/performance band (1–4) with row totals.
-	**Attrition by Salary Slab (Bar Chart)**
Shows attrition is highest among lower income brackets — Upto 5K (163) far exceeds higher salary slabs.
-	**Attrition by Years at Company (Area/Line Chart)**
Reveals a sharp attrition spike at year 1 (27), tapering off as tenure increases, with a smaller bump around year 9-10.
-	**Attrition by Job Role (Bar Chart)**
Laboratory Technician (62), Sales Executive (57), Research Scientist (47), and Sales Representative (33) show the highest attrition counts.

- **Business Impact & Insights**
**Retention Targeting:** HR can prioritize retention programs for early-tenure employees (year 1 spike) and lower-income bands, where attrition risk is highest.
**Role-Specific Strategy:** Roles like Laboratory Technician and Sales Executive can be flagged for exit interviews and engagement initiatives.
**Compensation Review:** The strong link between salary slab and attrition suggests reviewing pay bands for entry-level roles.
**Departmental Focus:** Leadership can compare attrition across HR, R&D, and Sales to allocate retention budgets where they're needed most.

## Screenshots / Demos

![Dashboard Preview](https://raw.githubusercontent.com/Akshita2309/HR-Analytics/main/HR%20Analytics%20Snapshot.png)
