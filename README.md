# EXPLORING LONDON TRAVEL

## Project Description.
How do Londoners get around? Transport for London (TfL) is a vast public transport network that allows London's residents to efficiently travel around the UK's capital, to the tune of over 1.5 million journeys per day!
This project demonstrates how to analyze and format sales data stored in PostgreSQL using Python and SQL queries.

## INSTRUCTIONS
1. Write three SQL queries to answer the following questions:

1.1 What are the most popular transport types, measured by the total number of journeys? The output should contain two columns, JOURNEY_TYPE and TOTAL_JOURNEYS_MILLIONS, and be sorted by the second column in descending order. Save the query as most_popular_transport_types.

1.2 Which five months and years were the most popular for the Emirates Airline? Return an output containing MONTH, YEAR, and JOURNEYS_MILLIONS, with the latter rounded to two decimal places and aliased as ROUNDED_JOURNEYS_MILLIONS. Exclude null values and save the result as emirates_airline_popularity.

1.3 Find the five years with the lowest volume of Underground & DLR journeys, saving as least_popular_years_tube. The results should contain the columns YEAR, JOURNEY_TYPE, and TOTAL_JOURNEYS_MILLIONS.

## Key Features
- Connect to PostgreSQL database
- Extract and transform sales data
- Perform basic data cleaning and formatting
- Create summary reports and visualizations

## Files
- 'Exploring_London_travel.ipynb' → main Jupyter notebook with the code and analysis
- README.md file linked to this project

## Author
Enrique Velasquez
