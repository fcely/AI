# Car Pricing Analysis

## Introduction

This repository contains an analysis of car pricing based on a Kaggle dataset of car listings. The analysis aims to identify key factors that influence car prices. The analysis includes data preprocessing, exploratory data analysis, feature selection, and model fitting.

## Data

The dataset used in this analysis includes information about various car listings, such as the manufacturer, model, year, mileage, condition, and price. Outliers were removed, and the data was limited to a controlled range of prices and models to enhance the quality of insights.

## Data Preprocessing

The data preprocessing steps involved removing outliers and limiting prices and models to a specific range. This was done to ensure the analysis focuses on relevant data and to prevent overfitting. The dataset was also cleaned to handle missing values and ensure consistency.

## Exploratory Data Analysis

The exploratory data analysis revealed several insights:

- The majority of cars sold had average prices below $25,000 and odometer readings below 120,000 miles.
- Price exhibited a negative correlation with odometer reading and a positive correlation with the year of manufacture.
- Certain car manufacturers and brands significantly influenced car prices. Brands like Ferrari and Aston Martin commanded higher prices, while others like Land Rover were relatively inexpensive.
- Vehicle type (e.g., minivans, trucks) played a role in determining car prices, as did the number of cylinders in the engine.

## Feature Selection

Feature selection was conducted to identify the most influential variables for predicting car prices. Factors like manufacturer, state, mileage, vehicle type, and brand emerged as significant features affecting prices.

## Model Fitting and Insights

A Lasso regression model was utilized to predict car prices. The best-fit model achieved an R-squared value of 76%, indicating a strong fit to the data. The coefficients from the model provided insights into the impact of various features on car prices. For instance:

- The brand "Aston Martin" was associated with a $28,000 price increase, while "Fiat" lowered the average price by $6,000.
- Features like 4WD contributed a $2,000 price increase.
- Certain colors, such as yellow, increased car values, while others like blue and gray lowered them.

## Dependencies

The following libraries were used in this analysis:

- pandas
- seaborn
- matplotlib
- numpy
- scikit-learn

## File Structure

The repository has the following file structure:

- `CarAnalysis/data/`: Directory containing the dataset files.
- `CarAnalysis/analysis`: Jupyter Notebook files for code details and explanations.
- `CarAnalysis/images/`: Directory containing images used in the analysis (if any).
- `README.md`: This file, providing an overview of the analysis.

## How to Use

1. Clone this repository.
2. Open the Jupyter Notebook 
3. Refer to the HTML summary for a concise overview of the analysis.

## Contact

For any questions or inquiries, feel free to contact Fernando Cely
