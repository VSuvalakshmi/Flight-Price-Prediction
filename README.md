# Flight-Price-Prediction

Business Problem Statement:

The objective of this project is to predict the prices of flight tickets accurately. This prediction
can benefit both airlines and passengers by providing insights into ticket pricing trends.

Data Science Approach:

1. Supervised Learning - Regression: This problem falls under the supervised learning
category as we have historical flight data with labeled ticket prices that we can use to train a
regression model.

Data Features / Independent Variables:

Our dataset contains various features, including:

- 'Flight_ID': Identifier for each flight.
- 'Airline': The airline associated with the flight (categorical).
- 'Departure_City': The city where the flight departs from.
- 'Arrival_City': The city where the flight arrives.
- 'Distance': The distance of the flight.
- 'Departure_Time': The time of departure (datetime).
- 'Arrival_Time': The time of arrival (datetime).
- 'Duration': The duration of the flight.
- 'Aircraft_Type': The type of aircraft (categorical).
- 'Number_of_Stops': The number of stops during the flight.
- 'Day_of_Week': The day of the week of the flight (categorical).
- 'Month_of_Travel': The month of travel (categorical).
- 'Holiday_Season': Whether it's a holiday season (categorical).
- 'Demand': Demand level for the flight (categorical).
- 'Weather_Conditions': Weather conditions during the flight (categorical).
- 'Passenger_Count': The number of passengers on the flight.
- 'Promotion_Type': The type of promotion (categorical).
- 'Fuel_Price': The price of fuel.
- 'Flight_Price': The target variable we want to predict (flight ticket price).
  
Tech Stack:

1. Python: The primary programming language for data analysis and modeling.
   
2. SQL/MongoDB: For data storage and retrieval.
   
3. Machine Learning (Sklearn): Scikit-Learn for building and evaluating machine learning
models.

4. Mathematics (Numpy): NumPy for mathematical operations.
   
5. Visualization (Plotly): Plotly for creating interactive data visualizations.
  
6. Statistics: For statistical analysis and hypothesis testing.

Machine Learning Model - End to End:

Requirements:

- Ensure you have the necessary packages and their versions installed.
  
Get the Data:

- Retrieve the flight ticket price dataset from the source.
Exploratory Data Analysis (EDA):
- Perform exploratory data analysis using Pandas to understand the dataset:
- Display the first few rows.
- Display the last few rows.
- Get data information.
- Summary statistics.
- Data shape.
- Data types.
- Check for duplicated rows.
- Identify low-variance or constant columns (remove if necessary).
- Handle missing data.
- Check column names.
- Check unique value counts.
- Transpose data for a different perspective.
  
Data Visualization (Using SweetViz):

- Create various visualizations to understand data patterns, relationships, and trends.
- Generate histograms for frequency distribution.
- Calculate correlations among numerical features.
- Analyze categorical vs. categorical associations (e.g., Chi-square test).
- Examine numerical vs. categorical associations (e.g., ANOVA).
  
Data Preprocessing:

- Split the data into training, validation, and test sets to prevent data leakage.
Handling Missing Values and Outliers:
- Replace missing values using methods like mean, median, or mode.
- Handle outliers by removing or treating them.
Data Encoding:
- Encode categorical features using techniques like one-hot encoding or label encoding.
- Scale numerical features using standard scaling.

Machine Learning Model Selection:

- Choose an appropriate machine learning model. In this case, XGBoost is selected for
regression.
Model Training and Evaluation:
- Train the selected model using the training dataset.
- Evaluate the model's performance using metrics such as Root Mean Squared Error (RMSE).
  
Conclusion:

The model's RMSE score is 12.5, which indicates the accuracy of flight ticket price
predictions.

This comprehensive approach covers data collection, exploratory data analysis, data
preprocessing, model selection, and evaluation, ensuring a systematic solution to predicting
flight ticket prices.
