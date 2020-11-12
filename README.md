# Academy-Awards-Analysis

Academy awards analysis is a data analysis of all the Oscar award winners from the year 1927 to 2015. It tries to answer the following questions -
* Can we come up with a model that could predict the winner among the nominees? Or determine their success factors? 
* Does budget necessarily play an important role?
* Does diversity or lack of diversity of cast and crew in terms of race, gender, sexual orientation, etc. show a pattern of some sort?
* What movie genre and categories are more likely to win the award?

 
## Data Loading Cleaning and Preparation
  * Loading Datasets
  * Handling data types like float, int, strings
  * Cleaning data to handle NA entries.
  * Merging data from various sources to create bigger data frames for analysis

## Machine Learning Model
The project uses Random Forest to predict winner among a given set of nominees. It attains an accuracy of 88% for test and 92% for train set. The code also shows a consufion matrix which depicts the overall performance of the model.

## Visualizations
The code displays a number of plots which includes 
* Impact of budget, income, duration of the movie on award winners
* Award winners correlation race, religion and sexual orientation
* Popular genres
