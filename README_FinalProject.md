# Final ADA project

##Topic: Hormonal contraceptive Use and Anemia Severity Among Non-Pregnant women aged 15-49 in Ghana; DHS data,2022.

## Project Description
This project investigates whether current contracpetive use is associated with 
anemia severity among non-pregnant women aged 15-49 years in Ghana,
using data from the 2022 Ghan Demographic and health Survey(DHS). 
A secondary objective assesses whether the association differs by hormonal 
method type(pill,injectables,implants), examining the effect modification 
through interaction modeling and subgroup analysis.
The project is an academic project submitted in an Advance Data Analysis(ADA) 
class in the Washington University MPH program to practice working with
real-world data in R markdown.

##Data
-Data source: The Demographic and Health Survey(DHS) from Ghana, 2022

-Population: 16,251 non-pregnant Ghanain women aged 15-49 years
-Country-Ghana
-Year- 2022
-Variable
    -Outcome: Anemia severity(not anemic, mild, moderate, severe)
    -Exposure: Current contraceptive methods were categorized into 
      ‘no method’, ‘non-hormonal’, and ‘hormonal’. 
    -Effect modifier: hormonal method type (implants, injectables, pills) 
    -Covariate: age, parity, and education
    -Other descriptive variables: Region, Residence, BMI, Religion,Wealth Index


## Files Included
- `DHS_COntraceptive.sav`: Cleaned version of the Class 1 survey dataset
- `DHS_FINAL PROJECT.Rmd`: R mackdown used to summarize, visualize and 
                           analyse the data.
- `README.md`: This file

## What the Code Does
- Reads in the survey dataset
- Performs basic data cleaning (renaming columns, filtering,recoding)
- Creates summary statistics 
  (contraceptive type,anemia, wealth,education,parity,religion,region,
  Residence(urban,rural,age, BMI))
- Generates a tables to visualize the data
- Ordinal logistic regression
-Adjusted models
-Effect modification analysis
-Subgroup analysis

##Software Requirements
-R version 4.2 +
-R packages;
  -Haven
  -MASS
  -table1
  -lmtest
  -dplyr
  -broom
  -Knitr
## How to Run the Code
1. Download or clone this repository to your computer
2. Open `DHS_COntraceptive.sav.Rmd` in RStudio
3. Make sure your working directory is set to the folder where the files are
saved
4.Run the data cleaning and management section
5. Run descriptive statistics
### Ordinal logistic regression
6.Run model 1(main association)
7. Run model 2 (adjusted model)
8. Run model 3 (interation model)
9. Run subgroup analysis model for hormonal users only
10. Brants test of proportional odds assumption

### Multinomial logistic regression
11.Run model 1(main association)
12. Run model 2 (adjusted model)
13. Run model 3 (interation model)
14. Run subgroup analysis model for hormonal users only
15.Multinomial regression assumptions




## Author
- Name: Evelyn Nketiah Annor
        MPH student(Epidemiology and Biostatistics)
        Washington University in St. Louis
- Course: Advance Data Analysis
-Date: December,2025

getwd()
