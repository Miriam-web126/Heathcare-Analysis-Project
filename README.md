# 🏥 Health Dataset Analysis

This project involves cleaning, analyzing, and visualizing a healthcare dataset using Microsoft Excel. The goal is to extract insights on hospital admissions, treatment status, length of stay, and causes of death.

## 📁 Dataset Overview

The dataset contains the following columns:

- `Patient ID`
- `Patient Name`
- `Age`
- `Gender`
- `Hospital`
- `Admission Date`
- `Discharge Date`
- `Treatment Status`
- `Cause of Death`

A new column, `Days to Discharge`, was added to calculate the duration of each hospital stay using the `DATEDIF` function.

## 🧹 Data Cleaning

Cleaning steps performed in Excel:

- Removed duplicates
- Fixed inconsistent date formats
- Standardized categorical values (e.g., gender, treatment status)
- Handled missing data
- Calculated hospitalization length (`Days to Discharge`)

## 📊 Analysis

Key questions addressed:

- Which hospitals had the highest number of admissions?
- What are the most common treatment outcomes?
- What is the average length of stay by hospital?
- What are the most frequent causes of death?
- How does age relate to treatment status or mortality?

## 📈 Dashboard Features

An interactive Excel dashboard was built with:

- Pivot tables and pivot charts
- Slicers for filtering by hospital, gender, and treatment status
- Visuals showing:
  - Admissions per hospital
  - Treatment status distribution
  - Cause of death by demographic
  - Average days to discharge

## 🛠 Tools Used

- Microsoft Excel
  - Pivot Tables
  - Slicers
  - Charts
  - Formulas (e.g., `DATEDIF`, `COUNTIF`, `IF`)

## 💡 Insights

- Elderly patients had longer stays and higher mortality rates
- Some hospitals consistently showed longer discharge durations
- Most patients were successfully treated
- Gender distribution and causes of death varied across facilities

## 📌 Project Files


## 🚀 Future Work

- Rebuild the dashboard in Power BI
- Perform geospatial analysis if hospital locations are added
- Explore time series trends in admissions and discharges

## 🧑‍💻 Author

Miriam Nyangwara  
*Data Enthusiast | Nairobi, Kenya*

---

