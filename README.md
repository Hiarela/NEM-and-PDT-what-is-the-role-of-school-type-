NEM and PDT: what is the role of school type?

This repository contains the code, data, and research paper for the study titled "Evaluating the Impact of High School Grades (NEM) on 2022 University Transition Test (PDT) Scores in Chile." The study examines how NEM scores affect PDT results across different types of schools, with a focus on exploring differences between public, subsidized, and private institutions.

Repository Contents:
Aravena__H__y_Avello__C_.pdf: The full research paper detailing the methodology, analysis, and findings. This paper examines the relationship between NEM scores and PDT scores, and includes robustness checks using alternative instrumental variables.
code.Rmd: This script performs the main analysis, including data cleaning, merging, and applying Ordinary Least Squares (OLS) and Instrumental Variables (IV) models to study the impact of NEM scores on PDT scores.
Robustness_check.Rmd: This script includes the robustness analysis, re-estimating the main effects using an alternative instrumental variable (SIMCE scores from fourth grade) to validate the consistency of the results across different school types.

Data:
The repository use:
1. NEM and PDT Scores: High school grades and university entrance test scores.
2. School Dependency Type: Indicates whether a student attended a public, subsidized, or private school.
3. Additional Socioeconomic and Demographic Variables: Used for control and analysis in the regression models.

How to Use the Code:
1. Install Required Libraries: The scripts require packages such as dplyr, stargazer, and AER for data manipulation, statistical analysis, and results formatting.
2. Run main_analysis_code.R: This script conducts the primary OLS and IV analyses.
3. Run robustness_check_code.R: This script replicates the main analysis with an alternative instrumental variable to verify robustness.

Results:
The analysis investigates whether the relationship between NEM and PDT scores varies across school types. The robustness check provides additional evidence by using SIMCE scores from fourth grade as an alternative instrumental variable.
