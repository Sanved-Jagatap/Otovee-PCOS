Otovee PCOS Data Analysis Project
This project presents a detailed analysis of a real-world medical dataset focused on Polycystic Ovary Syndrome (PCOS). It aims to uncover clinical and lifestyle patterns that differentiate PCOS and non-PCOS cases using data cleaning, visual exploration, and a Power BI dashboard.

1.Objective
To explore, clean, and analyze the PCOS dataset in order to identify key indicators (like BMI, AMH, LH/FSH ratio) and lifestyle factors (like diet and exercise) associated with PCOS risk. The goal is to assist early diagnosis and create awareness through clear insights and visualizations.

2.From Dataset to Diagnosis: Project Flow
-Now that the goal is set, let’s walk through the complete pipeline — from raw medical data to clean insights.
-We begin with Data Cleaning, the essential first step in transforming messy clinical entries into reliable features ready for analysis.

3.Data Cleaning
-Removed redundant columns like Sl. No, Patient File No., and Unnamed: 44
-Standardized column names (e.g., removed trailing spaces)
-Converted Y/N responses to binary (1 for Yes, 0 for No)
-Handled missing values based on the percentage and impact
-Saved a cleaned version of the dataset

4.Exploratory Data Analysis (EDA)
-Performed using Python libraries: pandas, matplotlib, seaborn.
-Key areas of analysis:
-Demographics: Age, BMI, years married
-Hormonal Analysis: LH, FSH, AMH, PRL
-PCOS Group Comparison: Feature means between PCOS and non-PCOS
-Correlation Heatmaps: Highlighting medical relationships
-Outlier Detection: Boxplots for BMI, AMH, LH/FSH
-Lifestyle Impact: Exercise frequency and fast food consumption
-Visuals include violin plots, scatter plots, boxplots, heatmaps, and bar charts.

5.Power BI Dashboard
-An interactive dashboard created using Power BI for easy data exploration. Features:
-Filters by age, BMI, and lifestyle
-Symptom and hormone comparisons
-Correlation views
-Risk factor visualizations
-Open the .pbix file using Power BI Desktop.

6.Key Findings
-Higher BMI, AMH levels, and LH/FSH ratio are linked with PCOS.
-Poor lifestyle habits (lack of exercise, frequent junk food) increase risk.
-Distinct hormonal trends exist between PCOS and non-PCOS groups.

7.Tools Used
Python (pandas, seaborn, matplotlib)
google colab
Power BI

8.How to Use
-Clone this repository.
-Open notebook/PCOS_EDA.ipynb to run the Python analysis and use PCOS_data.csv(dataset).
-View visuals/ for plots.
-Open dashboard/PCOS_PowerBI.pbix in Power BI Desktop.





