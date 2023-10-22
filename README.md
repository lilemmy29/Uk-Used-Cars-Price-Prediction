# Uk-Used-Cars-Price-Prediction
## Predicting Used Car Prices in the UK

## Introduction

This repository contains a machine learning project for predicting used car prices in the UK. We used a dataset available on Kaggle, titled "Used Cars Prices in the UK," to train and evaluate our model. The project includes data preprocessing, model training, and a simple linear regression model for predicting car prices based on various features.

## About the Dataset

The "Used Car Prices in UK" dataset is a comprehensive collection of automotive information extracted from the popular automotive marketplace website, autotrader.co.uk. This dataset comprises 3,685 data points, each representing a unique vehicle listing, and includes thirteen distinct features providing valuable insights into the world of automobiles. The dataset offers a rich source of information to explore and analyze used car prices in the UK.

You can find the dataset by following this [link](https://www.kaggle.com/datasets/muhammadawaistayyab/used-cars-prices-in-uk).

### Data Exploration

We started by exploring the dataset to gain insights into its structure. We found some missing values in features like "Previous Owners," "Engine," "Emission Class," and "Service history." To handle these missing values, we filled them with suitable imputed values. Specifically, we filled missing "Doors" and "Seats" values with their respective means.

## Model Training

We used linear regression as our predictive model, focusing on the features that had a notable correlation with the car prices, such as mileage, registration year, the number of doors, and the number of seats. After splitting the dataset into training and testing sets, we trained our model and made price predictions on the test data.

## Results

The R-squared value of around 0.6029 means that our model can explain about 60.29% of the variability in car prices, which is not bad at all. However, there are still some factors or variations that our model did not account for.

## Conclusion

This project showcases the use of a simple linear regression model to predict used car prices in the UK based on relevant features. While the model provides reasonable predictions, there is room for further improvement and exploration in future iterations.

Feel free to explore the code and project files in this repository to gain more insights into our data preprocessing and modeling steps.

If you have any questions or suggestions, please don't hesitate to reach out.

Happy coding!
