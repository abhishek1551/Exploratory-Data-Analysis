This project involves analyzing a video game sales dataset using various data analysis and machine learning techniques.
The dataset includes information on game names, platforms, release years, genres, publishers, and sales across different regions.

Key Steps
Data Analysis
1.	Data Loading and Exploration:
•	Loaded the dataset and explored the first few rows to understand its structure.
•	Checked the number of rows and columns.
•	Obtained statistical summaries of numerical features.
2.	Data Cleaning:
•	Identified and handled missing values in the Year and Publisher columns.
•	Converted categorical features to numerical values using Label Encoding.
3.	Exploratory Data Analysis (EDA):
•	Visualized the top 10 publishers, genres, and platforms using Plotly.
•	Created year-wise sales plots for different regions.
•	Generated scatter plots and sunburst charts to show relationships between features.
Machine Learning
1.	Feature Selection:
•	Selected relevant features for predicting global sales.
2.	Model Training and Evaluation:
•	Applied Linear Regression, Random Forest Regressor, and AdaBoost Regressor models.
•	Evaluated model performance using R² scores.
3.	Hyperparameter Tuning:
•	Performed GridSearchCV to find the best hyperparameters for Random Forest and AdaBoost models.
Visualization
•	Created various visualizations using Plotly and Seaborn, including bar charts, scatter plots, line plots, and heatmaps.
•	Generated word clouds for categorical features.
Results
•	Linear Regression: Achieved an R² score of ~0.999.
•	Random Forest Regressor: Improved R² score to ~0.819 after tuning.
•	AdaBoost Regressor: Improved R² score to ~0.38 after tuning.
Tools and Libraries
•	Python: NumPy, Pandas, Matplotlib, Seaborn, Plotly
•	Machine Learning: Scikit-learn
•	Other: WordCloud, PIL
