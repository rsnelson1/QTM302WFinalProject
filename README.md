# QTM302W:Sex and Covid Mortality Disparities
## Binder Badge

## Winni Weng and Ruth Nelson at Emory University

## Objectives:
This project aims to investigate whether Covid mortality rates differ based on Sex and whether they hold true regionally and overtime. 

## Methods

## Platforms and Languages
This project is performed in R using tidyverse, plotly, and usmap packages. 

- Tidyverse: A system of packages for data manipulation, exploration, and visulization. 
- Plotly: A package that creates interactive web-based graphs. 
- Usmap: A package that contains information regarding the US states that allows for plotting of the U.S. map.

## Project Description
This project explores a dataset, "Provisional Covid-19 Deaths by Sex and Age", published by the CDC. This dataset is upated daily and contains information on Covid deaths, Pnemonia deaths, and Influenza deaths within the United States and territories. The dataset also contains information on the sex, date of death, and age group of the indivual who died. Using this dataset we plan to see if Covid mortality rates differ based on sex. Specifically if these difference are significant and if they hold consistent across age groups; by state; and throughout the course of the pandemic. This project maps the differences 

Next steps: looking at the specific factors that may account for the regional difference, or the environmental difference between sexes. 

## Instructions For Getting Started
**1) Clone the Repository:**  if you plan on working with the repository locally, clone the repository using Git. First open the repository page and click on the green "Code" button and copy the repository's URL and use the "git.clone" command

**2) Install renv in R environment:** run "install.packages("renv")

**3) Initalize renv in the Project:** using the cloned repository, go to repository's folder in RStudio and run renv::init()

**4) Restore the Project Environment Using renv:** to restore the necessary R packages for this project run renv::restore(). This will install the required packages and versions specfied in the projects renv.lock file 

**5) Work with Project:** Now that the R environment contains all the required packages and data, you can analyze, visualize, and manipulate the data in the repository. 

## Directory Structure

## Contact Information: 
Winni Weng (wweng7@emory.edu) and Ruth Nelson (rsnelso@emory.edu)
