# Demographic Analysis of England's Population (2021 Census)

## Overview
This project presents an Exploratory Data Analysis (EDA) of the 2021 census data for England. By analysing population counts across 33,755 Layer Super Output Areas (LSOAs), this project uncovers structural age profiles at both national and local levels. The analysis focuses on extracting demographic indicators, comparing age distributions by area type, and classifying areas based on their population structure.

## Project Objectives
* **National vs. Local Profiling:** Compare the age distribution of specific LSOAs (e.g., Bury, Birmingham, Dorset) against the national average.
* **Demographic Segmentation:** Group populations into distinct life stages (e.g., Young Families/Students, Workers, Retirees) to understand regional characteristics.
* **Geographical Classification:** Analyse how different area types (e.g., London Boroughs, Metropolitan Districts, Unitary Authorities) correlate with specific demographic concentrations.

## Technologies Used
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualisation:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook

## Key Insights
* **Urban vs. Suburban Divides:** Workers are predominantly concentrated in London Boroughs due to economic opportunities, whereas 'Retiree' demographics are heavily mapped to Non-metropolitan districts.
* **Student/Young Family Clusters:** Metropolitan districts outside of London exhibit a higher concentration of young families and students, often correlating with university locations and affordable suburban housing.
* **National Demographic Extremes:** While the average median age across all LSOAs in England is approximately 42 years, this masks massive local polarisation. The analysis reveals extreme local variations, with the youngest LSOA median age plunging to just 14.5 years (likely student accommodations) and the oldest peaking at nearly 72 years (heavily concentrated retirement communities).
* **Stark Local Age Contrasts:** A direct comparison of specific LSOAs highlights completely inverted population structures. For example, the Dorset (024A) LSOA exhibits a heavily ageing profile, with over 50% of its residents aged 65 or older. In sharp contrast, areas like Bury (026E) show huge concentrations in the 0-14 age brackets (nearly 40%), reflecting localised "young family" hubs.

## How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have Python and Jupyter installed.
3. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
