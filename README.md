**📊 Heart Disease Risk Analysis Dashboard using Power BI** 

🏢 Business Problem
Healthcare organizations face challenges in early detection of heart disease, a condition that remains one of the leading causes of death worldwide.
Without early identification, patients are at a much higher risk of severe cardiac events, leading to higher healthcare costs and worse patient outcomes.

The challenge was to create a dynamic, insightful dashboard that would:
Analyze critical patient health metrics
Identify high-risk individuals
Provide healthcare professionals with real-time, actionable insights

🎯 Project Objective

Analyze patient-level data to detect patterns and correlations related to heart disease.
Identify key risk factors impacting heart disease probability.
Visualize trends and correlations dynamically with interactive filtering.
Enable data-driven decision-making for early medical intervention.

🛠️ Tools Used

Power BI Desktop (dashboard building and visualization)
Python (correlation matrix generation)
Excel/CSV (data preprocessing and storage)
Canva (background design for dashboard aesthetics)

📋 Metrics Used in the Dashboard

Metric	Description
RestingBP	Patient’s resting blood pressure (mm Hg).
MaxHR	Maximum heart rate achieved during exercise.
FastingBS	Fasting blood sugar indicator (>120 mg/dl).
Cholesterol	Serum cholesterol in mg/dl.
Oldpeak	ST depression induced by exercise relative to rest.
Chest Pain Type	Type of chest pain: Asymptomatic (ASY), Atypical Angina (ATA), Non-Anginal Pain (NAP), Typical Angina (TA).
Age	Patient’s age.
Sex	Gender (Male/Female).
Heart Disease	Target variable indicating presence (1) or absence (0) of heart disease.


🛠️ How I Solved This Problem Using Power BI
Data Import and Cleaning:
Loaded heart disease data into Power BI and handled basic cleaning.
Created custom DAX columns:
Age Group (20–30, 30–40, 40–50, etc.) for demographic segmentation.
Heart Disease Probability Label (High / Low) based on Heart Disease presence.

Custom DAX Columns - 
Age Group
Heart Disease Probability:

Data Modeling:
Built relationships and created calculated columns for better analysis flexibility.

Data Exploration:
Explored summary statistics and distributions.
Identified potential strong predictors using a correlation matrix (Python-generated).

Dashboard Construction:
Built KPI Cards to showcase key figures: Average RestingBP, MaxHR, FastingBS, Heart Disease Rate.
Designed Bar Charts to compare metrics across gender.
Created Pie and Donut Charts for Age Group and Gender distribution.
Developed Scatter Plots to showcase correlation between Age, MaxHR, and Heart Disease Probability.
Added Slicers (Gender, Age Group, Chest Pain Type, Heart Disease Probability) for dynamic filtering.

Professional Aesthetics:
Designed custom backgrounds (medical-themed light and dark versions).
Used modern and minimalistic dashboard themes for a clean and professional look.

Final Result:
Delivered an interactive, dynamic Heart Disease Risk Analysis Dashboard that helps early risk detection and supports better medical decision-making.

📈 Dashboard Findings - 
Oldpeak shows the strongest positive correlation with heart disease risk.
MaxHR shows a strong negative correlation — lower MaxHR patients have a higher risk.
Age moderately correlates with heart disease, with highest risk observed in 50–60 years age group.
Chest Pain Type Analysis showed Asymptomatic chest pain (ASY) patients have the highest risk.
Gender Analysis revealed males had slightly higher heart disease cases compared to females.
Fasting Blood Sugar showed minimal impact compared to other health indicators.

✨ Solution Outcome
The final Power BI dashboard:
Identifies high-risk individuals based on critical health metrics.
Visualizes key relationships like Age vs MaxHR decline, Oldpeak elevation, and chest pain severity.
Empowers medical professionals with actionable visual insights.
Enables dynamic filtering across demographics for deeper analysis and storytelling.

📜 Data Source
Dataset used: Kaggle - Heart Disease Dataset

📌 Tags
#PowerBI #DataVisualization #HeartDiseaseAnalysis #HealthcareAnalytics #DataAnalytics #BusinessIntelligence #DAX #DataModeling

