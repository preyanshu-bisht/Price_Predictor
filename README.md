# Real Estate Price Predictor

This project aims to predict house prices using various machine learning algorithms. The dataset used includes various features that influence house prices, such as the number of bedrooms, location, square footage, and more. By applying machine learning techniques, the model predicts the prices of houses based on these features.

## Project Objectives

- **Accurately predict house prices** using supervised machine learning techniques.
- **Explore different machine learning algorithms** to determine which yields the best results.
- **Analyze the key factors** influencing house prices using exploratory data analysis (EDA).
- **Evaluate model performance** using metrics like RMSE (Root Mean Squared Error) and R² score.

## Features

The key features in the dataset include:

- **Number of bedrooms**: Total number of bedrooms in the house.
- **Location**: Geographical location of the house.
- **Square footage**: Total living area in square feet.
- **Year built**: Year the house was constructed.
- **Lot size**: Total area of the land.
- **Garage**: Whether the house has a garage or not.
- **Other features**: Additional features that may impact house price, such as number of bathrooms, proximity to schools, etc.

## Data Preprocessing

Data preprocessing steps include:

1. **Handling missing values**: Dealing with missing or null values in the dataset.
2. **Feature scaling**: Normalizing or standardizing numerical features to bring them to the same scale.
3. **Encoding categorical variables**: Converting categorical features like location into a numerical format using techniques like one-hot encoding.
4. **Train-test split**: Splitting the dataset into training and testing sets for model evaluation.

## Models Used

The following machine learning models were implemented and compared:

1. **Linear Regression**: A baseline model for predicting house prices.
2. **Decision Tree**: A flowchart-like structure used to make decisions or predictions
3. **Random Forest**: An ensemble learning method for regression that improves performance by combining multiple decision trees.

## Model Evaluation

The performance of the models is evaluated using:

- **Mean Absolute Error (MAE)**: Average of the absolute differences between the predicted and actual values.
- **Root Mean Squared Error (RMSE)**: Measures the square root of the average of squared differences between predicted and actual values.


## Conclusion

This project demonstrates how machine learning techniques can be applied to predict house prices using a dataset of real estate information. By comparing various models, we aim to provide accurate predictions and gain insights into the factors that most influence house prices.

## Future Improvements

- Explore additional features that may improve prediction accuracy.
- Experiment with more advanced models like neural networks.
- Tune hyperparameters of models for further performance improvements.
