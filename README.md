# ASU_GTD_Applied_Project_2023

This repository contains the code and analysis for processing UN SDG 4 indicator data for creating Tableau dashboards.

## Overview

The United Nations Sustainable Development Goal 4 (SDG 4) focuses on ensuring inclusive and equitable quality education for all. The indicator data associated with SDG 4 provides valuable insights into the progress and challenges related to education globally.

SDG #4 aims to ensure inclusive and equitable quality education for all, promoting lifelong learning opportunities and fostering education that contributes to sustainable development (United Nations, 2023). 
All UN SDG indicator data is from the [United Nations Data Portal](https://unstats.un.org/sdgs/dataportal/database)

## Objective

My objective was to leverage python and Tableau's data analysis and visualization capabilities to create insightful and interactive dashboards that will aid in monitoring and promoting progress towards SDG #4.

## Background and Motivation

Access to quality education remains a persistent challenge in many parts of the world. Issues such as lack of resources, teacher shortages, and socio-economic disparities contribute to the education gap, hindering the achievement of UN Sustainable Development Goal #4 (SDG #4), which aims to ensure inclusive and equitable quality education for all (United Nations, 2023). UN SDG #4, "Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all," addresses the urgent need to improve educational outcomes, promote lifelong learning, and enhance educational infrastructure globally (United Nations, 2023). According to UNESCO, around 244 million children and youth were out of school in 2021, and even for those enrolled, the quality of education remains a concern in various regions (UNESCO, 2023). Addressing these challenges requires data-driven insights and actionable accessible information to support evidence-based decision-making in the education sector.

For this project, the Middle East and North Africa (MENA) region was specifically chosen as a subset for analysis. This decision was driven by my prior experience and interest in the region, where I served as a Peace Corps volunteer. It's important to note that the MENA region is defined by the United Nations, and this choice was aligned with the specific indicators and goals outlined by the UN for SDG #4. This region provides a unique context and diverse set of challenges and opportunities in the realm of education, making it an ideal focus for the project.

## Data Cleaning Process

I start by loading the indicator data from an Excel file into a pandas DataFrame. The data is then filtered to include only specific countries of interest within the SDG 4 framework. Columns with all NaN values are dropped, and a subset of relevant columns is selected.

To further refine the dataset, we identify the earliest and most recent years for each country, and a filtering process is applied to keep only the data corresponding to these years. Additionally, a 'Year_Type' column is added to categorize each year as either the base or most recent year for a given country.

## Formatting and Export

The resulting cleaned and filtered dataset is then exported to a CSV file for further analysis or visualization.

## Tableau Dashboards

The cleaned data serves as the foundation for creating Tableau dashboards that provide a visual representation of the SDG 4 indicator trends. These dashboards offer an interactive and dynamic way to explore and understand the educational landscape across the Middle East and North Afria region.

Explore the visual representation of the SDG 4 indicator trends through Tableau dashboards:
- [Tableau Dashboard UN SDG #4](https://public.tableau.com/views/ASUGTDFinalProject-UNSDG4/Coverpage?:language=en-US&:display_count=n&:origin=viz_share_link)

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

## Sources
-[United Nations](https://sdgs.un.org/goals)
-[UNESCO](https://en.unesco.org/sustainabledevelopmentgoals)
