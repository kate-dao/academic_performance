# Statistical Analysis of Factors Influencing College GPA
## Introduction
This project explores the factors that influence college students' GPA using survey data from nearly 10,000 undergraduates across 119 U.S. colleges. Motivated by my interest in educational outcomes and data-driven analysis, I used regression modeling and statistical testing to examine how variables such as gender, class year, work status, and lifestyle behaviors relate to academic performance.
## Methodology
This project uses survey data from 9,890 undergraduate students across 119 four-year colleges, collected by researchers at the Harvard School of Public Health in 2001. The analysis was conducted using R, primarily leveraging the tidyverse suite for data manipulation and visualization, and base R for statistical modeling.

The methodology consists of the following steps:

### 1. Data Exploration and Cleaning

- Imported the dataset (college.dta) and examined its structure and summary statistics.

- Handled missing values, particularly in GPA, to assess the randomness of non-responses.

- Created relevant categorical and binary variables to support analysis (e.g., class year, gender, work status, substance use).

### 2. Descriptive Analysis

- Calculated key summary statistics, including average GPA, gender distribution, and the proportion of students involved in activities such as working, fraternity/sorority membership, and marijuana use.

- Identified the number of students with missing GPA values and assessed the likelihood of non-random missingness.

### 3. Regression Analysis

- Performed linear regression to examine how GPA is affected by variables such as gender (male), work status (work), and class year (freshman, sophomore, junior, senior).

- Ran subgroup analyses, including regressions for male students only, to explore variation across class years.

- Included additional controls in extended models: marijuana use, drinking behavior (lightdrinker, moddrinker, heavydrinker), and age.

- Estimated predicted GPA values for specific student profiles based on regression coefficients.

### 4. Hypothesis Testing

- Conducted t-tests and F-tests to assess the statistical significance of individual and grouped coefficients.

- Tested hypotheses about differences in GPA across class years and between student subgroups, with a 5% significance level.

### 5. Model Evaluation

- Reported and interpreted adjusted R² values to assess model fit.

- Considered the potential for omitted variable bias and the limitations of the survey-based dataset.

