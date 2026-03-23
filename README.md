# Executive Function as a Predictor of Cognitive Performance in Adults

## Overview
This project examines whether executive function predicts overall cognitive performance using a large, publicly available dataset (MIDUS). A secondary data analysis was conducted to evaluate the relationship between executive functioning and cognitive outcomes across adulthood.

## Research Question
Does executive function predict cognitive performance in adults, after accounting for age?

## Study Design
Type: Secondary data analysis
Design: Cross-sectional
Approach: Correlational
Statistical Method: Multiple Linear Regression

## Dataset
Data were obtained from the MIDUS (MIDUS 3, Project 3: Cognitive Dataset).
Sample Size: N = 3043
Population: Adults (ages 42–94)
Measures: Standardized cognitive assessments (BTACT battery)

## Variables
- Outcome Variable: C3TCOMP — Cognitive Performance (Composite Score)
Overall measure of cognitive performance
Continuous (standardized score)
Higher values indicate better performance
- Predictor Variable: C3TEF — Executive Function
Composite measure of executive functioning
Includes cognitive control and working memory processes
Continuous (standardized score)
- Control Variable: C1PRAGE — Age
Participant age in years
Continuous variable
Included to account for age-related cognitive differences
- Optional Variable (Exploratory): C3TBKTOT — Working Memory
Backward counting task performance
Used as an additional indicator of executive functioning

## Results
Executive function was a strong positive predictor of cognitive performance (β = 0.83, p < .001).  
Age was a small but significant negative predictor (β = -0.005, p < .001).  

The overall model was significant, F(2, 3040) = 7125, p < .001, explaining a large proportion of variance in cognitive performance (R² = 0.82).

## Interpretation
These findings suggest that executive function plays a critical role in overall cognitive performance, even after accounting for age-related decline. This supports theoretical models emphasizing executive control as a central component of cognitive functioning across adulthood.

## Relevance
Understanding how executive function contributes to cognitive performance has implications for neuropsychological assessment and rehabilitation, particularly in populations experiencing cognitive decline or neurological impairment.

## Files
- M3_P3_BTACT_N3291_20210922.sav (dataset)
- PsiChi.R (analysis code)

## Author
Lilly Fattizzi
University of Central Florida
