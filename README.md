# Olympic Medals Prediction

In this project, I used machine learning to predict how many medals a country will win in future Olympic Games based on historical data. The goal was to explore factors that influence Olympic success, such as the number of athletes and a country’s previous performance.

# Objective

The primary objectives of this project were to:

1. Predict the number of medals a country will win in future Olympic Games.
2. Explore how historical data (such as the number of athletes and past medal counts) correlates with a country's Olympic performance.

# Project Steps

The project was carried out in the following steps:

1. Form a Hypothesis:
I began by formulating a hypothesis about the factors that could predict the number of medals a country might win, such as the number of athletes, previous medal counts, and the age of athletes.

2. Find and Explore the Data:
I explored the available dataset to understand the different features, such as the number of athletes and the countries’ historical medal counts. I analyzed the data to identify which features might be most relevant for making predictions.

3. Reshape the Data:
The dataset initially contained athlete-level data. I reshaped this data into team-level data, where each entry represented a country and its performance across different Olympic years. This transformation was crucial for making predictions at the country level.

4. Clean the Data:
I cleaned the dataset by handling missing values, removing duplicates, and fixing any inconsistencies to ensure the data was in the right format for machine learning. This step was critical to avoid errors and ensure the quality of the data.

5. Pick an Error Metric:
To evaluate the performance of the machine learning model, I chose the Mean Absolute Error (MAE) as the error metric. MAE measures the average of the absolute errors between predicted and actual values, which is useful for regression tasks.

6. Split the Data:
I divided the dataset into a training set and a test set. The training set consisted of data from years before 2012, and the test set contained data from 2012 onward. This allowed me to train the model on one subset of the data and evaluate it on another to test its generalizability.

7. Train a Model:
I used a Linear Regression model to predict the number of medals. Linear regression is a basic and efficient method for predicting continuous values, and it was well-suited for this problem given the available data.

# Project Files

The project includes the following files:

1. linear_regression.ipynb: This is the main notebook where the machine learning model is built, the data is cleaned, and predictions are made.
2. data_prep.ipynb: A separate notebook for preparing the data by transforming the raw athlete-level data into team-level data.

Data Sources

The data used for this project is derived from historical Olympic Games data:

1. teams.csv: Contains data about teams (countries) and their performance in the Olympics.
2. athlete_events.csv: Contains individual athlete-level data, which was used to generate team-level data for this project.

# Key Insights

1. The number of athletes and previous medal counts were the most important factors in predicting the number of medals a country would win. These features showed a strong correlation with a country’s success in the Olympics.
2. Linear Regression was a useful tool for building a baseline model to predict medal counts, but it might not be the best model for more complex cases, especially for countries with highly variable performance over time.
3. On average, the model's predictions were off by around 3.30 medals. While this error isn't huge, it shows that there is room for improvement and the model can be refined further.

# Future Enhancements

1. One plan to improve the model is to experiment with more advanced techniques, like Decision Trees or Random Forests. These models are better suited for handling non-linear relationships, which could improve prediction accuracy.
2. Cross-validation will be applied to get a better understanding of how the model performs on different subsets of the data. This will help assess whether the model is overfitting or underfitting.
3. Adding more features, such as the age of athletes, historical performance trends, and types of events participated in, could increase the model's predictive power and lead to more accurate results.

# Contact Information

If you have any questions or suggestions, feel free to reach out. I am happy to discuss the project further or collaborate.

Debanjan Debnath

Email: debanjandebnath05@gmail.com
