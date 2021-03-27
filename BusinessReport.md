# CapstoneProject
Final Capstone Project

Introduction / Problem:

An Australian entrepreneur has a pharmacy chain called “Priceline pharmacy”. He would like to expand his business to America. 
He wants to setup his first store in New York as it is one of the most popular city in America. 
To ensure he has the highest chance of success, he wants to find out which New York borough has the least amount of pharmacy per capita.  

Data:

In order to execute this plan, we need to have the number of pharmacies in each borough and the population of each borough. 
The number of pharmacy in each borough can be obtained using FourSquare location. Foursquare has a database with locations of different venues. Venues with a pharmacy category can be extracted through their API and then grouped by borough. 

The population in each borough can be obtained from the US Census Bureau. The latest data is from 1st July 2019. 
The US Census Bureau is the most ideal source as it is from the government. 

Once these 2 dataset is collected and cleaned, the borough with the least amount of pharmacy per capita is calculated by dividing the number of pharmacies in each borough with its respected population.
