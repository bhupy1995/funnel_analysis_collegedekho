# funnel_analysis_collegedekho
Funnel Analysis Of College (Lead Journey)


SQL-EDA-on-food-prices
Performed the following operations: Removed null values, split the menu category into main category and sub-category for better evaluation, and added a review column(poor, Avg, Very Good, and Excellent) by converting the user ratings.

Overview
This project analyzes a store's database using MySQL. The project is designed to enhance SQL querying skills by solving practical problems.

Question Sets
Count of records

Find out from how many states data are taken -- A2. 27 states and 4 Union terrirories (Andaman nicobar, Chandigargh, Delhi, Puducheri)

How to find out the states which have had the highest prices of Rice under the cereals and tubers category - Retail purchases

Find out the states and markets that have had the highest prices of Rice under the cereals and tubers category- Wholesale purchases

Find out the states and markets that have had the highest prices of Milk under the milk and dairy category- Retail purchases only --A5. Only in 7 states Raw milk is sold

Find out the states and markets that have had the highest prices of Milk (pasteurized) under the milk and dairy category- Retail purchases only

Find out the states and markets that have had the highest prices of Ghee (vanaspati) under oil and fats- Retail purchases only -- A7. Mysore(Karnataka) seems to have the highest Ghee(vanaspati) prices

Finding out the average price of oil and fats as a whole

Find out the average prices for each type of oil under oil and fats -- A9. Groundnut Oil has the highest average price of 148.5 INR and palm oil has the lowest average price of 100 INR

Finding out the average prices of lentils -- A10. Urad has the highest average price of 102.13 INR and chickpeas has the lowest average price of 46.23 INR

Finding out the average price of Onions and tomatoes -- A11. The average price of an Onion is 28 INR and the Average price of a Tomato is 30.3 INR

Find out which commodity has the highest price -- A12 Tea(black) has the highest price throughout all the years (Data for Tea available only from the year 2013)

Find out the commodities that have the highest prices in the recent year 2022 -- Tea comes first, oil comes second, lentils come third

Create a table for zones -- Select city and State from the food prices in the table and insert them into the zones table

JOIN zones table and food_prices_ind AND Create a view

Average price of commodities zone-wise

Find out the price differences between 2022 and 2012

Find out the average prices of each category of food products zone-wise -- South zone has the highest avg price for cereals and tubers(Potatoes,rice,wheat,wheat flour),North zone has the lowest average -- North-East zone has the highest average price for Milk and dairy, South zone has the lowest average -- North-East zone has the highest avg price for Miscellaneous food(Sugar,salt,jaggery,Tea(black)),Union territory has the lowest average -- Union Territory has the highest avg price for oil and fats(Ghee,Groundnut,Mustard,palm,soybean,sunflower),Central has the lowest average -- Union Territory, North East has the highest average price for pulses and nuts(chickpeas and other types of lentils), Central has the lowest average -- North-East zone has the highest average price for vegetables and fruits, South has the lowest average

Find out the average prices of each commodity zone-wise

Drop unnecessary tables

Techniques Used
Basic SQL Queries
JOINs
Subqueries
CTE (Common Table Expressions)
This repository contains the SQL scripts and results for each of the questions listed above. Each solution is designed to demonstrate different aspects of SQL querying and database analysis.
