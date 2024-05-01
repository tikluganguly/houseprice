# House Price Detection - Advance Regression

> This project uses housing data to detetect the house price in australian market. The project uses Lasso and Ridge
> regression to determine the house price and determine what are the parameters that positively and negatively affects the house price

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- We should choose Ridge over Lasso as Lasso is doing overfitting of the data and Ridge is not overfitting
- Here are some of the variables that effects the value of the property positively
  - **Above grade (ground) living area square feet**
  - **OverallQual:** Rates the overall material and finish of the house - any value from 8 (Very Good) increases the price. But for Quality anything from 7 affects the price negatively
  - For **Neighborhood** that gives higher to lower price effects are Northridge, Northridge Heights, Crawford, Stone Brook, Somerset and Veenker. Also,the price of the property is negatively effected if the neighborhood is in Edwards, North Ames, Mitchell, Meadow Village, Gilbert, Old Town,
  - **First Floor** square feet
  - **Second floor** square feet
  - **Roof material** - The price positively affects if the materials are Wood Shingles, Standard (Composite) Shingle, Other materials does not add much value
  - **Size of garage in car capacity**
  - **Size of garage in square feet**
  - **Full bathrooms** above grade
  - **Total rooms** above grade (does not include bathrooms)
  - Good **Basement exposure** increases the price but for any other cases like Minimum, No exposure or if No basement available then the price is negatively effected.
  - Total square feet of **basement area**
  - **Masonry veneer area** in square feet
  - **Remodel date**
  - **Lot size** in square feet
  - **Number of fireplaces**
  - **Basement full bathrooms**
- Some of the paramerers that negatively affects the value of the property are as follows - The **property is near** positive off-site feature--park, greenbelt, etc. - The **height of the basement** less than 100 inches - The **quality of the material on the exterior** is typical or less. - **Kitchen quality** is not excellent (Good, Typical,Fair etc) - The **quality of the material on the exterior** is Typical or less - **Fireplace quality** is fair, poor avarage or no fireplace available - General **shape of property** is irregular

## Technologies Used

- numpy
- pandas
- matplotlib
- seaborn
- sklearn

## Contact

Created by [@tikluganguly] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
