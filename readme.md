\# Gender and Intrafamily Violence – Descriptive Data Analysis

\# Project Overview  
This project presents a descriptive analysis of reported cases of gender and intrafamily violence using publicly available health surveillance data from Colombia.  
The objective is to explore who is affected, how cases are distributed across age groups, gender, and territory, and to practice responsible data visualization using Power BI.  
This analysis focuses on patterns and distributions, not on causal interpretation or prevalence estimation.

\# Key Questions Addressed  
The dashboard was designed to answer the following questions:

1. How many cases have been reported in the selected dataset?

2. How are reported cases distributed by gender of the victim?

3. How are reported cases distributed by gender of the aggressor?

4. Which age groups concentrate the highest number of reported events?

5. How are cases geographically distributed by municipality?  
   

\# Dataset Description  
The dataset comes from a public health surveillance registry and contains anonymized records of reported violence cases.  
Key variables used in this analysis include:

* Gender of the victim

* Gender of the aggressor

* Age of the victim

* Municipality of occurrence

Missing or incomplete values were preserved and handled carefully to avoid introducing assumptions.

\# Methodology & Data Preparation

* Age values were grouped into standard age ranges commonly used in public health reporting to improve readability and interpretation.

* No records were removed for visualization purposes.

* The analysis remains purely descriptive, avoiding causal claims or predictive modeling.

* Visual choices prioritize clarity and respect due to the sensitive nature of the data.


\# Dashboard Description  
The Power BI dashboard includes:

* A central KPI showing the total number of reported cases

* Bar charts displaying:

  * Cases by gender of the victim

  * Cases by gender of the aggressor

  * Events grouped by age range

* A geographic visualization showing the distribution of reported cases by municipality

Design decisions favored neutral colors, minimal decoration, and clear labeling to support responsible communication of sensitive information.

\# Key Observations

* Reported cases are not evenly distributed across gender or age groups.

* Certain age ranges concentrate a higher number of reported events.

* Geographic distribution shows clustering in specific municipalities.

These observations describe the data as reported, without implying underreporting levels or causality.

\# Important Notes & Limitations

* The data reflects reported cases only, not the true prevalence of violence.

* Results depend on reporting practices and data completeness.

* This project does not attempt to infer causes, risk factors, or outcomes.

This dashboard is intended for educational and analytical practice purposes only.

\# Tools Used

* Power BI Desktop – data modeling and visualization

* DAX – calculated columns and measures

* Power Query – light data preparation

* Public CSV dataset – official surveillance data

\# Repository Structure  
violence-data-analysis/  
├── data/  
│   └── Registro\_Vigilancia\_Violencia.csv  
│  
├── powerbi/  
│   └── violencia\_dashboard.pbix  
│  
├── images/  
│   └── dashboard\_preview.png  
│  
├── README.md

\# Disclaimer  
This project was created as a data analysis practice exercise.  
 All interpretations are descriptive and should be contextualized within broader public health research.  
