# Data Analysis using R



You can view the analysis report [here](https://vishnuvij.github.io/Data-Analysis-using-R/dataviz.html).

### Data Visualization with R

Spread of Influenza in the USA (1919–1951)
Author: Vishnu Vijayan (00806007)




### Introduction

Influenza is a contagious viral infection caused by influenza virus A or B. It mainly affects the upper respiratory system and has caused significant morbidity and mortality over time.

This project analyzes influenza outbreaks in the United States between 1919 and 1951, using data provided by Project Tycho, which makes historical epidemiological data accessible for research. The analysis relies on R and various visualization techniques to uncover patterns in influenza’s spread and impact.

### Problem Definition

Influenza epidemics have posed recurring challenges for public health due to the virus’s unpredictability and evolution. This project investigates the patterns of influenza spread and related mortality in the U.S. to identify:

How influenza spread changed over time

Regional differences in spread

The most affected states and cities

Death rates associated with influenza

### Objectives

The main objectives are to:

Analyze influenza spread across the USA between 1919–1951.

Visualize trends in influenza cases and deaths.

Identify states and cities with the highest and lowest average spread.

Investigate seasonal and yearly influenza patterns.

Provide insights that could support future epidemiological research.

### Methodology

All analyses were performed in R using the following packages:

tidyverse → Data manipulation & analysis

ggplot2 → Data visualization

ggpubr → Publication-ready plots

lubridate → Date and time handling

forcats → Factor handling

RColorBrewer → Color palettes

usmap → U.S. map visualizations

Workflow:

Import dataset from Project Tycho.

Filter influenza-related data.

Preprocess date fields to extract year/month.

Perform exploratory data analysis:

Yearly, monthly, state, and city-level trends

Mortality comparisons

Top 10 highest/lowest spread periods

Visualize findings with plots and maps.

### Results Overview

The analysis covers multiple perspectives:

Yearly trends: Highest incidence in 1950, lowest from 1924–1927.

Seasonality: Cases peaked during winter months (Dec–Feb).

State-level spread: Highest in Mississippi and Texas, lowest in Delaware and Vermont.

City-level spread: Erie reported the highest average cases and deaths.

Mortality:

New York had the highest influenza-related deaths among states.

Cities with high spread (e.g., Erie, New York) also showed the highest deaths.

Key Findings

Influenza incidence increased overall from 1919–1951.

Seasonal peaks aligned with winter.

Southern states were more affected than northern states.

Spread and mortality did not always correlate (e.g., Mississippi had high spread, but New York had highest deaths).

### Discussion

This project demonstrates how historical epidemiological data can be leveraged using data visualization in R to reveal insights into disease patterns. While the analysis focuses on influenza from 1919–1951, the same methods can be extended to other infectious diseases or timeframes.

Conclusion

Through extensive visualization, this project answers key research questions about influenza spread in the U.S. during the early 20th century. The findings may serve as a foundation for further epidemiological studies, policy planning, and preparedness strategies.


### References

White, Tim (2014). What is the Difference Between an "Injury" and "Disease" for Comcare Commonwealth Compensation Claims?

Mayo Clinic – Flu Symptoms & Causes

FDA – Influenza Information

Elert, E. (2013). FYI: Why is There a Winter Flu Season? Popular Science.



