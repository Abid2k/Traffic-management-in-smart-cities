# Traffic Analysis and Prediction

## Overview

This project involves the analysis and prediction of traffic data using Python and various data science libraries. The dataset used contains information about traffic at different junctions over time.

## Data Wrangling

We start by importing necessary libraries and loading the dataset. The dataset includes columns like 'DateTime,' 'Junction,' 'Vehicles,' and 'ID.' We perform data wrangling by:

- Converting the 'DateTime' column to a datetime data type.
- Creating additional features such as 'Year,' 'Month,' 'Date_no,' 'Hour,' and 'Day.'

## Exploratory Data Analysis (EDA)

### Line Plots of Vehicle Count by Time Features and Smart Cities

We create line plots to visualize how the count of vehicles varies with different time features (Year, Month, Date_no, Hour, and Day) for different junctions.

### Visualizing Average Traffic Patterns by SmartCity

We analyze the average traffic patterns by grouping the data by junction and time features. Plots are generated for average monthly traffic, traffic by day of the week, traffic by day of the month, and average hourly traffic.

### Count of Traffic in Smart Cities Over the Years

We count and visualize the traffic on junctions over the years to understand how traffic has evolved.

### Correlation Heatmap for Numeric Columns

A correlation heatmap is created to visualize the relationships between numeric columns, including 'Vehicles,' 'Year,' 'Month,' 'Date_no,' and 'Hour.'

### Pairplot of Numeric Columns with Hue by Junction

A pairplot is used to visualize the relationships between numeric columns, with different colors for different junctions.

## Machine Learning - Traffic Prediction

We use a Random Forest Regressor to predict the number of vehicles based on various features. This includes one-hot encoding the 'Day' feature and using a grid search to find the best model. Evaluation metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared are used to assess the model's performance.

### Scatter Plot of Actual vs. Predicted Vehicles

We create a scatter plot to compare the actual and predicted values of the number of vehicles, with color differentiation based on prediction values.

### Scatter Plot of Actual vs. Predicted Vehicles (Sample)

A scatter plot of a sample of 100 data points is generated to provide a more detailed view of the model's performance.

## Conclusion

This project provides insights into traffic patterns, allows for traffic prediction, and demonstrates data visualization and machine learning techniques.

For a more detailed analysis and code, please refer to the Jupyter Notebook provided in this repository.

## Dependencies

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

## Usage

You can clone this repository and run the provided Jupyter Notebook to perform your own analysis and predictions on traffic data.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as needed.

## Acknowledgments

- The dataset used in this project is from [source].
- Thanks to the open-source community for the libraries and tools used.
