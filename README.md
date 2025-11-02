# 🏏 Sportlytix  
**Data Quality Analysis of Baseball Player Performance (TrackMan Data)**  

---

## 📘 Overview  
**Sportlytix** is a data analysis project focused on cleaning, merging, and analyzing baseball player performance data.  
The goal is to ensure data accuracy, identify inconsistencies, and calculate meaningful insights such as **average exit velocity** for home and away teams.  

This project was created as part of a data quality assessment challenge using **TrackMan** data from a 2025 minor league regular-season game.  
It demonstrates strong skills in **data cleaning**, **data merging**, and **data analysis** using **Python and Pandas**.

---

## 🎯 Objective  
- Combine two separate datasets — **pitch-level data** and **contact-level data** — into a single, cleaned dataset.  
- Detect and correct multiple data errors and inconsistencies.  
- Calculate **average exit velocities** for both the home and away teams.  
- Visually represent outliers and summarize data quality findings.  

---

## 🧩 Dataset Description  
Two CSV files were provided as the data sources:

1. **BBOps_DQ_26FellowPitch.csv** – Contains all pitch-level details.  
2. **BBOps_DQ_26FellowContact.csv** – Contains details of balls hit into play or hit foul.  

Each dataset contains overlapping fields, which were merged and validated to produce one unified, error-free file.

---

## 🧠 Process Summary  
The project followed three main steps:

### 1. **Data Cleaning**  
- Converted date and time columns into standard formats.  
- Removed invalid or duplicate records.  
- Detected and handled incorrect numeric values.  
- Verified column consistency across both datasets.

### 2. **Data Merging**  
- Combined both datasets into a single DataFrame using shared identifiers.  
- Ensured matching and non-matching columns were handled properly.  
- Removed redundant suffixes (like `_x` and `_y`) created during merging.

### 3. **Error Detection & Analysis**  
- Identified more than ten specific data errors (beyond missing values).  
- Used visualization (boxplots, scatter plots) to highlight outliers.  
- Calculated **average exit velocities** for both **Home Team** and **Away Team**.  

---

## 🧰 Tools & Technologies  
| Category | Tools Used |
|-----------|------------|
| Programming Language | Python |
| Libraries | pandas, numpy, matplotlib, seaborn |
| IDE | Visual Studio Code |
| Data Format | CSV, Jupyter Notebook (.ipynb) |

---

## 📊 Key Insights  
- Cleaned datasets improved consistency for analysis.  
- Identified outliers effectively using visual techniques.  
- Provided a reliable calculation of **average exit velocity** for both teams.  
- Demonstrated ability to handle real-world sports analytics challenges with professional precision.

---


