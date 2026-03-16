Project Overview

This project presents an exploratory analysis of UK police crime data to identify patterns in crime levels, crime types, geographic distribution and temporal trends. The analysis was conducted to support real estate decision-making by identifying areas where crime patterns may influence property investment opportunities.

The project compares four police forces:
	-	Metropolitan Police Service
	-	West Midlands Police
	-	North Yorkshire Police
	-	Dyfed-Powys Police

These regions were selected to allow comparison between urban and rural environments.

The dataset covers the period January 2024 to December 2025 and is sourced from the UK Police open data platform. https://data.police.uk/data/

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Submission Contents

The submission folder contains the following components:

README.txt
Statement of Work.docx
Crime Analysis – Trello.html
Pre-Processing Document.docx
Exploratory Data Analysis Report.docx
GitHub Repo - 

Figures/ - Contains exported figures used within the EDA report.

crime_analysis_project
│
├── notebooks
│   ├── 01_preprocessing.ipynb
│   └── 02_eda.ipynb
│
├── data_raw
│   Raw monthly crime datasets downloaded from data.police.uk
│
├── data_clean
│   Cleaned dataset generated during preprocessing
│
└── data_sample
    Small subset of the dataset for quick inspection

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Data Setup (IMPORTANT)

Raw crime datasets are not included in this repository.

To reproduce the analysis:

1. Download the street-level crime datasets from  
https://data.police.uk/data/

2. Select the four police forces listed above.

3. Extract all monthly CSV files into the folder "data_raw"

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Running the Analysis

Open the preprocessing notebook - crime_analysis_project/notebooks/01_preprocessing.ipynb

Running this notebook will generated the cleaned dataset - crime_analysis_project/data_clean/crime_cleaned.csv

Next run the EDA notebook - crime_analysis_project/notebooks/02_eda.ipynb

Running this notebook will generate the visualisations used in the EDA report.

All file paths within the notebooks are relative, allowing the project to run directly fro the proved folder structure.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------


Data Source

Crime data used in this project was obtained from:

UK Police Open Data Portal - https://data.police.uk/data/

Street-level crime datasets were downloaded for the four selected police forces covering the period January 2024 – December 2025.


