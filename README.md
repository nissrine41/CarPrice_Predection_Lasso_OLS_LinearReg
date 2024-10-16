# Car Price Prediction using: Lasso regression ,OLS(Ordinary Least Squares)

## Overview
This project aims to predict the selling price of cars based on various features such as present price, year, kilometers driven, fuel type, seller type, transmission, and owner. The model is built using machine learning techniques, specifically focusing on Lasso regression, Linear Regression, and Ordinary Least Squares (OLS) regression.

## Features
- **Input Variables**: 
  - Present Price
  - Year
  - Kilometers Driven
  - Fuel Type (e.g., Petrol, Diesel, CNG)
  - Seller Type (e.g., Dealer, Individual)
  - Transmission (e.g., Manual, Automatic)
  - Owner (number of previous owners)

- **Output**: 
  - Predicted Selling Price of the car

## Model Selection
- **Lasso Regression**: This model performs well in terms of prediction accuracy, particularly for high-dimensional data. It helps prevent overfitting by applying L1 regularization.
- **Linear Regression**: A basic regression technique used for comparison.
- **Ordinary Least Squares (OLS)**: Another standard method for regression analysis.

## Implementation Steps
1. **Data Loading**: The dataset is loaded using Pandas.
2. **Preprocessing**:
   - Label encoding is applied to categorical features.
   - The Car_Name column is dropped as it's not useful for prediction.
3. **Data Splitting**: The dataset is split into training and testing sets.
4. **Model Training**: 
   - The Lasso regression model is trained on the training dataset.
5. **Prediction Function**: A function is defined to predict the selling price based on user input.
6. **Gradio Interface**: A user-friendly interface is created to allow users to input features and receive predictions.

## Usage
Run the Gradio interface to input the features of a car, and it will output the predicted selling price.

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- Gradio
- Matplotlib
- Seaborn

## Conclusion
The Lasso regression model has been chosen for the final prediction due to its superior performance compared to other models. This project provides a simple yet effective way for users to estimate car prices based on relevant features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
