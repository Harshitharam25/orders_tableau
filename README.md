# Oral Care Project Management Dashboard using Tableau

## 📌 Project Overview

This project presents an end-to-end **Project Management Dashboard** developed using **Tableau Desktop** and **Tableau Prep Builder**. The objective is to transform project planning and execution data into meaningful business insights through data preparation, visualization, and interactive dashboards.

The dashboard enables management to monitor the performance of IT and Marketing projects across multiple regions, identify project delays, analyze costs, and track deliverables against planned schedules.

---

## 🎯 Business Objective

The dashboard helps management answer key business questions such as:

- Which projects are exceeding their planned budget?
- Which projects are behind schedule?
- Which regions have the highest number of delayed projects?
- Are project deliverables being completed according to plan?
- Which project type (IT or Marketing) is performing better?
- Which projects require immediate management attention?
- Which regions have the highest project costs?

---

## 📂 Dataset

The project uses project management data consisting of the following worksheets:

- Projects_plans
- Project_type
- Actual_Costs
- Actual_Duration
- Actual_Delivrable
- Projects_Locations
- Country_Profiles

The datasets were cleaned, joined, and prepared using Tableau Prep before being imported into Tableau Desktop for visualization.

---

## 🛠️ Tools Used

- Tableau Desktop
- Tableau Prep Builder
- Microsoft Excel
- Hyper Extract (.hyper)
- Git & GitHub

---

## 🔄 Project Workflow

```
Raw Project Data
        ↓
Tableau Prep Builder
(Data Cleaning & Joins)
        ↓
Prepared Hyper Extract
        ↓
Tableau Desktop
        ↓
Interactive Dashboard
        ↓
Business Insights
```

---

## 📊 Dashboard Features

The dashboard provides insights into:

- 📈 Project Performance Overview
- 💰 Planned vs Actual Cost Analysis
- ⏳ Planned vs Actual Duration
- 📦 Planned vs Actual Deliverables
- 🌍 Regional Project Performance
- 🏢 IT vs Marketing Project Analysis
- 🚨 15% Performance Alert Monitoring
- 📅 Project Status Tracking

---

## 📊 Key Performance Indicators (KPIs)

The dashboard monitors:

- Total Projects
- Total Planned Cost
- Total Actual Cost
- Cost Variance (%)
- Planned Duration
- Actual Duration
- Duration Variance (%)
- Planned Deliverables
- Actual Deliverables
- Deliverable Variance (%)
- Projects with Alerts
- Projects On Track

---

## 🚨 Alert Logic

According to the business requirement, the dashboard automatically highlights projects whenever the difference between planned and actual values exceeds **15%** for:

- Project Cost
- Project Duration
- Project Deliverables

Projects exceeding the threshold are flagged as **Alert**, allowing management to quickly identify projects requiring attention.

---

## 📁 Repository Structure

```
Oral_Care_Project_Management_Dashboard/

│
├── Data/
│   ├── Données Sanitoral.xlsx
│   ├── Output.hyper
│
├── Tableau/
│   ├── Oral_Care_Dashboard.twb
│   ├── flow5.tfl
│
├── Dashboard/
│   ├── Executive_Dashboard.png
│   ├── Cost_Analysis.png
│   ├── Duration_Analysis.png
│   ├── Deliverables_Analysis.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 📸 Dashboard Preview

The dashboard contains interactive visualizations including:

- Executive Overview Dashboard
- Cost Performance Dashboard
- Duration Monitoring Dashboard
- Deliverables Tracking Dashboard
- Regional Performance Dashboard

Dashboard screenshots are available in the **Dashboard** folder.

---

## 🚀 How to Use

1. Clone this repository.

```bash
git clone https://github.com/yourusername/Oral_Care_Project_Management_Dashboard.git
```

2. Open the Tableau workbook (`.twb`) using Tableau Desktop.

3. If prompted, reconnect the workbook to the **Output.hyper** file or the original Excel workbook.

4. Explore the interactive dashboard using filters for:

- Region
- Country
- Project Type
- Project
- Phase

---

## 📈 Key Business Insights

The dashboard enables users to:

- Monitor project performance across four regions.
- Compare planned and actual project costs.
- Track project schedule adherence.
- Monitor deliverable completion rates.
- Identify projects requiring management intervention.
- Compare IT and Marketing project performance.
- Support strategic project management decisions.

---

## 📌 Future Enhancements

- Publish the dashboard to Tableau Public or Tableau Cloud.
- Add advanced dashboard actions and drill-down navigation.
- Connect to a live project management database.
- Add predictive analytics and project forecasting.
- Integrate real-time project monitoring.

---

## 👨‍💻 Author

**HARSHITHARAM**

MSc Data Science & Business Analysis

EDC Paris Business School

---

⭐ If you found this project useful, consider giving it a star!
