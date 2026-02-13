# Visualizing FEMA National Risk Index Scores & Climate Hazard Risk Exposure in California

## Purpose of This Repository

This repository initially examined the distribution of county-level NRI scores across U.S. states, with California highlighted for comparison and focuses on designing and interpreting a data visualization using {`ggplot2`} to compare county-level FEMA National Risk Index (NRI) scores across US states, with particular emphasis on California. The primary objective is to apply principles of effective data visualization to communicate patterns in disaster risk across states. The assignment requires creating a polished visualization that meets specific design and accessibility criteria, including custom colors, clear annotations, captions, and alt text. The project also involves reflecting on visualization choices and explaining the rationale behind design decisions. 

A newer edition of this repository builds on this work by joining FEMA NRI risk scores with ACS demographic estimates to answer the question:

**How does climate hazard risk exposure vary across racial and ethnic groups in California?**

The project emphasizes clear communication, accessibility, and thoughtful design choices, including custom colorblind friendly palettes, captions, and alt text.

## Visualization Approach

#### Homework #2: County-Level Risk Distributions Across States

The final visualization uses a ridgeline density plot to show the distribution of county-level NRI scores by state. States are ordered by their median county score to highlight overall trends, and California is highlighted in custom colors. Median values are overlaid to improve interpretability and reduce ambiguity. Design choices prioritize readability, accessibility, and clear communication of the main takeaway.

<img width="300" height="480" alt="figure" src="https://github.com/user-attachments/assets/dbe96f6f-6bc5-4582-82ec-e46cb252fe97" />

### Homework #3: Climate Hazard Exposure by Race and Ethnicity in California

The final visualization answers how climate hazard risk exposure differs across racial and ethnic groups in California. County-level FEMA NRI scores are combined with ACS population estimates, and group exposure is calculated as the population-weighted average risk experienced across counties. Exposure differences are modest statewide, but Asian and Black communities face slightly higher-than-average climate hazard risk exposure compared with the California baseline.

<Insert Image Here>

## Repository Structure

``` bash
EDS-240-NRI-ACS-VIZ
├── .gitignore
├── EDS-240-NRI-ACS-VIZ.Rproj
├── HW2.qmd
├── HW3.qmd
└── README.md
```

## Data Access

This project uses two primary datasets:

#### FEMA National Risk Index Data

The FEMA National Risk Index is a composite measure designed to help communities understand their relative risk from natural hazards. In this assignment, the primary variable of interest is the National Risk Index composite score, which summarizes overall disaster risk at the county level. The dataset also includes composite risk scores and component measures related to expected annual loss, social vulnerability, and community resilience. The analysis compares county-level risk score distributions across states to assess how California counties compare with those in other states.

#### American Community Survey (ACS)

Demographic estimates by race and ethnicity were obtained from the 2023 ACS 1-year county-level dataset. These population counts were used to calculate exposure-weighted averages of hazard risk across racial and ethnic groups.

## References

Federal Emergency Management Agency (FEMA). (2025). National Risk Index. https://www.fema.gov/flood-maps/products-tools/national-risk-index.

U.S. Census Bureau. (2023). American Community Survey 1-Year Estimates.
https://www.census.gov/programs-surveys/acs.