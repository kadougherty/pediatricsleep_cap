# Predicting private health coverage in the United States

*This project uses the Census Bureau Data API but is not endorsed or certified by the Census Bureau.*

## Data
The US Census Bureau collects demographic data, on topics such as employment, income, education, ancestry, household information as well as health care coverage, from 1% of the population each year as a part of a program called the American Community Survey. Each record in the dataset represents one individual surveyed, and all records are de-identified. The data are publicly available for download or retrieval from the US Census Bureau API. The most recent survey publicly availble at this API is from 2019. (Note data from 2020 are available to download in csv files).

This project will call the American Community Survey Public Use MicroSample (PUMS) API for data from 2019. Data is saved from a subsample of records from each state and DC. 


Below are links for information on the American Community Survey:
1. [American Community Survey (ACS)](https://www.census.gov/programs-surveys/acs/)

2. [American Community Survey Data via API ](https://www.census.gov/programs-surveys/acs/data/data-via-api.html)

Here is the address for information on variables that can be retrieved on the API

3. https://api.census.gov/data/2019/acs/acs1/pums/variables

Calls are made with python code written in utils.py[utils.py] 
by using this address https://api.census.gov/data/2019/acs/acs1/pums/ followed by a query statement

## Repo organization
Python code written for data retrieval, wrangling, exploration, and modelling is organized in Jupyter notebooks. Notebooks are numbered consecutively, as they were run for the project.

1. Data Wrangling[1.census_healthinsurance_datawrangling.ipynb]
2. Defining variables[2.census_healthinsurance_definingvars.ipynb]
3. Exploration Data Analysis[3.census_healthinsurance_eda.ipynb]
4. Preprocessing for Model Development[4.census_healthinsurance_preprocessing_trainingdev.ipynb]
5. Modelling and Modelling Selection[5.census_healthinsurance_modeling.ipynb]
6. Assessing the Final Model[6.assessing%20final%20model.ipynb]









