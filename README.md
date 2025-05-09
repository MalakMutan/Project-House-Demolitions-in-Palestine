# Project-House-Demolitions-in-Palestine


# Forced House Demolitions in Palestine

This project aims to analyze the issue of forced house demolitions in Palestine, identifying the areas most affected, the number of people displaced, and the most vulnerable groups. The report will explore patterns related to settlement projects and targeted demolitions in Jerusalem, providing data-driven insights to support advocacy and awareness.

## Objective

The objective of this project is to:
- Identify the regions and cities most affected by forced demolitions.
- Quantify the number of people, especially vulnerable groups (e.g., minors), displaced by these demolitions.
- Analyze the trends and patterns, particularly in relation to settlement projects and the targeting of Jerusalem.

## Hypotheses
1. The number of homes demolished annually has been increasing due to the rise in settlement projects.
2. Jerusalem has been specifically targeted to push the population out and suppress their presence.

## Data Description

The dataset used in this analysis includes the following fields:

- **Year**: The year the demolition decision was implemented.
- **Housing Units**: The number of housing units demolished.
- **People Left Homeless**: The number of people left homeless due to the demolitions.
- **Minors Left Homeless**: The number of children (under 18) who became homeless due to demolitions.
- **Area**: Region of the demolition (West Bank, Jerusalem, Gaza).
- **Type of Structures**: Type of structure demolished (residential, non-residential).
- **Scope of Demolition**: Whether the demolition was complete or partial.
- **District**: The specific city or district affected by the demolition.
- **Demolition Reason**: The reason for the demolition (unlawful construction, military purposes, punishment).
- **Demolition Carried Out By**: The party responsible for the demolition (Israeli occupation, etc.).

## Data Engineering Process

### Data Loading and Exploration
- Load the data and explore its structure.
- View the first few rows and check for any anomalies or inconsistencies.

### Data Cleaning
- Convert columns representing numbers to appropriate numerical data types.
- Convert date columns to a consistent format.
- Handle missing values:
  - Fill NaN values in columns related to homelessness with 0.
  - Fill missing values in 'Demolition carried out by' with "Israeli occupation".
- Remove duplicate rows and rows with incomplete data.

### Data Analysis
- **Statistical Description**: Summarize the data with basic statistics.
- **People Left Homeless**: Study the number of displaced individuals, with a focus on minors.
- **Trends by Year**: Analyze trends in the number of demolitions over the years.
- **Geographical Distribution**: Explore the impact of demolitions in different areas and districts.

## Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebooks for data analysis and visualization
- GIS tools (QGIS, GeoPandas) for mapping
- Data visualization libraries (Matplotlib, Seaborn)

## Results & Insights

- **Demolition Trends**: Trends in the number of demolitions over time, including the influence of settlement projects.
- **Impact on Vulnerable Groups**: Insights into the impact on children and displaced families.
- **Geographical Insights**: Analysis of areas, with a focus on Jerusalem, that are most targeted for demolitions.

## Conclusion

This report presents a data-driven analysis of forced house demolitions in Palestine, shedding light on the most affected regions, the people displaced, and the underlying factors contributing to this humanitarian crisis.

## Contact

For more information, collaboration, or inquiries, please contact:

**Malak Mutan**  
📧 malak.almutan@students.alquds.edu  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/malakmutan)

---

> "Data can tell powerful stories — let’s use it to make a difference."
