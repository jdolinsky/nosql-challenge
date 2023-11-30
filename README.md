# MongoDB Challenge
## Overview
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. Import and evaluate establishment data using MongoDB and pymongo.

## Part 1: 
* Import the data provided in the [establishments.json](Resources/establishments.json) file from the Terminal  
* Create an instance of the Mongo Client

## Part 2:
* Add a new establishment record to the database
* Make updates to the record
* Remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted
* Cast certain fields to integer and decimal types

## Part 3: Exploratory Analysis

* Query the data to find establishments with hygiene score equal to 20
* Find establishments in London that have a rating greater than or equal to 4
* Find top 5 establishments with a rating of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"
* Find establishments in each Local Authority area that have a hygiene score of 0. Sort the results from highest to lowest, and print out the top ten local authority areas

## Technologies
MongoDB, pandas, PyMongo

## Data Source
UK Food Standards Agency (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB