# Temperature-Prediction-Using-ML


In this project, I used weather data from Riyadh to build a model for predicting temperatures using machine learning techniques, specifically linear regression. After cleaning and transforming the data, we trained the model using various weather-related variables such as pressure, wind speed, humidity, and cloud cover. The model was then used to predict temperature, with performance evaluated using metrics like R² and RMSE.

## Libraries Used:

Pandas
NumPy
Matplotlib
Seaborn
scikit-learn

## Results:

The model showed good results with high R² values (close to 1), indicating its ability to predict temperatures accurately.
Graphs were displayed to understand performance, including Actual vs Predicted and Distribution of Errors.

## How to Use:

Download the data in a CSV file.
Run the code to analyze the data and train the model.
Review the metrics and plots to understand the performance and prediction accuracy.


# First Code (Exploratory Data Analysis and Visualization):
Data Reading: I loaded a dataset containing weather information for Riyadh, including temperature, pressure, wind speed, humidity, and more.

Data Cleaning: I dropped irrelevant columns such as date, city, and geographic location. Missing values in numerical columns were filled with the mean.

Data Transformation: The 'dt_iso' column was converted to a datetime format, and I extracted the month and season from the date.

Data Visualization:

I plotted a Boxplot to show the distribution of temperatures by season.
A Scatterplot was used to explore the relationship between pressure and temperature.
I displayed a Barplot of average cloud cover by season.
I calculated the number of days with strong winds and extreme heat.
Conclusions: I examined the presence of days with extreme temperatures or strong winds based on the initial data values.

# Second Code (Machine Learning Model Application):
Model Preparation:

I used columns such as pressure, wind speed, humidity, and cloud cover to predict the temperature (target variable).
The data was split into training (80%) and testing (20%) sets.
Model Creation and Training:

A Linear Regression model was applied to the training data.
The model was trained to learn the relationship between the features and temperature.
Prediction and Evaluation:

The model was used to predict temperature values on both the training and test data.
Performance metrics such as R² score and Root Mean Squared Error (RMSE) were calculated for both training and testing datasets.
Error distribution plots were displayed to compare predicted values with actual values.
Results:

Model performance was evaluated using metrics like R² and RMSE to ensure accurate predictions.
Actual vs Predicted and Error Distribution plots were displayed to visualize the results.



