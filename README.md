# Springboard-Capstone-Project-1

What the project is about?
The project aims at Analyzing Airbnb data and developing a model to correctly predict the price of the rooms based on different attributes of the room.

Tools used:
Jupyter notebook with Anaconda Python 3.
Python packages: Pandas, numpy, matplotlib,scipy, statsmodels, sklearn

Steps Followed in building the model:

1. Obtain the dataset as CSV file from airbnb site.
2. Load the CSV file into the Dataframe
3. Analyze the Data.
   Analyzing the data consists of :
   - Run Pandas describe to check mean median mode for the variable price
   - Use Matplotlib to plot histograms, bar plots, box plots and scatter plots to determine the variation of price with different attributes like neighbourhood, room type, latitude, longitude.
4. Clean the Data:
   - Check for null values. Ignore any attribute with too many NULL values
   - filter out neighbourhoods with very small sample size.
   - convert categorical variables to dummy variables
   - convert binary variables to 0/1
5. Perform a T-test using scipy stats to validate the NULL hypothesis that the average price of the rooms is the same for all room types.
6. Apply OLS to check the attributes on which price is dependent
7. Apply different ML models to see which is the best model to determine the price: 
   - Decision Tree
   - Nearest Neighbours
   - Random Forest
8. Chose the best model based on the R squared value. 
9. Tune hyperparameters to get the best performance out of the model
