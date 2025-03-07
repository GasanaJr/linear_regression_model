#### Linear Regression Model using Gradient Descent

## Overview
This project focuses on building a simple linear regression model to predict sales based on TV marketing expenses. The project explores three different approaches:
- Using NumPy: Implementing linear regression using the np.polyfit function.
- Using Scikit-Learn: Utilizing the LinearRegression model from Scikit-Learn.
- Gradient Descent Optimization: Constructing and optimizing the sum of squares cost function from scratch.
  
## Dataset
The dataset used for this project is tvmarketing.csv, which contains two fields:
- TV: Marketing expenses on TV advertisements
- Sales: Sales amount generated

## Project Structure
1. Linear Regression with NumPy
   - Used np.polyfit() to compute slope and intercept.
   - Made predictions using the equation: Y = mX + b.
2. Linear Regression with Scikit-Learn
   - Used LinearRegression() from sklearn.linear_model.
   - Split dataset into training and testing sets.
   - Trained the model using .fit() and made predictions with .predict().
3. Linear Regression using Gradient Descent
   - Implemented from scratch by minimizing the sum of squared errors.
   - Used learning rate and iterations to optimize parameters.

At the end, there is a model rank basing on the RSMEs of the three different models
This model is implemented using Python and scikit-learn Library

## Running the Notebook
1. Open Google Colab or Jupyter Notebook.
2. Load the dataset.
3. Execute each cell sequentially.
