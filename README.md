<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="50"/>

# Web Scraping - Caterpillar :tractor:

*Bruna Ferreira Santos*

*Data Analysis Full Time FEB 2021, Paris, February, 22, 2021*

## Content
- [Project Description](#project-description)
- [Collecting the Data](#collecting-the-data)
- [Workflow](#workflow)
- [Improvements](#improvements)
- [Links](#links)

## Project Description
The goal of this project was to collect information from Caterpillar's new equipment through web scraping. 

## Collecting the Data

```GET method:```

1. Two data access with request module (headers and normalize JSON)
2. One data access with Selenium and BeautifulSoup (webdriver, execute script, find all tables)

### The type of website 

- [ ] Static

- [X] Restful API Based

- [X] Dynamic

## Workflow

1. To access the data, first I retrieved the names of all types of equipment displayed on the page, clean and store them into a list.
2. Then, I lopped to access the 3 main characteristics of each model from the selected equipment - that are exposed in the page.
3. After having the information in a Dataframe, I started my Data Cleaning and Feature Organization.
4. With adequate data, I enabled access to MySQL and created the excel file.
5. To go further, I accessed the page of each model from all the types of equipment with Selenium, where I needed to click to 'expand' the information. 
6. I looped trou all the pages retrieving and storing (concat) the information into a data frame.
7. Data Cleaning (in processing)

## Improvements

## Links

