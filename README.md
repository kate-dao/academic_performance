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

## Conclusion
This project set out to explore the factors associated with college GPA using survey data from nearly 10,000 students across 119 four-year U.S. colleges. Through descriptive analysis and linear regression modeling, I examined how variables such as gender, class year, employment during the school year, substance use, and drinking behavior relate to academic performance.

The results suggest that GPA is influenced by a combination of demographic and lifestyle factors. For instance, working during the academic year and certain behaviors like marijuana use showed a measurable association with lower GPA, while academic standing (e.g., being a senior vs. a freshman) also revealed significant differences. Gender differences were also observed, with male students, on average, reporting slightly lower GPAs than their female counterparts.

By testing specific hypotheses and comparing model performance using adjusted R², RMSE, and significance levels, this analysis provided insights into how different variables contribute to academic outcomes. Overall, the project highlights the value of data analysis in understanding student experiences and can help inform support strategies for improving academic performance in higher education settings.

This project also reflects my strong interest in using data to uncover patterns in human behavior and education, while strengthening my skills in statistical modeling, hypothesis testing, and real-world data interpretation.
