# 📊 Panic Attack Data Analysis 

## 📌 Project Overview
This project analyzes **Panic Attack–related data** using **Microsoft Power BI** with **Snowflake** as the primary data source.  
The goal is to understand patterns, frequencies, and contributing factors through effective data modeling and visualization.

---

## ❄️ Data Source
- **Database**: Snowflake  
- Data queried using **Snowflake SQL**
- Structured datasets used for analytical reporting

---

## 🔍 Data Understanding & Preparation
- Data understanding and exploratory analysis
- Data transformation and cleaning using **Snowflake SQL**
- Handling null values and inconsistent records
- Creation of derived fields for better analysis

---

## 🔗 Snowflake to Power BI Integration
- Connected Snowflake to Power BI using native connector
- Optimized queries for efficient data refresh
- Imported transformed data into Power BI data model

---

## 📐 DAX Functions Used
- `IF()` – conditional logic  
- `SWITCH()` – category-based evaluation  
- `COUNTROWS()` – record counting  
- `FILTER()` – row-level filtering  
- `DIVIDE()` – safe division for ratio calculations  

---

## 🧮 Calculated Columns
- Created calculated columns to classify panic attack severity
- Derived indicators for analytical grouping and comparison

---

## 📊 Visualizations
- Designed a **four-page dashboard** (including titlepage)
- Created a dashboard page with the help of stacked bar chart for to get the count of **number of patients effected by different symptoms**.
- Created Multiple **clustered column charts** in single page for the analysis of average **Sleep Hour(SL)** ,**Panic Score(PS)** ,**Panic Attack Frequency(PAF)** for different categories of symptoms by age    groups.
- Interactive visuals for easy interpretation

---

## 📈 Key Insights
- Identification of high-frequency panic attack patterns
- Category-wise comparison using clustered visuals
- Clear understanding of contributing factors and distributions
- Data-driven insights to support mental health analysis

---

## 📸 Screenshots
### Snapshot of DAX expression used for Measures and Calculated Column
![image alt](https://github.com/prasannak2405/PowerBI_Dashboard_2/blob/290894f3fd95f25f548f026185b09965be5c9d7a/images/PA_M%26CC.png)

---

## 📁 Repository Contents
- Power BI report file (`.pbix`)
- PDF report
- Screenshots
- README.md

---

## ✅ Conclusion


This project demonstrates end-to-end analytics using **Snowflake and Power BI**, covering data extraction, transformation, modeling, and visualization to generate meaningful insights into panic attack data.
