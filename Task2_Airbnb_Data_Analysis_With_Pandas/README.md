# New York Airbnb Listings – Data Cleaning & Analysis

This project analyzes Airbnb-style property listings for New York to understand pricing, availability, and neighbourhood trends.

## Key Tasks
- Data loading & Initial Exploration
- Data Cleaning
- Data Enrichment
- Data Analysis

Project tasks
1. Data Loading and Initial Exploration
Load the dataset using Pandas.
Display basic information (.info(), .describe(), .head()).
Check for missing values, duplicated rows, and unusual data types.

2. Data Cleaning
Convert price fields (e.g., "$2,100.00") to float.
Parse dates (e.g., last_review) into datetime objects.
Handle missing values in critical fields like reviews_per_month, host_name, and neighbourhood_group.
Remove irrelevant rows (e.g., listings with zero availability or price).

3. Data Enrichment
Create a price_per_booking column using price and minimum_nights.
Bucket availability into categories:
Full-time (availability > 300)
Part-time (100–300)
Rare (<100)

4. Data Analysis Using Pandas
Answer the following using Pandas:

What are the top 10 most expensive neighborhoods by average price?
What’s the average availability and price by room type?
Which host has the most listings?
How does average price vary across different boroughs or districts?
How many listings have never been reviewed?
Write a summary of 3–5 key insights you found through your analysis


## Key Findings
- Most expensive neighbourhood_group is Manhattan with an average price of $1,182.95
- Hotel room has the highest average availabilty of 293.67 and average price of $36,431.21 amongst the different room types.
- 6,343 listings have never been reviewed.
- Some hosts have many listings. 
 

## Files Included
- New York Airbnb Listings Data Analysis.ipynb – Full code & analysis
- New York Airbnb Listings Dataset.csv

## Link to the Dataset
- `New York Listings.csv` – Dataset link (https://data.insideairbnb.com/united-states/ny/new-york-city/2025-10-01/visualisations/reviews.csv)


## Technologies Used
- Python
- Jupyter Notebook