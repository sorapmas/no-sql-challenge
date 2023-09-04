# NOSQL-CHALLENGE

## Background:
This respistory is a coded analysis research with numerous dataframes, documents, and overall data extracted from our findings based off a research in order to help journalists in the UK Food Standards Agency and food critics decide where to focus future articles where they evaluate various establishments across the United Kingdom.

This repository contains the following:

    ANALYSIS
- ***NoSQL_setup_starter.ipynb:*** A jupyter notebook used to set us up for the analysis.ipynb. This file was used to import our JSON file, import our dependencies, confirm that the JSON file was properly imported, and assign the collection in that was loaded from the file to a passing variable so that way it's available to use for later. 
- ***NoSQL_analysis_starter.ipynb:*** Another jupyter notebook used to update the databse, analyze, and extract information we're finding to answer the following four questions.
1) Which establishments have a hygiene score equal to 20?
   There are 41 establishments who have a hygiene score equal to 20.
2) Which establishments in London have a 'RatingValue' greater than or equal to 4?
   There are 33 establishments in London with a rating value of greater and equal to 4.
3) What are the top 5 establishments with a 'RatingValue' of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
   The top 5 establishments with a rating value of 5 are "Howe and Co Fish and Chips - Van 17", "Atlantic Fish Bar", "Plumstead Manor Nursery", "Iceland", and "Volunteer"
4) How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
    There are 55 establishments within the Local Authority area who have a hygiene score of 0, heres a preview on the top 10 establishments in that area
   
<img width="208" alt="Screenshot 2023-09-04 at 3 03 51 PM" src="https://github.com/sorapmas/no-sql-challenge/assets/128443029/aff2c6e2-99bf-4f71-bdb9-4bd3a1604133">
.


   
       RESOURCES
- ***establishments.json:*** A JSON file which stores all of the data such as the establishments collections and which ratings each establishments have, as well as their address, hygiene score given, business type, list goes on! We use this as a reference for our analysis.
  
