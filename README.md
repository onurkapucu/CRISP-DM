# CRISP DM Analysis for AirBNB Seattle Data


## Motivation

This project aims to understand the prices and accomodation availability in Seattle throughout the year, using the 2016 data provided by AirBNB on Kaggle.

## Files

1 csv file:

calendar.csv : Consists of 4 columns: listing_id, date, availability and price. This is the dataset I used to run my analysis for availability and pricing for each listing throughout the year. 

1 jupyter notebook:

Seattle CRISP DM.ipynb: This is a Jupyter notebook using Python3 kernel. Guide by guide instruction for each step is available in the notebook.

## Libraries:

**numpy:** for numerical calculations
**pandas:** for easy handling of data using dataframes
**matplotlib:** for data visualization using plots

## Use

Follow the process in the jupyter notebook to read the csv files, clean the data and answer the following questions

## CRISP - DM Questions

Project targets to answer following business questions based on the dataset provided

1- When does each listing have the highest price?

2- When does Seattle has the most expensive night to stay?

3- When does Seattle have the most number of listings throughout the year?

4- Do hosts increase prices during Summer?

## Results

If we follow the order of questions that are asked above:


**1-** We first looked at all the data and tried to see if maximum prices are mostly marked during a certain time. 
However, this initial study had flaws such as some locations were only listed at those special dates and showing up as marked up price.

**2-** We have seen that just before the summer and through the holiday season, Seattle has more offerings.

**3-** We have seen that Seattle has a pike in accomodation during the summer and at the end of the year.
Then we wanted to understand if this increase in price is happening due to the new listings, so we reduced our db to listings with throughout the year offerings.

**4-** We have clearly seen the answer is YES


An analysis can be found on:

https://medium.com/@onurkpc/seattle-summers-are-beautiful-and-airbnb-hosts-know-it-ab66c1fe5bfc