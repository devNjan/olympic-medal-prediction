Predicting Olympic Medals

In this project, I used machine learning to predict how many medals a country will win in the Olympics. I used historical data to see if we could figure out what factors—like how many athletes a country sends or how many medals they won before—affect the number of medals they win in future Olympic Games.
Objective

The main goal of this project is to predict how many medals a country will win in the Olympics based on data from previous Games. Specifically, I used features like:

    The number of athletes a country sends to the Olympics
    The number of medals the country won in the past
    Other factors like the country’s age and events

Steps I Followed

Here’s a breakdown of the steps I took to complete the project:

    Forming a Hypothesis: I started by thinking about the problem. I wondered: Can the number of athletes and past medal wins help predict future success?
    Finding and Exploring the Data: I worked with the Olympic dataset to gather information and understand what was available to use.
    Reshaping the Data: Sometimes, the data wasn’t in the format I needed, so I changed it a little to make it easier to use for machine learning.
    Cleaning the Data: I cleaned the data by handling any missing values or problems in the dataset to make sure it was ready for modeling.
    Choosing an Error Metric: I decided to use Mean Absolute Error (MAE) to measure how accurate my predictions were.
    Splitting the Data: I split the data into two parts: one for training the model and one for testing how well the model worked.
    Training a Model: I used Linear Regression to create the model. This is a simple machine learning method that helps us predict a value based on other variables.

Project Files

Here are the two main files in the project:

    machine_learning.ipynb: This is where I built the model, did the data cleaning, and made predictions. It’s the main file for the project.
    data_prep.ipynb: This file is used to get the data ready. It takes the original athlete-level data and transforms it into team-level data, which I used for the model.

Data Sources

The data for this project comes from the Olympics dataset available on Kaggle. There are two main files I worked with:

    teams.csv: This file contains data about the teams (countries) and their performance in the Olympics.
    athlete_events.csv: This file has information about individual athletes, which I used to generate the team-level data.

You can find the dataset on Kaggle here.
Key Takeaways

    Important Features: The number of athletes and how many medals a country won in previous Olympics were important for predicting the number of medals they would win.
    Model Choice: I used Linear Regression for this project because it's simple to understand and easy to work with.
    Model Accuracy: The model made predictions that were off by about 3.30 medals on average, which means the model is not perfect but still gives a reasonable estimate.
    Error Analysis: Some countries, like the USA, had a large difference between predicted and actual medal counts, which shows that a more advanced model might perform better for extreme cases.

Next Steps for Improvement

There are many ways to make this project better:

    Use Advanced Models: Models like Decision Trees or Random Forests might give better results for predicting medals.
    Cross-Validation: I can use cross-validation to check how well my model works on different parts of the data.
    Add More Features: I could try using other features, like athlete age or events attended, to see if they make the predictions more accurate.
