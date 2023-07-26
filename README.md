# Laptop Price Prediction

<p align="center">
  <img src="https://example.com/laptop-price-predict/assets/laptop_image.png" alt="Laptop Price Prediction">
</p>

## Introduction

The Laptop Price Prediction project aims to develop a machine learning model that can predict the prices of laptops based on various features and specifications. This project utilizes Python and popular machine learning libraries to create a predictive model and provides a user-friendly interface to interact with the model.

## Problem Aimed to Solve

1. Predict Laptop Prices: The primary goal of this project is to predict laptop prices accurately, considering different attributes and configurations.

## <img src="https://example.com/laptop-price-predict/assets/user_icon.png" width="48" height="48"> **User's Manual**

| Files/Folders       | Description                                                                                   |
|---------------------|-----------------------------------------------------------------------------------------------|
| **data**            | Contains the dataset used for training and testing the laptop price prediction model.        |
| **notebooks**       | Jupyter notebooks detailing the data exploration, preprocessing, model training, and evaluation steps. |
| **src**             | Source code for the machine learning model and utility functions.                             |
| **app**             | Web application code that allows users to interact with the laptop price prediction model.     |
| **requirements.txt**| Lists the required Python libraries and their versions.                                       |

## Data Description

The dataset used for this project contains the following columns:

Column Name        | Description
--------------------|-------------------------------------------------
Brand               | The brand of the laptop.
Processor           | The processor type and model.
RAM                 | The amount of RAM (in gigabytes).
Storage             | The storage capacity (in gigabytes).
GPU                 | The graphics card model.
ScreenSize          | The size of the laptop screen (in inches).
OS                  | The operating system installed on the laptop.
Weight              | The weight of the laptop (in kilograms).
Price               | The target variable - the price of the laptop.

## Methodology

The following methodology is used to build the laptop price prediction model:

1. Data Collection: Gathered laptop data from various sources and compiled it into a dataset for analysis.
2. Data Preprocessing: Handled missing values, removed duplicates, and performed feature engineering to prepare the data for modeling.
3. Model Selection: Evaluated multiple regression algorithms and selected the best-performing one based on evaluation metrics.
4. Model Training: Trained the selected regression model on the preprocessed data.
5. Model Evaluation: Evaluated the model's performance using metrics such as mean squared error and R-squared.
6. Web Application Development: Created a user-friendly web application using Flask to allow users to input laptop specifications and receive price predictions.

## Usage

To use the laptop price prediction model, follow these steps:

1. Install the required Python libraries listed in the `requirements.txt` file.
2. Run the Flask web application (`app.py`) to launch the user interface.
3. Enter the laptop specifications in the provided fields and submit the form.
4. The model will predict the laptop price based on the input features and display the result on the webpage.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact [email@example.com](mailto:email@example.com).

## Acknowledgments

Special thanks to [Name Surname](https://github.com/user) for their contributions to this project.
