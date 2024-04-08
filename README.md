# ASU_GTD_Applied_Project_2023

This repository contains the code and analysis for processing UN SDG 4 indicator data for creating Tableau dashboards.

## Overview

The United Nations Sustainable Development Goal 4 (SDG 4) focuses on ensuring inclusive and equitable quality education for all. The indicator data associated with SDG 4 provides valuable insights into the progress and challenges related to education globally.

SDG #4 aims to ensure inclusive and equitable quality education for all, promoting lifelong learning opportunities and fostering education that contributes to sustainable development (United Nations, 2023). 
All UN SDG indicator data is from the [U.N Department of Economic and Social Affaris SDG Database ](https://unstats.un.org/sdgs/dataportal/database).

## Objective

My objective was to leverage python and Tableau's data analysis and visualization capabilities to create insightful and interactive dashboards that will aid in monitoring and promoting progress towards SDG #4.

## Background and Motivation

Access to quality education remains a persistent challenge in many parts of the world. Issues such as lack of resources, teacher shortages, and socio-economic disparities contribute to the education gap, hindering the achievement of UN Sustainable Development Goal #4 (SDG #4), which aims to ensure inclusive and equitable quality education for all (United Nations, 2023). UN SDG #4, "Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all," addresses the urgent need to improve educational outcomes, promote lifelong learning, and enhance educational infrastructure globally (United Nations, 2023). According to UNESCO, around 244 million children and youth were out of school in 2021, and even for those enrolled, the quality of education remains a concern in various regions (UNESCO, 2023). Addressing these challenges requires data-driven insights and actionable accessible information to support evidence-based decision-making in the education sector.

For this project, the World Bank Eastern Mediterranean Region was specifically chosen as a subset for analysis. This decision was driven by my prior experience and interest in the region, where I served as a Peace Corps volunteer. It's important to note that the EMRO is defined by the World Health Organization as the Eastern Mediterranean Region (EMRO). 

## Data Cleaning and Analysis

I started by downloading the 4 indicators from [U.N Department of Economic and Social Affaris SDG Database ](https://unstats.un.org/sdgs/dataportal/database) . To download the data, select the Data Series (4.1.1, 4.2.2, 4.3.1, 4.4.1), all the [EMRO Countries](https://www.emro.who.int/countries.html), and all years. Next, I loaded the indicator data from an Excel file into a pandas DataFrame.

Import Pandas: The code begins by importing the Pandas library, commonly used for data manipulation and analysis in Python.

Load Data: The Goal4.xlsx file is loaded into a Pandas DataFrame named df.

Filtering: Rows where the 'Indicator' column equals the selected indicator are filtered out and stored back in the DataFrame df.

Base and Recent Years Determination: The script determines the base and most recent years for each country, considering different factors such as sex, education level, and type of skill. This information is stored in a DataFrame named base_recent_years_df.

Merge Data: The original DataFrame df is merged with base_recent_years_df to obtain values for base and recent years. This merged DataFrame is stored as merged_df.

Percentage Point Change Calculation: The percentage point change between base and recent years is calculated for each country, sex, and selected subgroups. The result is stored in a DataFrame named percentage_change_df.

## Tableau Dashboards

The cleaned data serves as the foundation for creating Tableau dashboards that provide a visual representation of the SDG 4 indicator trends. These dashboards offer an interactive and dynamic way to explore and understand the educational landscape across the EMRO region.

Explore the visual representation of the SDG 4 indicator trends through Tableau dashboards:
- [Tableau Dashboard UN SDG #4](https://public.tableau.com/views/ASUGTDFinalProject-UNSDG4/Coverpage?:language=en-US&:display_count=n&:origin=viz_share_link)

## Usage

1. **Data Cleaning and Analysis:**
   - The Python script (`Indicator Data Transformations.ipynb`) provided in this repository is used to clean and analyze the SDG 4 indicator data for all EMRO countries.
   - The Python script ('4.1, 4.2, 4.3 World Averages') provided in this repository is used to clean and analyse all countries data.
   - Make sure to have the required libraries installed (`pandas`).

2. **Tableau Dashboards:**
   - The cleaned dataset (example `output_4.1.csv`) can be imported into Tableau for creating customized dashboards.
   - Utilize the processed data to visualize and analyze trends related to education indicators.

Feel free to explore the code and dashboards to gain insights into the progress and challenges associated with SDG 4.

## Contributors

- [Sydney Leiher]

## Sources
-[United Nations](https://sdgs.un.org/goals)
-[UNESCO](https://en.unesco.org/sustainabledevelopmentgoals)
- [U.N Department of Economic and Social Affaris SDG Database ](https://unstats.un.org/sdgs/dataportal/database)
