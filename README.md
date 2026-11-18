# 🏥 Hospital Readmission Analytics Dashboard | Power BI

## 📌 Project Overview

This project focuses on analyzing hospital readmission patterns among diabetic patients using the **Diabetes 130-US Hospitals Dataset (1999–2008)**.

An interactive, multi-page Power BI dashboard was developed to explore patient demographics, hospital utilization, clinical characteristics, treatment patterns, and 30-day readmissions.

The objective is to transform raw healthcare data into meaningful insights that can help identify readmission patterns and potential areas for healthcare quality improvement.

## 🎯 Business Objectives

- Analyze 30-day hospital readmission patterns among diabetic patients.
- Understand the relationship between patient demographics and readmission outcomes.
- Examine hospital admission types, admission sources, and discharge patterns.
- Explore clinical indicators, medication-related patterns, and treatment characteristics.
- Identify patient groups and encounter characteristics associated with readmission.

## 📊 Dataset Information

| Attribute | Details |
|---|---|
| Dataset | Diabetes 130-US Hospitals |
| Source | UCI Machine Learning Repository |
| Time Period | 1999–2008 |
| Total Encounters | 101,766 |
| Unique Patients | 71,518 |
| Domain | Healthcare Analytics |
| Data Type | Structured Healthcare Data |

**Dataset Source:** [UCI Machine Learning Repository – Diabetes 130-US Hospitals](https://archive.ics.uci.edu/dataset/296/diabetes+130+us+hospitals+for+years+1999+2008)

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated measures and KPI development
- **Data Modeling** – Fact and dimension table design
- **Data Visualization** – Interactive charts, KPI cards, slicers, and analytical visuals

## 📈 Dashboard Pages

### 1. Executive Overview
Provides a high-level summary of hospital encounters, patient counts, readmission metrics, and key performance indicators.

### 2. Patient Demographics
Explores patient characteristics such as age group, gender, race, and their relationship with readmission outcomes.

### 3. Hospital Utilization
Analyzes admission types, admission sources, discharge destinations, length of stay, and prior healthcare utilization indicators.

### 4. Clinical & Treatment Analysis
Examines clinical indicators, glucose and A1C test results, medication-related patterns, and treatment characteristics.

### 5. Readmission Insights
Provides deeper analysis of readmission patterns using interactive analytical visuals, including Key Influencers and Decomposition Tree.

## 🔍 Key Findings

- **101,766** total hospital encounters were analyzed.
- **71,518** unique patients were represented in the dataset.
- **11,357 encounters** were classified as readmitted within 30 days.
- The encounter-based 30-day readmission rate was **11.16%**.
- **35,545 encounters** were classified as readmitted after 30 days.
- **54,864 encounters** were classified as not readmitted.
- Average length of hospital stay was approximately **4.4 days**.

## 📐 Key Performance Indicators (KPIs)

- Total Encounters
- Unique Patients
- 30-Day Readmissions
- 30-Day Readmission Rate
- Readmissions After 30 Days
- Not Readmitted Encounters
- Average Length of Stay

## 🧹 Data Preparation & Modeling

The project involved the following data preparation activities:

- Cleaned and transformed healthcare data using Power Query.
- Reviewed missing and unknown values.
- Preserved repeated patient encounters for encounter-level analysis.
- Created calculated columns to display missing glucose and A1C test results as "Not Measured".
- Developed a structured fact and dimension data model.
- Created DAX measures to calculate KPIs and readmission metrics.
- Validated readmission category counts against total encounters.

## 💡 Business Value

This dashboard provides an interactive way to explore historical hospital readmission patterns and patient characteristics.

It can support exploratory healthcare analytics by helping users:

- Identify patient groups with different readmission patterns.
- Understand hospital utilization trends.
- Explore associations between clinical indicators and readmission outcomes.
- Identify potential areas for further investigation and quality improvement.

## ⚠️ Data Limitations

- The dataset represents historical hospital encounters from 1999–2008 and should not be interpreted as current hospital performance.
- The 30-day readmission rate is calculated at the encounter level, not the unique-patient level.
- Missing clinical measurements are displayed as "Not Measured" rather than assumed to be normal.
- The dataset does not provide hospital identifiers suitable for hospital-level ranking.
- The analysis identifies associations and patterns; it does not establish causation.

## 🚀 How to Explore the Project

1. Download the `.pbix` Power BI report from this repository.
2. Open the file using Microsoft Power BI Desktop.
3. Explore the five report pages.
4. Use slicers and interactive visuals to investigate different readmission patterns.

## 👨‍💻 Author

**Power BI | Healthcare Data Analytics Project**

Developed as a portfolio project to demonstrate practical skills in data cleaning, data modeling, DAX calculations, interactive dashboard development, and analytical storytelling.

## 📜 Dataset Attribution

Dataset: Diabetes 130-US Hospitals for Years 1999–2008  
Source: UCI Machine Learning Repository  
License: CC BY 4.0

Please refer to the original dataset source for licensing and attribution details.
