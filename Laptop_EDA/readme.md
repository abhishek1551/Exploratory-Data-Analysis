# Laptop EDA

## Overview:

This project aims to predict laptop prices based on various features using machine learning models. It involves data cleaning,
preprocessing, exploratory data analysis (EDA), model training, evaluation, and comparison to identify the best model for predicting laptop prices.
The dataset used contains information about different laptop models, including their brand, specifications, and pricing details.

The project is structured as follows:

1.	Data Cleaning and Preprocessing:
	Removed duplicate entries from the dataset.
	Handled missing values using techniques like imputation and replacing with appropriate values.
	Applied feature engineering to derive new features from existing ones, such as extracting numerical values from text data.

2.	Exploratory Data Analysis (EDA):
	Analyzed distributions and relationships between variables using visualizations like histograms, box plots, and scatter plots.
	Investigated correlations between numerical features to understand their impact on laptop prices.
3.	Visualization:
	Visualized the top 10 most expensive and cheapest laptop brands using bar charts.
	Created a sunburst chart to visualize laptop brands and models based on their prices.

4.	Feature Engineering:
	Encoded categorical features using one-hot encoding to prepare the data for model training.
	Transformed textual data into numerical format where applicable to enhance model compatibility.

5.	Machine Learning Models:
	Trained multiple regression models including Linear Regression, ElasticNet, XGBRegressor, and Ridge Regression.
	Evaluated each model's performance using metrics such as RMSE, MAE, and R-squared.
	Selected XGBRegressor as the best performing model based on the highest R-squared score.

6.	Results and Conclusion:
	Concluded that the XGBRegressor model achieved the highest R-squared score among all models, indicating its effectiveness in predicting laptop prices.
	Provided insights into the key features influencing laptop prices, such as brand, specifications, and operating system.

