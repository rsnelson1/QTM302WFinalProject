# QTM302W:Sex and Covid Mortality Disparities

### Winni Weng and Ruth Nelson at Emory University

## Objectives:
This project aims to investigate whether Covid mortality rates differ based on Sex and whether they hold true regionally and overtime. 

## Methods
The data used in the research project is collected by the Centers for Disease Control's (CDC) National Center for Health Statistics (NCHS) and accessed from the their website under "Provisional Covid-19 Deaths by Sex and Age". Before analyzing the data, the data was "cleaned" to enhance its usability. The observations under "New York City" were combined with "New York" state, the 16 age range groups were refactored to fall under 5 groups (infant, child, young adult, adult, and senior), and an additional "seasons" column was generated based on the months. Along with our visulizations, the project utilized methods including ANOVA tests and t-tests to determine the statistical significance of our findings. The null hypotheses were rejected if the p-values were less than 0.05. 

## Platforms and Languages
This project is performed in R version 4.0.3 using tidyverse, plotly, and usmap packages. 

- Tidyverse: A system of packages for data manipulation, exploration, and visulization. 
- Plotly: A package that creates interactive web-based graphs. 
- Usmap: A package that contains information regarding the US states that allows for plotting of the U.S. map.

## Project Description
This project explores a dataset, "Provisional Covid-19 Deaths by Sex and Age", published by the CDC. This dataset is upated daily and contains information on Covid deaths, Pnemonia deaths, and Influenza deaths within the United States and territories. The dataset also contains information on the sex, date of death, and age group of the indivual who died. Using this dataset we plan to see if Covid mortality rates differ based on sex. Specifically if these difference are significant and if they hold consistent across age groups; by state; and throughout the course of the pandemic. This project maps the differences in Covid mortlaity between sex, across age groups, across the different U.S. states, seasons, years of the pandemic. It also attempts to account for the statisical reasoning behind why the Covid mortality disparity is so drastic in certain states. The main visualizations used are barplots, tables, and choropleth maps. To test for statistical significance between Covid mortality across age, sex, age and sex, sex and seasons, and sex and year we employed a two-way anova test. In addition, a one way t-test was utilized to determine the statistical signifcance between male covid death percentages across the states and 50%. However, due to the limitations of the dataset we were unable to address "the why" behind our findings. In addition, the dataset limited us from utilizing more statistical methods, such as regressions, as variables, such as age, were given as a categorical variable. The nature reserach question prevents us from conducting expirements, we are only uncover trends within existing data to find associations rather than causation. For our next steps we plan to look at the specific factors that may account for the regional difference and general difference between sex and covid mortality. 

## Instructions For Getting Started
**1) Clone the Repository:**  if you plan on working with the repository locally, clone the repository using Git. First open the repository page and click on the green "Code" button and copy the repository's URL and use the "git.clone" command

**2) Install renv in R environment:** run "install.packages("renv")

**3) Initalize renv in the Project:** using the cloned repository, go to repository's folder in RStudio and run renv::init()

**4) Restore the Project Environment Using renv:** to restore the necessary R packages for this project run renv::restore(). This will install the required packages and versions specfied in the projects renv.lock file 

**5) Work with Project:** Now that the R environment contains all the required packages and data, you can analyze, visualize, and manipulate the data in the repository. 

## Directory Structure
![image](<img width="421" alt="Screen Shot 2023-08-02 at 9 15 04 PM" src="https://github.com/rsnelson1/QTM302WFinalProject/assets/139489541/3b3d6e24-27c3-4ec3-8792-dcc68380fec4">)

    
## Contact Information: 
Winni Weng (wweng7@emory.edu) and Ruth Nelson (rsnelso@emory.edu)
