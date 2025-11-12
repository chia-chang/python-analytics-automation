# Notebooks Directory

This folder contains the Jupyter notebooks used in this project. Each notebook covers a different stage of the analysis pipeline:

- **Data_Cleaning_and_Integration.ipynb:** Shows data loading, cleaning steps, and integration of sources
  - Clean column names, handle missing values, and standardize date formats
  - Generate derived metrics such as 7-day averages, cumulative totals, and week-over-week changes
  - Exporting the processed dataset (`covid_integrated_data.csv`) for use in the reporting notebook
  
- **Automated_Reporting.ipynb:** Demonstrates how the reporting process can be run automatically
  - Loads the processed dataset
  - Calculates key metrics (averages, trends, cumulative totals)
  - Generates publication-ready visualizations
  - Produces a multi-sheet Excel report that includes daily, weekly, and summary data


Suggestions, feedback, or additional notebooks are always welcome!
