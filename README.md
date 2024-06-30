# Employee-Attrition-Analysis


### Problem Statement
---
XYZ company which was established a few years back is facing around a 15% attrition rate for
a couple of years. And it's majorly affecting the company in many aspects. In order to
understand why employees are leaving the company and reduce the attrition rate XYZ
company has approached an HR analytics consultancy for analyzing the data they have. You
are playing the HR analyst role in this project and building a dashboard which can help the
organization in making data-driven decisions.


### ASK
---
The key business task is to identify the reason employees are leaving the company,  

1. Finding out total employees  
2. Calculating the attrition rate  
3. Finding out the reason for attrition  


### Data Preparation
---

The dataset used is provided by Unified Mentor Private Limited which was provided for my Data Analytics internship program.

Note - The XYZ is a fictional company.


### Tools Used

**RStudio** - Data cleaning, Analyzing, and Visualization  
**Tableau** - Data Visualization  



### Installing and Loading required packages
---

```r
install.packages(tidyverse)

library(tidyverse)
library(tidyr)
library(dplyr)
library(ggplot2)
library(janitor)
library(forcats) # to reorder by values, variables etc..
library(scales) # to use percent()

```

### Importing the Dataset in Rstudio
---

```r

employee_attrition_data = read.csv("F:/Rprojects/Rprojects/Projects to work/Employee Attrition data.csv")

```










