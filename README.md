# Hi 👋, I'm Tom (Tamilselvan)

# Weather_prediction_Decision_tree
This project aims to predict weather conditions based on various meteorological parameters such as temperature, humidity, wind speed, and pressure. The dataset used in this project is weather_data_sample.csv.

# Project Overview
The project involves the following key steps:

Data Loading and Exploration: The dataset is loaded and explored to understand its structure and check for missing values.

Data Preprocessing: The features (temperature, humidity, wind speed, and pressure) are extracted, and the target variable (weather condition) is encoded using a label encoder.

Model Training: A Decision Tree Classifier is used to train the model with the preprocessed data.

Model Evaluation: The model's predictions are evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R²) score. Additionally, visualizations such as scatter plots and correlation heatmaps are generated to understand the relationships between different variables.

Visualizations: Various plots including scatter plots, pair plots, histograms, and heatmaps are created to visualize the data and the model's performance.

# Detailed Steps
1. Data Loading and Exploration
The dataset is loaded using Pandas, and the structure of the dataset is explored using the .info() method. Missing values in the dataset are identified and handled appropriately.

2. Data Preprocessing
The features Temperature, Humidity, WindSpeed, and Pressure are selected as input variables (X), and the target variable Weather is selected as the output variable (y). The data is then split into training and testing sets using train_test_split from Scikit-learn. The target variable is encoded using a LabelEncoder to convert categorical values to numerical values suitable for model training.

3. Model Training
A Decision Tree Classifier is initialized and trained using the preprocessed training data. The model is fitted on the training data to learn the patterns and relationships between the input features and the target variable.

4. Model Evaluation
The trained model is used to make predictions on the test data. The predictions are evaluated using Mean Squared Error (MSE) and R-squared (R²) score. Any invalid or missing values in the predictions are handled appropriately. The model's performance is assessed using these metrics.

5. Visualizations
Several visualizations are created to analyze the data and the model's performance:

Scatter Plot: A scatter plot is generated to visualize the relationship between the actual and predicted weather conditions.

Correlation Heatmap: A heatmap is created to show the correlation between different features in the dataset.

Pair Plot: A pair plot is generated to visualize the pairwise relationships between different features, with different weather conditions indicated by different colors.

Histograms: Histograms are created to visualize the distribution of different features such as temperature, humidity, wind speed, and pressure.

# Conclusion:
This project demonstrates a basic workflow for predicting weather conditions using a Decision Tree Classifier. The project includes data loading, preprocessing, model training, evaluation, and visualization steps. The visualizations help in understanding the data and the model's performance, providing insights into the relationships between different meteorological parameters.
