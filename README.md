# Healthcare Data Analysis 🏥📊

A Power BI dashboard project analyzing hospital admissions, billing, and patient demographics to support data-driven decisions in cost management and patient care.

**Author:** Ann Mary Varghese · Data Analytics Batch

---

## 📌 Overview

Healthcare data plays a critical role in improving patient outcomes, optimizing operational efficiency, and reducing costs. This project analyzes over **55,500 patient admissions** to deliver insights into healthcare operations and financial performance — focusing on operational efficiency, revenue, and patient demographics, with trends in billing, insurance market share, and length of stay.

## 🗂️ Dataset

| Attribute | Detail |
|---|---|
| Total Records | 55,500 |
| Time Period | 2019 – 2024 |
| Institutions | Northwestern, UChicago, Loyola, UI Health |

**Key Data Pillars:**
- **Demographics:** Name, Age, Gender, Blood Type
- **Clinical:** Medical Condition, Medication, Test Results
- **Operational:** Admission/Discharge Dates, Length of Stay, Hospital, Doctor
- **Financial:** Billing Amount, Insurance Provider

The data was pre-processed to standardize insurance providers and clean patient names, ensuring high accuracy in the final dashboard.

## 📈 Visualization Techniques Used

- **Pie Chart** – proportional category comparisons
- **Donut Chart** – clean proportional view with space for key metrics
- **Line Chart** – trends over time
- **Bar Chart** – categorical comparisons
- **Treemap** – hierarchical proportions
- **Decomposition Tree** – root cause / drill-down analysis

## 🔑 Key Results

- **Flu** is the most frequent medical condition across the dataset
- **50.06%** of all diagnostic tests returned abnormal results
- Average patient age: **48 years**
- Average recovery time: **17.84 days**
- Total revenue generated: **$1.21 billion**
- **Emergency admissions** are the primary volume driver
- Root cause analysis (hospital → admission type → condition → test result) was used to identify bottlenecks and improve bed management

## 📊 Dashboard Pages

The Power BI report (`Healthcare_Data_Analysis.pbix`) includes four pages:
1. **Executive Summary** – patient count, avg. length of stay, total revenue, admission type breakdown
2. **Clinical Insights** – medical conditions, test results, length of stay by condition
3. **Financial Insights** – billing by admission type/condition, revenue heatmap by condition vs. insurance
4. **Operational Insights** – age/length of stay trends, root cause of patient volume, severity rate

## 📁 Repository Contents

```
├── Healthcare_Data_Analysis.pbix      # Power BI dashboard file
└── README.md
```

## 🛠️ How to Use

1. Download `Healthcare_Data_Analysis.pbix`
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Explore the four report pages using the navigation buttons on each page

## 📄 License

This project is shared for portfolio/educational purposes.
