# A Study of Hate Crimes in 2009 and 2017: 
### There have been many discussion around the prevelance of hate crimes in the United States, particulary as we head towards the upcoming 2020 Presidential election. As such, this team thought that it would be apropos to examine and analyze the prevelance of such crimes, and which factors, be they political or socioeconomic in nature, have the greatest impact on the total and relative (to population size) numbers of hate crimes across the country.

## Hypothesis:

* Each team member made a certain hypothesis about hate crimes and how environmental factors could potentially affect outcomes. Each team members hypothesis is documented below.

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

## Code Files:

## Images:


The technical requirements for Project 1 are as follows.

* [ ] Use Pandas to clean and format your data set(s)

* [ ] Create a Jupyter Notebook describing the **data exploration and cleanup** process

* [ ] Create a Jupyter Notebook illustrating the **final data analysis**

* [ ] Use Matplotlib to create a total of 6-8 visualizations of your data (ideally, at least 2 per "question" you ask of your data(per person))

* [ ] Save PNG images of your visualizations to distribute to the class and instructional team, and for inclusion in your presentation

* [ ] Optionally, use at least one API, if you can find an API with data pertinent to your primary research questions

* [ ] Create a write-up summarizing your major findings. This should include a heading for each "question" you asked of your data, and under each heading, a short description of what you found and any relevant plots.

Code Files:

- Zach: hate_crime.ipynb

- Max:

- Jackson: 
