PCOS Data Analysis Project
This project presents a detailed analysis of a real-world medical dataset focused on Polycystic Ovary Syndrome (PCOS). It aims to uncover clinical and lifestyle patterns that differentiate PCOS and non-PCOS cases using data cleaning, visual exploration, and a Power BI dashboard.

1.Objective<br>
To explore, clean, and analyze the PCOS dataset in order to identify key indicators (like BMI, AMH, LH/FSH ratio) and lifestyle factors (like diet and exercise) associated with PCOS risk. The goal is to assist early diagnosis and create awareness through clear insights and visualizations.<br>

2.From Dataset to Diagnosis: Project Flow<br>
-Now that the goal is set, let’s walk through the complete pipeline — from raw medical data to clean insights.<br>
-We begin with Data Cleaning, the essential first step in transforming messy clinical entries into reliable features ready for analysis.<br>

3.Data Cleaning<br>
-Removed redundant columns like Sl. No, Patient File No., and Unnamed: 44<br>
-Standardized column names (e.g., removed trailing spaces)<br>
-Converted Y/N responses to binary (1 for Yes, 0 for No)<br>
-Handled missing values based on the percentage and impact<br>
-Saved a cleaned version of the dataset

4.Exploratory Data Analysis (EDA)<br>
-Performed using Python libraries: pandas, matplotlib, seaborn.<br>
-Key areas of analysis:<br>
-Demographics: Age, BMI, years married<br>
-Hormonal Analysis: LH, FSH, AMH, PRL<br>
-PCOS Group Comparison: Feature means between PCOS and non-PCOS<br>
-Correlation Heatmaps: Highlighting medical relationships<br>
-Outlier Detection: Boxplots for BMI, AMH, LH/FSH<br>
-Lifestyle Impact: Exercise frequency and fast food consumption<br>
-Visuals include violin plots, scatter plots, boxplots, heatmaps, and bar charts.<br>

5.Power BI Dashboard<br>
-An interactive dashboard created using Power BI for easy data exploration. Features:<br>
-Filters by age, BMI, and lifestyle<br>
-Symptom and hormone comparisons<br>
-Correlation views<br>
-Risk factor visualizations<br>
-Open the .pbix file using Power BI Desktop.<br>

6.Key Findings<br>
-Higher BMI, AMH levels, and LH/FSH ratio are linked with PCOS.<br>
-Poor lifestyle habits (lack of exercise, frequent junk food) increase risk.<br>
-Distinct hormonal trends exist between PCOS and non-PCOS groups.<br>

7.Tools Used<br>
Python (pandas, seaborn, matplotlib)<br>
google colab<br>
Power BI<br>

8.How to Use<br>
-Clone this repository.<br>
-Open notebook/PCOS_EDA.ipynb to run the Python analysis and use PCOS_data.csv(dataset).<br>
-View visuals/ for plots.<br>
-Open dashboard/PCOS_PowerBI.pbix in Power BI Desktop.<br>





