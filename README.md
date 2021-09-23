# california-housing-price-prediction

### Problem Statement (Beginner level)
Your first task is to use California census data to build a model of housing prices in the state. This data includes metrics such as the population, median income, and median housing price for each block group in California. Block groups are the smallest geographical unit for which the US Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people). We will call them “districts” for short. Your model should learn from this data and be able to predict the median housing price in any district, given all the other metrics.

![image](https://raw.githubusercontent.com/DeepModiDev/california-housing-price-prediction/main/figures/i1.jpg)

# Frame the solution
This is a supervised machine learning problem. Because we have the labelled data for the training. We need to find median value of the house so it is a regression problem. Also we are not getting the data from the any kind of live stream so it's a batch learning problem.
