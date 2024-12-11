# Exploratory Data Analysis (EDA) Code Notebook
### Project: Analyzing the Impact of Regional and Demographic Factors on Education Inequality
### Last Updated: December 11, 2024

## Team Members and Affiliations
Kevin Xie, Fay Yan, Claudia Yang, Karl Zhou<br>
QTM 302W, Technical Writing, Emory University

## Objectives
The primary objectives of this project are:

1. To analyze the impact of regional and demographic factors on educational disparities in the U.S.
2. To identify patterns in SAT scores and GPAs across different socioeconomic backgrounds.
3. Conducting descriptive statistical analysis of the dataset to summarize key trends.
4. Visualizing the data through appropriate plots and charts to uncover insights.
5. Identifying missing values, outliers, and data anomalies to ensure data quality.
6. Documenting the analysis process for reproducibility and collaboration.

## Project Description
This repository contains the Exploratory Data Analysis (EDA) Code Notebook, developed as part of our research to understand disparities in educational outcomes across the U.S. The analysis focuses on identifying patterns, trends, and relationships within the dataset to inform decision-making and highlight key insights.
### Research Questions
What regional and demographic factors contribute most significantly to disparities in educational outcomes in the U.S.?<br>
How do socioeconomic factors influence SAT scores and GPAs?
### Methods Used
Quantitative Analysis: Statistical summaries and tests to uncover relationships between variables.<br>
Visualization & Spatial Analysis: Graphical plots and maps to visualize trends across regions and demographics.<br>
Statistical Testing: Hypothesis testing to validate findings.<br>
### Results / Key Findings
Regional Variations: Significant differences in SAT scores and GPAs were observed across regions, with urban and suburban areas outperforming rural areas.<br>
Socioeconomic Influence: Higher household incomes and parental education levels strongly correlate with improved SAT scores and GPAs.<br>
Demographic Trends: Disparities exist across racial and ethnic groups, emphasizing systemic inequalities.<br>
### Future Directions
Comparison of pre and post-COVID-19 data to assess the pandemic's impact on educational disparities.<br>
Exploration of policy interventions aimed at reducing disparities.

## How to Use the Repository
### Prerequisites
R (for statistical analysis)<br>
RStudio (integrated development environment)<br>
Binder (for reproducibility and sharing)<br>
Required libraries for EDA (e.g., `ggplot2`, `dplyr`, `tidyr`, `summarytools`).<br>

### Instructions
1. Clone this repository:
```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```
2. Open the `EDA_Codebook.Rmd` file in RStudio or render the `EDA_Codebook.html` file for a preview.
3. To reproduce the results, execute the code blocks sequentially in RStudio.
### Rendering the Notebook
To generate the HTML file from `EDA_Codebook.Rmd`, run the following command in R:
```r
rmarkdown::render("EDA_Codebook.Rmd")
```
