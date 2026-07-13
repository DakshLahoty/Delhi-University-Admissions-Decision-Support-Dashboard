# Delhi-University-Admissions-Decision-Support-Dashboard
An Excel-based decision support system for University of Delhi admissions that combines official cutoffs, placement data, fees, and institutional metrics to help applicants make informed college choices based on CUET marks.

## Overview
**Delhi University Admissions Decision Support Dashboard** is an Excel-based analytics project designed to help prospective students make informed decisions while selecting colleges and courses under the University of Delhi.

Every CUET admission cycle, students face difficulty comparing colleges due to scattered information across cutoff PDFs, college websites, and unofficial online sources. This project solves that problem by consolidating **official admission cutoffs, institutional data, and placement information** into a structured, interactive dashboard.

Users input their course and marks and are provided with a filtered view of colleges they are eligible for, along with comparative insights such as cutoffs, placements, and institutional quality indicators.

## Problem Statement - Pain point identified and solved

University of Delhi cutoff data is publicly available but is highly fragmented across multiple sources and formats. Students usually rely on:
- Cutoff prediction websites  
- Static PDF documents  
- Manual comparison of colleges  
- Incomplete placement information  

Which leads to:
- confusion during college selection  
- inaccurate expectations about admission chances  
- difficulty comparing institutions systematically  

The goal of this project is to create a **decision support system** that organizes official data into a usable analytical format.
---
## Objectives

- Consolidate official DU admission cutoff data into a structured dataset  
- Enable dynamic filtering based on marks and course selection  
- Provide comparative insights on colleges using multiple indicators  
- Visualize admission and institutional data through dashboards  
- Support faster and more informed college selection decisions  

---

## Features (V1.5)

- Interactive dashboard for DU admissions exploration  
- Slicer-based filtering (Course + College)  
- Auto-generated list of eligible colleges with NAAC ratings  
- Course-wise and category-wise cutoff analysis
- Gender based filtering of colleges  
- Power Query-based ETL pipeline for data cleaning  
- Standardized tables for:
  - Colleges  
  - Courses

 ## Excel Skills
- Dynamic Excel functions:
- FILTER function
- SORT Function  
- Data Validation  
- Structured Tables
- Pivot Tables
- Pivot Charts
- Clean and structured dashboard layout  

---
## Data Sources

All data used in this project is sourced from **official public domains**, including:

- University of Delhi CSAS admission cutoff releases  
- Official college websites (placement and institutional data)  
- Publicly available institutional reports  

No unofficial prediction data or third-party estimates have been used.

---

## Data Processing (ETL Pipeline)

The project follows a structured **Extract - Transform - Load (ETL)** approach using **Microsoft Power Query**.

### 1. Extract
Raw data is collected from official DU admission PDFs and institutional sources.

### 2. Transform
Data is cleaned and standardized:
- Course names are mapped and corrected to official DU-CSAS names  
- College names are mapped and corrected to official DU-CSAS names
- Duplicate entries are removed  
- Inconsistent formatting is corrected  
- Data types are standardized for analysis  

### 3. Load
Cleaned data is loaded into Excel tables used by:
- Pivot Tables  
- Dashboard filters  
- Lookup functions  

This ensures the dashboard remains **refreshable and scalable** for future admission cycles.

---

## Dashboard Functionality

Users can:

1. Select course (e.g., B.Com, Economics, etc.)  
2. Enter marks scored  
3. View eligible colleges based on cutoff data  
4. Compare institutions using:
   - Admission cutoffs  
   - Placement data  
   - Institutional indicators (NAAC where available)  
5. Analyze relative differences between colleges  

The system is designed to simplify complex admission data into an **interactive decision-making experience**.

---

## Planned Improvements

Future enhancements include:

- Fee structure integration  
- ROI-based analysis (Placement vs Fees)  
- NIRF ranking integration  
- Improved college comparison dashboard  

---

## Limitations

- Placement data is available only for selected colleges  
- The system is based on historical cutoff data and does not predict future cutoffs  
- Rankings and institutional metrics are used as comparative indicators, not absolute measures  
- Data accuracy depends on official public sources  

---

## Disclaimer

This project is an independent educational initiative created using publicly available data. It is not affiliated with or endorsed by the University of Delhi or any of its constituent colleges.

The dashboard is intended solely for informational and analytical purposes. Users should verify all admission-related decisions through official University of Delhi channels.

---

## Author

Developed by: DAKSH LAHOTY 
Built using: Microsoft Excel + Power Query  
Version: V1.5
