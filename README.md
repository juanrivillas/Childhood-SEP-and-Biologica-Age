# Early-life-inequalities-and-biological-aging-Colombia-

This repository contents data frames, scripts, results, and supplementary material of the research project "Social patterning of chronic cardiometabolic conditions and biological aging using SABE aging survey data in Colombian population".

Please note that there are four codes in this repository covering five main steps described below:

Code 1. Data manipulation steps and imputation missing data. This covers than initial cleaning and data exploration, understanding the missing value patterns, and 
apply Missing completely at random (MCAR) imputation procedures.

Code 2. Transformation data. This Markdown covers tidying data, data processing, and preparation for analysis. This step includes: importing of imputed data base, vector transformation (re-coding, standardizing values, and creating new functions, and combination of vectors not present in the data such as ACEs, comorbidities, BMI) and computing frequency tables.

Code 3. Data visualization and statistical testing. This Markdown covers basic statistics to summarise the data (Mean, Median, Mode, Outliers, errors), describe distribution and spreading of the data (plotting charts), measure the variability in the data (inter-quartile range, variance, SD, FWHM), quantify the strength of associations between variables (Pearson correlation coefficient), and asking questions about data (correlation matrices) and clustering.

Code 4 BHS Calculation. The Markdown contains main working parts: calculate the relevant quartiles for the given combination of biomarkers and reference choice, get the score for each individual biomarker, and calculate the aggregated score by sub-systems (In this case only two: metabolic and cardio systems).

Code 5. Regression tables.

