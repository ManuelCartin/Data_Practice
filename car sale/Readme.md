# 📝 My Learning Path
This repository documents my work with the Kaggle car sales dataset, following a learning path in data science and, in the future, artificial intelligence. The goal is to apply and reinforce theoretical knowledge in a practical project.

# 🚗 About the project and data
Project: Analysis and prediction of second-hand car prices.

Data source: Mock Dataset of Second-Hand Car Sales

Objectives:

Perform exploratory data analysis (EDA) to understand the main characteristics of the dataset.

Preprocess the data to prepare it for modeling.

Build a machine learning model to predict car prices.

Analyze the importance of features in price prediction.

# 📊 1. Exploratory Data Analysis (EDA)
This is where you show what you found in the initial phase. The idea is to use graphs and statistics to understand the data before creating any models.

Initial Analysis: Briefly describe the data. What types of columns are there? (Numeric, categorical, etc.) For example: "The dataset contains X rows and Y columns, with information about the manufacturer, mileage, year, etc.."

Distribution Analysis: How are the key variables distributed? For example, you could include graphs showing:

Car price distribution.

Mileage distribution.

Car count by manufacturer.

Relationship between variables: Are there any interesting correlations? For example, are year of manufacture and price related? What about mileage? You could show a heat map for the correlations.

# 🧼 2. Data Preprocessing
This is the section where you explain how you prepared the data for the model. This is a crucial step.

Missing Values: Were there any missing data? How did you handle them? (For example: "I removed rows with missing values ​​in the 'engine_size' column.")

Variable encoding: How did you convert text variables (such as fuel type or manufacturer) to numbers? (For example: "I used One-Hot Encoding for categorical variables.")

Feature engineering: Did you create new variables from existing ones? (For example: "I created a new column called car_age from the year column.")

# 🧠 3. Machine learning modeling
This is where you'll test your prediction models.

Models used: Mention the models you tested. You can start with simpler models and then try more advanced ones. For example:

Linear regression

Random Forest Regressor

XGBoost

Evaluation metrics: How did you measure the models' performance? The most common ones for regression are Mean Squared Error (MSE) and R-squared (R2).

Results: Compare the results of the models. Which performed best? (For example: "The XGBoost model performed the best, with an R2 of 0.92 and an MSE of 5,500.")

# 📓 Internship Log
Entry 1: Data Cleaning and Visualization
Date: September 16, 2025

Phase: 1. Exploratory Data Analysis (EDA) and 2. Data Preprocessing.

Objectives achieved:

Data cleaning: I identified and handled missing values ​​in key columns such as engine_size and fuel_type. In some cases, I chose to delete rows, and in others, I filled in missing data with the mean or mode to avoid losing valuable information.

Visualization: I created graphs to understand the distribution of price, mileage, and year of manufacture. An interesting finding was the negative correlation between mileage and price, confirming my initial hypothesis that cars with more mileage are cheaper.

Challenges:

I struggled to decide how to handle outliers in price. I decided not to remove them for now, as they might represent luxury cars that are relevant to the model.

Learnings:

Data cleaning is a more important step than it seems. Clean data is the foundation for any successful model.

The visualizations gave me a much deeper understanding than just looking at data tables. A simple scatter plot can reveal an important relationship.

Next steps:

Continue preparing the data for modeling, including coding categorical variables.

Investigate different regression models for predicting price.
