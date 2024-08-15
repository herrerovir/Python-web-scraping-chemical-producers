# :factory: Web Scraping: largest chemical producers worldwide

This repository contains an end to end data analysis project on the largest chemical companies in the world using Python. 

## Table of content
 - [Intro](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Introduction)
 - [Goal](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Goal)
 - [Project Overview](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Project_Overview)
 - [Dependencies](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Dependencies)
 - [Technical skills](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Technical_skills)
 - [Data set](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Data_set)
 - [Data Cleaning](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Data_cleaning)
 - [Data Exploratio](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Data_exploration)
 - [Data Visualization](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Data_visualization)
 - [Conclusion](https://github.com/herrerovir/Web-scraping-largest-chemical-producers-worldwide/blob/main/README.md#Conclusion)

## Introduction
This data analysis project is focused on web scraping Wikipedia data using Python. 

The purpose of this work is to extract relevant data from Wikipedia to obtain meaningful information about the largest chemical producing companies in the world in the year 2021.

In this project, a general analysis of chemical companies is performed using Python in order to discover valuable information. The analysis workflow includes essential steps such as data extraction, data cleaning, data exploration, data analysis and data visualization.

## Goal
The **overall** objective of this project is to scrap from the Wikipedia website all relevant information on the largest chemical producers by sales in the year 2021. Once the data has been collected, it will be preprocessed to undergo exploration and analysis in order to later visualize the significant results obtained. 

Through the data analysis, it is expected to find answers to the following points:

* Best-selling chemical companies in the world
* Fastest growing companies in the world
* Countries with the largest amount of successful chemical companies in the world
* Best-selling Geman chemical companies
* Fastest growing German chemical companies

## Project overview
   1. Web scrape data from Wikipedia using Python
   2. Perform data preprocessing to clean and prepare the scraped data
   3. Data explotarion to find missing values, outliers, anomalies or patterns
   4. Data visualization to communicate the information obtained during the analysis
   5. Conclusion

## Dependencies
The following tools are necessary to carry out this project:

* Python 3
* Jupyter Notebooks
* Python libraries: 
    - BeautifulSoup
    - Requests
    - Numpy
    - Pandas
    - Matplotlib.pyplot
    - Seaborn

## Technical skills
The following skills were used throughout the implementation of this project:

* Web scraping
* Data cleaning
* Data exploration
* Data visualization

## Data set
Data collection was achived by means of scraping techniques using the BeautifulSoup Python library.

The data set consists of:
* 50 entries
* 5 columns

**Data source:** [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_chemical_producers)

## Data cleaning
To ensure the integrity and reliability of the data obtained by scraping the Wikipedia website, it was necessary to clean it. 

To this end, column names were modified to make them more informative and improve readability; numeric values were transformed from string to integer and float type and underwent minor changes to conform to the metric decimal system and data that were transferred with errors were also corrected to ensure their reliability.

## Data exploration
To ensure that the data obtained from the analysis is accurate and reliable it is essential to handle duplicate values, missing values, outliers, as well as to find inconsistencies and patterns in the data.

No missing, duplicate or out-of-range values were found in this data set. The incorrectly transferred values were fixed in the previous step and no more errors were found. In addition, a new feature was created from the “Headquarters” column to obtain more precise information on the country of origin of the companies.

## Data visualization
Data visualization plays a crucial role in data analysis, as it is the stage at which the conclusions drawn from the analysis are effectively communicated.

This stage focuses on creating visual representations of the insights gained during the analysis. The Python libraries Matplotlib and Seaborn were used for this purpose.

## Conclusion
In conclusion, this project successfully analyzed the world's leading chemical producing companies using Python. 

As expected from this project, the following questions were answered:

* **Best-selling chemical companies in the world**
  
![Top 5 best selling chemical companies in 2021](https://github.com/user-attachments/assets/f063d00a-0ab1-4bba-92a8-d1fbd4afca51)

* **Fastest growing companies in the world**
  
![Top 5 fastest growing chemical companies in 2021](https://github.com/user-attachments/assets/0d2d6bf9-b61b-4c5c-8fcd-60316505c628)

* **Countries with the largest amount of successful chemical companies in the world**

![Distributioin of the most sucessful chemical companies by country in 20211](https://github.com/user-attachments/assets/1b532be0-94a3-445d-b280-f3d26ab7c464)

* **Best-selling Geman chemical companies**

![Top best selling German chemical companies in 2021](https://github.com/user-attachments/assets/36b69fb5-2e64-4c49-8500-26d4ede5d52b)

* **Fastest growing German chemical companies**

![Top fastest growing German chemical companies in 2021](https://github.com/user-attachments/assets/91821b49-903c-417b-9ac6-40b67d886ea8)


Looking ahead, there are several areas that are worthy of further exploration:

* Develop advanced predictive models: Use machine learning algorithms to build predictive models that can accurately assess annual growth and revenue for these chemical companies. 

* Expand the data set: Increase the robustness of the analysis by incorporating a larger and more diverse data set.
