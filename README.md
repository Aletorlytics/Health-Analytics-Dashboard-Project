# 🚀Health Analytics Dashboard Project
## Health Analytics | Power BI Dashboard | Data Visualization | Risk Pattern Interpretation
### View the Dashboard Interface below
<img width="1170" height="661" alt="Screenshot 2026-01-15 081832" src="https://github.com/user-attachments/assets/c149eb78-15b6-4a18-af77-468c085c9dee" />|
<img width="1170" height="657" alt="Screenshot 2026-01-15 082139" src="https://github.com/user-attachments/assets/feaec612-a1f5-482b-a58e-4bab44f2c9f7" />
<img width="1171" height="664" alt="Screenshot 2026-01-15 082330" src="https://github.com/user-attachments/assets/ab997cd7-353f-40b5-96e4-fb79e4c6930d" />
<img width="1169" height="661" alt="Screenshot 2026-01-15 082433" src="https://github.com/user-attachments/assets/37b22dc9-6a61-4e1f-b7b2-50d1bd133464" />
<img width="1169" height="660" alt="Screenshot 2026-01-15 082523" src="https://github.com/user-attachments/assets/74367ee4-59fd-4687-a824-ecf2dc896101" />
<img width="1166" height="662" alt="Screenshot 2026-01-15 082620" src="https://github.com/user-attachments/assets/d1bea1d0-9bfd-4b9c-a950-d2bd72cc38b5" />
<img width="1170" height="661" alt="Screenshot 2026-01-15 082907" src="https://github.com/user-attachments/assets/33db2ecb-0d5c-4d2b-9c23-3635d0c07050" />
<img width="1168" height="662" alt="Screenshot 2026-01-15 082718" src="https://github.com/user-attachments/assets/aa2d30bf-4835-4beb-89c1-2295019cc6ba" />
<img width="1169" height="659" alt="Screenshot 2026-01-15 083126" src="https://github.com/user-attachments/assets/eea62808-40c6-4a04-9cb2-d68743e72b03" />
<img width="1170" height="660" alt="Screenshot 2026-01-15 104852" src="https://github.com/user-attachments/assets/877bb135-bb71-4b70-ae66-a122049cc390" />

### 🪗Table of Contents
 - [Business Introduction](#business-introduction)
 - [Problem Statement](#problem-statement)
 - [Project Overview](#project-overview)
 - [Data Preparation and Modeling](#data-preparation-and-modeling)
 - [Dashboard Scope and Focus](#dashboard-scope-and-focus)
 - [Scope of Analysis](#scope-of-analysis)
 - [Dashboard Capabilities](#dashboard-capabilities)
 - [Analytical Insights](#analytical-insights)
 - [Data Dictionary](#data-dictionary)
 - [Key Achievements](#key-achievements)
 - [Strategic Takeaway](#strategic-takeaway)
 - [Tools and Technologies](#tools-and-technologies)
 - [Disclaimer](#disclaimer) 

### ⚓Business Introduction
Healthcare organizations rely on data analytics and business intelligence to understand behavioural risk factors and improve decision-making. However, health data is often complex, multi-dimensional, and difficult to interpret without effective analytical modelling and visualization.
This project demonstrates how health analytics, data analysis, and Power BI dashboards can be used to interpret complex health datasets and transform them into clear, actionable insights. The analysis focuses on understanding how smoking behaviour relates to health risks across multiple organs and demographic dimensions, using interactive data visualisation and analytical storytelling.

### ❗Problem Statement
Smoking-related health risks are commonly analysed using isolated metrics or single-organ outcomes. This approach limits the ability to identify systemic patterns, understand cumulative risk, and evaluate how behavioural and demographic factors interact over time.
The problem addressed in this project is:
How can multi-dimensional health data be analyzed and visualized using Power BI to clearly identify smoking-related health risk patterns across organ systems, age groups, BMI categories, and gender segments in a single analytical view?

### 🪗Project Overview
This project applies data analytics, health data analysis, and business intelligence techniques to explore the relationship between smoking status and health outcomes. An interactive Power BI dashboard allows users to compare Healthy and Damaged profiles across multiple organs while simultaneously evaluating demographic and behavioural variables.
The dashboard supports exploratory data analysis, comparative analysis, and pattern recognition, enabling insight generation rather than static reporting.
Key analytical questions include:
- How does smoking status correlate with observed health risk across different organs?
- Do current smokers consistently exhibit higher risk indicators?
- How does age influence smoking-related risk accumulation?
- Do former smokers return to the same risk profile as never smokers?
- How do BMI and gender interact with smoking-related health outcomes?

### 🚡Data Preparation and Modeling
Data Preparation
- Cleaned and transformed raw CSV datasets using Power Query.
- Standardized health outcome variables into Healthy and Damaged classifications.
- Normalized smoking status into Never, Former, and Current smoker categories.
- Reviewed missing values and inconsistencies to maintain data quality and analytical accuracy.
Data Modeling
- Established smoking status as a core segmentation variable across all visuals.
- Created categorical age groups to support comparative analysis.
- Grouped BMI values into analytical categories to observe incremental risk changes.
- Built DAX measures to ensure consistent calculations across all organ views.
- Implemented a unified data model enabling synchronized slicer interaction across visuals.

### 📋Dashboard Scope and Focus
Analytical Dimensions
- Smoking Status
- Health Profile, Healthy vs Damaged
- Organ Systems, Heart, Liver, Kidney, Body
- Age Groups
- BMI Categories
- Gender Segmentation
### 🫀Scope of Analysis
The dashboard supports:
- Cross-organ health risk comparison
- Identification of cumulative and systemic risk patterns
- Analysis of behavioural risk factors
- Evaluation of demographic influences on health outcomes
- Insight-driven interpretation rather than clinical diagnosis

### 📋Dashboard Capabilities
The Power BI dashboard enables:
- Interactive toggling between Healthy and Damaged health profiles
- Dynamic organ level analysis through slicers
- Comparative analysis of smoking status distributions
- Visualization of age-related risk accumulation
- Exploration of BMI as a compounding risk factor
- Gender based segmentation without disrupting analytical consistency
- Simultaneous multi dimensional exploration within a single dashboard

### 📈Analytical Insights
Smoking Status and Health Profiles
Across all organ systems, Current Smokers show consistently higher representation in Damaged profiles compared to Never and Former Smokers. This trend remains stable across all organ views, indicating systemic rather than localized risk patterns.

Healthy vs Damaged Comparison
Switching between Healthy and Damaged profiles produces a clear redistribution of smoking categories. Healthy profiles are dominated by Never Smokers, while Damaged profiles show increased concentrations of Current and Former Smokers across all visuals.

Age Group Analysis
Damaged profiles reveal smoking-related risk appearing earlier across age groups. Younger smokers often display risk patterns comparable to older individuals in Healthy profiles, suggesting accelerated health risk accumulation associated with smoking behaviour.

Former Smoker Outcomes
Former Smokers consistently fall between Never and Current Smokers across organ views. While outcomes improve compared to Current Smokers, residual risk remains observable when compared to Never Smokers.

BMI and Risk Interaction
Higher BMI categories show increased Damaged outcomes among smokers. This pattern is gradual and consistent, indicating BMI functions as a compounding risk factor rather than an independent driver.

Gender Based Patterns
Although smoking prevalence varies slightly by gender, overall health risk trends remain consistent. In both male and female segments, Current Smokers are more strongly associated with Damaged profiles.

Cross Organ Consistency
Switching between heart, liver, kidney, and full body views does not alter the observed smoking risk hierarchy. The relative ordering of smoking categories remains consistent across all organ systems.
### 📖Data Dictionary

   Field name           |          Description
:----------------------:|:---------------------------------------------------------------:
  Smoking_status        |       Smoking classification: Never, Former, Current
  Health_profile        |       Health outcome classification: Healthy or Damaged
  Organ_type            |       Organ system analyzed: Heart, Liver, Kidney, Body
  Age_group             |       Categorized age ranges for comparative analysis
  BMI_Category          |       Grouped BMI ranges used for risk pattern evaluation
  Gender                |       Gender classification for segmentation


### 🎰Key Achievements
- Built an interactive Power BI health analytics dashboard.
- Applied data cleaning, data modelling, and DAX calculations.
- Enabled multi-dimensional health risk analysis in a single view.
- Delivered insight-driven analytics focused on interpretation.
- Designed recruiter-friendly visuals aligned with business intelligence best practices.

### 🫀Strategic Takeaway
This project demonstrates that smoking-related health risk is cumulative, systemic, and behaviour-driven. By integrating behavioural, demographic, and organ-level data into a single interactive dashboard, the analysis highlights how data analytics and business intelligence can support a clearer understanding of complex health patterns and inform data-driven decision-making.

### 🧰Tools and Technologies
- Power BI, data visualization and dashboard development
- Power Query, data cleaning and transformation
- DAX, analytical calculations and measures
- CSV, structured data source

### Disclaimer
This project is intended for educational and portfolio purposes only. It is not a medical, diagnostic, or clinical decision support tool.






