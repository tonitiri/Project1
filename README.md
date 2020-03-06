Marathon_Analysis_Project
This project is an analysis of marathon competition data, country demographic data and regional weather data for KU Data Analytics Bootcamp

-- Project Status: [Completed]
Project Intro/Objective
The purpose of this project was to identify emergent phenomenon from data contained in Olympic Medal data in Marathon events and other other datasets or sources that provide context and justy.

Methods Used
Data Collection
Data Cleaning
Data Analysis
Data Interpretation
Data Visualization
Technologies
Python libraries:
pandas
matplotlib
requests
numpy
stats
Json
os
Project Description
Data sets:
Kaggle
Olympic Medal Data - csv
World Marathon Majors - csv
World Bank
GDP Data - csv
CIA World Book - JSON dump
World Weather Online - API call
The project started by exploring 100 years of Olympic marathon medal data in which the sudden rise and pronounced success of two African nations, Ethiopia and Kenya, was of interest. Many secondary sources were encountered where journalists and acedemics had looked into this. However, there was little to no data involved in their analysis. Consistent in the hyposthesis found in these sources were interests in the influence of demographics and benefit of climate and geography in training.

Initially there were challenges in cleaning the Olympic data, isolating the Marathon results, merging this with the data from the World Marathon Majors and standardizing labels and metrics. In order to collect the pertinent demographic data for each of the countries a JSON dump from the CIA World Book was sourced. In order to collect climate data an API call was utlized to gather 5 years of weather data for cities that held either major races or the olympics. The weather data for the African countries was approximated by refrencing their respective capital cities.

Needs of this project
data exploration/descriptive statistics
data processing/cleaning
data visualization
writeup/reporting
Getting Started
Clone this repo: https://github.com/dorisep/Marathon_Analysis_Project.git

(for help see this tutorial).

Raw Data is being kept here within this repo.

offline data for Jonathan_Project01.ipynb *athlete_events.csv *Female_Elite_Berlin.csv *Female_Elite_Boston.csv *Female_Elite_Chicago.csv *Female_Elite_London.csv *Female_Elite_New_York.csv *Female_Elite_Tokyo.csv *Male_Elite_Berlin.csv *Male_Elite_Boston.csv *Male_Elite_Chicago.csv *Male_Elite_London.csv *Male_Elite_New_York.csv *Male_Elite_Tokyo.csv

offline data for project1_GDPVsMedals.ipynb *athlete_events.csv *API_NY.GDP.MKTP.CD_DS2_en_csv_v2_103640.csv

offline data for GroupProject.ipynb

uses major_marathon_men.csv and major_marathon_women.csv from Jonathan_Project01.ipynb
uses gdp_data from project1_GDPVsMedals.ipynb
Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
Featured Notebooks/Analysis/Deliverables
Notebooks
Data Visualizations
Written Analysis
Presentation
Contributing Members
Adam Blinn|github|LinkedIn|

project1_GDPVsMedals.ipynb
Written Analysis
Presentation
Jonathan Smith|github|LinkedIn|

Jonathan_Project01.ipynb
Written Analysis
Taiwo Onitiri|github|LinkedIn|

GroupProject.ipynb
Written Analysis
Edward Doris|github|LinkedIn|

CIA_WFB_Json.ipynb
Historical_majors_weather.ipynb
Written analysis/final edit
Presentation
