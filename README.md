# ASU_GTD_Applied_Project_2023

This repository contains the code and analysis for processing UN SDG 4 indicator data for creating Tableau dashboards.

## Overview

The United Nations Sustainable Development Goal 4 (SDG 4) focuses on ensuring inclusive and equitable quality education for all. The indicator data associated with SDG 4 provides valuable insights into the progress and challenges related to education globally.

In this project, I utilize Python to analyze and clean the SDG 4 indicator data. The cleaned data is then used to create a series of informative Tableau dashboards for a more visual representation of the education indicators.

## Data Cleaning Process

I start by loading the indicator data from an Excel file into a pandas DataFrame. The data is then filtered to include only specific countries of interest within the SDG 4 framework. Columns with all NaN values are dropped, and a subset of relevant columns is selected.

To further refine the dataset, we identify the earliest and most recent years for each country, and a filtering process is applied to keep only the data corresponding to these years. Additionally, a 'Year_Type' column is added to categorize each year as either the base or most recent year for a given country.

## Formatting and Export

The resulting cleaned and filtered dataset is then exported to a CSV file for further analysis or visualization.

## Tableau Dashboards

The cleaned data serves as the foundation for creating Tableau dashboards that provide a visual representation of the SDG 4 indicator trends. These dashboards offer an interactive and dynamic way to explore and understand the educational landscape across the Middle East and North Afria region.

Explore the visual representation of the SDG 4 indicator trends through Tableau dashboards:
- [Tableau Dashboard 1]([https://your-tableau-dashboard-url-1](https://public.tableau.com/views/ASUGTDFinalProject-UNSDG4/Coverpage?:language=en-US&:display_count=n&:origin=viz_share_link))

## Usage

1. **Data Cleaning and Analysis:**
   - The Python script (`UN SDG 4 Data Cleaning.ipynb`) provided in this repository is used to clean and analyze the SDG 4 indicator data.
   - Make sure to have the required libraries installed (`pandas`).

2. **Tableau Dashboards:**
   - The cleaned dataset (example `output_4_2_2.csv`) can be imported into Tableau for creating customized dashboards.
   - Utilize the processed data to visualize and analyze trends related to education indicators.

Feel free to explore the code and dashboards to gain insights into the progress and challenges associated with SDG 4.

## Contributors

- [Sydney Leiher]
