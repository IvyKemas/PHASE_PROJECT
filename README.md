# Phase 2 Project

## Ivy's project

## Business Problem
Maison Real Estate Agency have decided to invest in the King County Area in the USA however, they want to be certain of the best ways to note where to invest their Capital in.

## Business understanding
Maison Real Estate Agency wants to invest in some areas of King County Area. The stakeholders of Maison Real Estate Agency want me to conduct an Analysis on the provided data, In order to provide accurate recommendations on the ways to carry out their investments therefore maximising their profits.

From the following analysis you may note that all tests condcted were conducted using price as the dependent variable. This is because it was the primary objective that Maison Real Estate Agency realizes positive results for their investments.

### What questions were asked during the analytics process?
* Do prices vary according to zipcode, if so which zipcodes have higher prices distribution?
* Is there a relationship between the prices and the square feet of the house?
* Is there a relationship between the number of bedrooms and the prices?
* Is there a relationship between the number of floors and the prices?
* Is there a relationship between the number of Bathrooms and the prices?

## In order to coduct the analysis , the following steps were implemented
* Data Mining
* Data Cleaning
* Data Exploration
* Feature Engineering
* Predictive Modelling
* Data Visualization


### Data Mining 
The following csv files were extracted for this analysis
kc_house_data.csv-The analysis was to be conducted here
column_names.md- This provvided abetter understanding of the(kc_house_data.csv)

### Data Cleaning
The following unclean data was dealt with using appropriate methods
* Missing Data
* Wrong Data Types

* **The unclean data was dealt with in the following ways**

* **Missing data**

* Creation of separate Categories for the missing Data and filling the values -This was to avoid messing with the data as I wasn't sure what would have been the reason this data was missing.

<img width="815" alt="cleaning1" src="https://user-images.githubusercontent.com/122665283/228152463-bd589471-5b5b-41f0-9b33-91e468cb825c.png">

* Using the median to fill in the missing values-

<img width="806" alt="cleaning3" src="https://user-images.githubusercontent.com/122665283/228154983-a34cbf84-7623-4753-ac17-645c71690a99.png">

* Using the mode to fill in the missing values-

<img width="557" alt="cleaning4" src="https://user-images.githubusercontent.com/122665283/228154996-bbf9421c-9fdf-45a3-8794-e8850b86862a.png">


* **Wrong Data Types**

Here I assigned the correct data type

<img width="534" alt="cleaning2" src="https://user-images.githubusercontent.com/122665283/228154955-85d5169b-1ac2-43a3-bc99-7efb191c8f5b.png">

### Data Exploration

* Here I did exploratory Data Analysis to understand some relationships and some descriptive statistics to better understand the variables.

**Descriptive Statistics**

<img width="644" alt="cleaning5" src="https://user-images.githubusercontent.com/122665283/228155026-cd3ab3a1-cf58-40b7-bb99-8ca66c6b11c0.png">

**Exploraty Data Analysis**

Here I tried to check for relationships in different variables

<img width="481" alt="cleaning7" src="https://user-images.githubusercontent.com/122665283/228155042-dbceb045-9e1b-46db-8ebf-0a901ec607dd.png">

### Feature Engineering

### Predictive Modelling

Here I used trained models to try predict

<img width="471" alt="cleaning8" src="https://user-images.githubusercontent.com/122665283/228155057-b7297308-a82f-46d3-87af-82e498940d5d.png">

### Data Visualization

Here I finally created visualizations from the trained model

<img width="302" alt="cleaning9" src="https://user-images.githubusercontent.com/122665283/228155074-f1fb5a72-f265-4bf3-8869-df7c4a4e75bf.png">

## Action 

- After completing the data science process I came up with appropriate recommendations to answer the Business Problem
- They include:-
* Invest in houses with higher number of bathrooms.
* Invest in houses with higher number of floors.
* Invest in houses with a bedroom range of 6-8
* Invest in houses with a higher number of square feet
* Invest in houses in the recommended zipcodes


## Summary
To propell the success of Maison Real Estate Agency as they begin to make investments , Data from one extracted, The data sets then underwent cleaning then Exploration . After wrangling the Data was used to create various statistical models and visualizations in order to establish appropriate actions to be undertook by Maison Real Estate Agency as the begin making investments. Various actions were suggested and business recommendations were yielded in the process.

## Conclusion
The goal of this project was to provide sound recommendations that Maison Real Estate Agency should follow when making investments in housing. Of course they would want to realise profits , that is why it was necessary to conduct the analysis to give great advice when it came to their investment process. From the analysis we have noted that Yes the data needed some extra research in order to understand it better, It was also necessary to prepare the data adequately in order to get the best out of the results. After building a model and using it to predict, with full confidence I can recommend that they Maison Real Estate Agency should, carry out their investments in the mentioned zip codes as they attract the highest prices, they should also invest in houses with higher number of bathrooms, on top of that they should invest in houses with a higher number in square feet to maximise their profits and finally they should aim for houses with about 7 bedrooms, not lesser than 5 or greater than 8 in order to realise maximum profits.




