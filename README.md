# A Study of Hate Crimes in 2009 and 2017: 
### There have been many discussions around the prevelance of hate crimes in the United States, particulary as we head towards the upcoming 2020 Presidential election. As such, this team thought that it would be apropos to examine and analyze the prevelance of such crimes, and which factors, be they political or socioeconomic in nature, have the greatest impact on the total and relative (to population size) numbers of hate crimes across the country.

## Hypothesis:

* Each team member made a certain hypothesis about hate crimes and how environmental factors could potentially affect outcomes. Each team member's hypothesis is documented below.

  * Max: "Intolerance is the first sign of an inadequate education." This quote by Aleksander Solzhenitsyn sums up a general belief about prejudice, that with education these attitudes can be erased. However, is this really the case? Through research, are we able to prove a correlation between people who graduate high school and lack of hate crimes?

  * Zach: It is well known that the factors that contribute to socioeconomic status affect crime rates around the world. Therefore, areas that experience higher rates of poverty, relatively low per capita income, and high rates of income inequality (according to the Gini Index), should also experience higher rates of hate crimes.

  * Jackson: In today’s divisive political climate, Democrats and Republicans often try to place blame on one another for various problems facing our society.  One of these problems, which is a huge source of media attention, is discrimination of race, religion, sexuality, and gender.  In this study, we will use the rates of specific hate crimes to measure the targeted attacks against these groups.  So, the question is, is there a correlation between political affiliation and race, religion, sexuality, gender-based discrimination?

## Resources:

* Each team member utilized the hate_crime.csv file to begin their analysis.

  * This dataset comes directly from the FBI Crime Data Explorer: Hate Crime Specific ---> https://crime-data-explorer.fr.cloud.gov/downloads-and-docs
    
    * Other than reducing the dataset to include only neccessary data (2009 & 2017), this dataset was well formatted and required minimal cleaning. 
  
* Zach: 

  * US Census API Wrapper ---> https://github.com/datamade/census
  
  * Gini Index: Folder (Gini Index CSV) ---> https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_10_1YR_B19083&prodType=table

* Max:

  * Hate Crime Socioeconomic Data: Cleaned hate_crime.csv was merged with US Census Data from API Wrapper in hate_crime.ipynb to create two seperate csv documents for each year of analysis.

    * hate_crime_socioeconomic_2009.csv
  
    * hate_crime_socioeconomic_2017.csv

  * US Census API Wrapper ---> https://github.com/datamade/census

* Jackson:

  * Election Data: 1976-2016-president.csv ---> https://electionlab.mit.edu/
  
  * US Census API Wrapper ---> https://github.com/datamade/census
  
* Presentation Tables (Type: Folder): This folder includes 4 total Excel files that contain the top 5 hate crime count and the top 5 hate crime rates (per 100,000 population) per year (2009 & 2017). These workbooks were utilized as visualizations in the Hate_Crime_Study PowerPoint presentation.

  * max_incidents_2009.xlxs
  
  * max_incidents_2017.xlxs
  
  * max_rate_2009.xlxs
  
  * max_rate_2017.xlxs

## Code Notebooks:

 * Zach: 
 
   * hate_crime.ipynb
 
 * Max:
 
   * max code book.ipynb
 
 * Jackson: 
   
   * bias_filtering_politics.ipynb
   
   * State Politic Change.ipynb
   
   * 2008_Election.ipynb
   
   * 2016_Election.ipynb

## Images:

 * Workflow:
 
   * The Triple Chiquita Flow.pdf
   
 * Zach (Folder):
 
   * Hate Crime Rate vs. Per Capita Income - 2009.png
   
   * Hate Crime Rate vs. Per Capita Income - 2017.png
   
   * Hate Crime Rate vs. Poverty Rate - 2009.png
   
   * Hate Crime Rate vs. Poverty Rate - 2017.png
   
   * Hate Crime Rate vs. Gini Index - 2009.png
   
   * Hate Crime Rate vs. Gini Index - 2017.png
   
 * Jackson (Folder):
 
   * DemVotingVsHateCrimeRate.png
   
   * DemVotingVsHateCrimeRate09.png
   
   * PercHCR2009.png
   
   * PercHCR2017.png
   
   * Political Change.png
   
   * Significant States DF.png
   
 * Max (Interactive Visualization Created via Plotly|Chart Studio):
 
   * https://plot.ly/~maximusrex/3
   
 * Group Images (Folder):
 
   * Hate_Crime_Count_per_State_2009_2017.png
   
   * Hate_Crime_Rate_per_State_2009_2017.png
   
   * DC_boxplot_2017.png

## Summary:

 * Hate_Crime_Study.pptx
 
   * Contains Final Presentation & Major Findings
   
     * Broken Down by Each Hypothesis (Individual Analysis)
   
   * Limitations of Dataset
   
   * Documents Washington D.C. as Major Outlier
