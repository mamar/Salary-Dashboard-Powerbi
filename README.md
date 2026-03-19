# Power BI Salary & Consumer Insight Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-blue)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [KPIs Included](#kpis-included)
4. [Customer / Employee Segmentation](#customer--employee-segmentation)
5. [Visualizations Used](#visualizations-used)
6. [Tools & Technologies](#tools--technologies)
7. [How to Use](#how-to-use)
8. [Insights / Business Use Cases](#insights--business-use-cases)
9. [Future Enhancements](#future-enhancements)
10. [Visualizations Preview](#visualizations-preview)
11. [License](#license)

---

## Project Overview
This project is a **Power BI dashboard** designed to analyze employee and customer-related data.  
It provides actionable insights by tracking **key performance indicators (KPIs)**, segmenting behaviors, and visualizing trends across dimensions such as **job title, experience, skills, and location**.

![Power BI Salary Dashboard](Salary%20Dashboard.jpg)

The dashboard is particularly useful for:
- Understanding salary distribution
- Analyzing customer or employee behavior
- Supporting strategic decisions in HR, marketing, and business analytics

---

## Dataset
The dataset includes the following columns:

| Column            | Description                                     |
|------------------|-------------------------------------------------|
| `job_title`       | Role of the employee                            |
| `experience_years`| Years of experience                             |
| `education_level` | Highest education attained                      |
| `skills_count`    | Number of skills                                |
| `industry`        | Industry sector                                 |
| `company_size`    | Company size (Small/Medium/Large/Enterprise)   |
| `location`        | Country/location                                |
| `remote_work`     | Work type (Yes/No/Hybrid)                       |
| `certifications`  | Number of professional certifications          |
| `salary`          | Annual salary in USD                            |

Dataset file: [`job_salary_prediction_dataset.csv`](job_salary_prediction_dataset.csv)

---

## KPIs Included
The dashboard tracks the following **main KPIs**:
- **Average Salary** – Overall average salary for selected filters  
- **Highest / Lowest Salary** – Extreme values to identify outliers  
- **Total Employees** – Count of employees/customers  
- **Average Experience** – Workforce experience level  
- **Average Skills Count** – Measure of team capability  
- **Remote Worker Ratio** – Percentage of remote workers  
- **High Salary Ratio** – % of employees earning above 150K USD  

---

## Customer / Employee Segmentation
Segmentation is implemented based on:
- **Salary:** Low / Medium / High  
- **Experience:** Junior / Mid / Senior  
- **Skills Count:** Low / Medium / High  
- **Job Title & Industry:** For targeted insights  

This helps identify:
- High-value employees or customers  
- Trends across industries  
- Skill gaps or training opportunities  

---

## Visualizations Used
- **Bar Chart:** Salary distribution by Job Title / Industry  
- **Pie Chart:** Employee / Customer distribution across categories  
- **Scatter Plot:** Relationship between Experience, Skills, and Salary  
- **Box Plot:** Detect outliers and salary spread  
- **Line Chart / Time Series:** Trends in salary or activity over time  
- **KPI Cards:** Quick overview of key metrics  
- **Funnel Chart:** Customer or employee journey stages  

---

## Tools & Technologies
- **Power BI Desktop** – Dashboard development  
- **DAX (Data Analysis Expressions)** – KPI calculations  
- **SQL / CSV** – Data extraction and preparation  
- Optional: **Power BI Service** for dashboard sharing  

---

## How to Use
1. Open the **Power BI `.pbix` file** (`Salary Dashboard.pbix`)  
2. Connect to the dataset (`job_salary_prediction_dataset.csv`)  
3. Use filters for:
   - Job Title  
   - Industry  
   - Location  
   - Remote Work  
4. Explore KPI cards for quick insights  
5. Analyze trends and segments using the visualizations  

---

## Insights / Business Use Cases
- Identify **high-value employees or customers**  
- Understand **salary trends by experience and education**  
- Support **hiring, retention, and reward strategies**  
- Visualize employee or customer distribution by **location** or **remote work**  
- Detect gaps in **skills** and **training needs**  

---

## Future Enhancements
- Add **predictive analytics** to forecast salary or customer behavior  
- Integrate **real-time data** using APIs  
- Implement **Power BI alerts** for key KPI thresholds  

---

## Visualizations Preview
- **Bar Chart:** Salary by Job Title  
![Bar Chart](Salary%20Dashboard.jpg)  

- **KPI Cards Overview:**  
![KPI Cards](Salary%20Dashboard.jpg)  

> *(Replace with additional screenshots as needed for your portfolio)*

---

## License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
