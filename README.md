#PROJECT OVERVIEW
This project aims to carry out analyses on past aviation accidents and identify airplane makes and models

#BUSINESS UNDERSTANDING
As part of its strategic growth plan, our company is seeking to diversify into the aviation industry by purchasing and operating aircraft for both commercial and private enterprises. 
The insights that have been obtained after analysis will guide the aviation division in making informed investment decisions and developing effective risk management strategies for fleet acquisition.
KEY BUSINESS QUESTIONS
1.Which airplane makes have the lowest risk profile in terms of aviation accidents?
2.Which airplane models experienced the least number o fatal injuries in aviation accidents?
3.Does the number of engines impact safety on flights?

#DATA UNDERSTANDING AND ANALYSIS
The dataset was obtained from Kaggle(https://www.kaggle.com/datasets/prathamsharma123/aviation-accidents-and-incidents-ntsb-faa-waas?resource=download&select=airline_accidents.csv). 

It was compiled by the National Transport and Safety Board.

The dataset contains data on aviation accidents over the years.
Columns that are key to our analysis include:
    Event.Id 
    Make
    Model
    Total.Fatal.Injuries
    Total.Uninjured

Columns with too many missing values that are not used in our analysis are removed entirely(Latitude, Longitude, Airport.Code and Airport.Name)



