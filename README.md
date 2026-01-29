# Homework #2 (Visualizing FEMA National Risk Index Scores)
### Homework #3 (Pending)

## Purpose of This Project

This project focuses on designing and interpreting a data visualization using {ggplot2} to compare county-level FEMA National Risk Index (NRI) scores across US states, with particular emphasis on California. The primary objective is to apply principles of effective data visualization to communicate patterns in disaster risk across states. The assignment requires creating a polished visualization that meets specific design and accessibility criteria, including custom colors, clear annotations, captions, and alt text. The project also involves reflecting on visualization choices and explaining the rationale behind design decisions.

## Visualization Approach

The final visualization uses a ridgeline density plot to display the distribution of county-level NRI scores for each state. States are ordered by their median county score to highlight overall trends, and California is visually emphasized using custom colors. Median values are overlaid to improve interpretability and reduce ambiguity. Design choices prioritize readability, accessibility, and clear communication of the main takeaway.



## Repository Structure

``` bash
EDS-240-NRI-ACS-VIZ
├── .gitignore
├── EDS-240-NRI-ACS-VIZ.Rproj
├── HW2.qmd
└── README.md
```

## Data Access

This project uses the FEMA National Risk Index (NRI) dataset (2025 Release), which provides county-level measures of disaster risk across the United States. Only data from the 50 US states are included in this analysis and the territories are excluded.

#### FEMA National Risk Index Data

The FEMA National Risk Index is a composite measure designed to help communities understand their relative risk from natural hazards. In this assignment, the primary variable of interest is the National Risk Index composite score, which summarizes overall disaster risk at the county level. The dataset also includes composite risk scores as well as component measures related to expected annual loss, social vulnerability, and community resilience. The analysis compares distributions of county-level risk scores across states to assess how California counties compare to those in other states.

## References

Federal Emergency Management Agency (FEMA). (2025). National Risk Index. https://www.fema.gov/flood-maps/products-tools/national-risk-index.