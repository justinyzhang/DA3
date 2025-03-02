# DA3
Prediction with Machine Learning for Economists

The repository is setup for assignment submission at CEU

The raw data "merg-2014-emp is too big to upload here.

I use the Claude AI to help me with the code.

Introduction
This study analyzes the determinants of hourly earnings in legal occupations using data from the CPS dataset. Four linear regression models with increasing complexity were constructed to predict hourly earnings (earnhre), calculated as weekly earnings divided by weekly hours worked.
Data and Methodology
The analysis used a dataset of 1,743 individuals in legal occupations (occupational codes 2100-2160) after removing outliers. Four OLS regression models were developed with progressive complexity:
Model 1 (Gender + Age): Includes only basic demographic factors.

Rationale: Gender and age are fundamental demographic variables that typically influence earnings across occupations.

Model 2 (+ Education): Adds education years to Model 1.

Rationale: Education is particularly important in legal professions where advanced degrees are common and often required.

Model 3 (+ Experience & Race): Adds work experience and race indicators to Model 2.

Rationale: Experience captures career progression, while race variables account for potential demographic disparities.

Model 4 (+ Marriage & Non-linear Effects): Further adds marital status, non-linear experience effects (exp²), and ethnicity.

Rationale: The squared experience term captures diminishing returns to experience, while marital status may reflect social factors affecting earnings.
