# Ames Housing Price Prediction

## Overview
This repository contains a comprehensive analysis and predictive modeling of the Ames Housing dataset, which encompasses residential property sales in Ames, Iowa, between 2006 and 2010. The goal is to understand the factors influencing house prices and to develop a model to predict SalePrice.

## Dataset
The Ames Housing dataset provides a detailed description of the residential properties sold in Ames, Iowa. It includes a variety of features such as the type of dwelling, lot size, quality and condition, year built, and many other aspects of the houses.

## Analysis
The analysis process involves the following steps:
1. **Exploratory Data Analysis (EDA):** Summarize the dataset’s characteristics, handle missing values, and analyze the distribution of SalePrice.
2. **Feature Selection:** Use statistical analysis and correlation matrices to identify significant predictors of SalePrice.
3. **Model Building:** Fit a linear regression model, checking assumptions and refining the model based on diagnostic plots and multicollinearity analysis.
4. **Model Optimization:** Employ all-subsets regression to identify the optimal set of predictive features.

## Results
Our final model demonstrates that Overall Quality, Ground Living Area, and Garage Area are the most significant predictors of SalePrice, explaining approximately 81.8% of its variability.

## Repository Structure
Enter the Module-1 folder
- `AmesHousing.csv`: The dataset file.
- `ALY6015_SankalpBiswal_Week1_Winter_2024.Rmd`: R script containing the analysis, model building, and validation.
- 
## How to Use
1. Clone this repository.
2. Open `ALY6015_SankalpBiswal_Week1_Winter_2024.Rmd` in RStudio or your preferred R environment.
3. Run the script to reproduce the analysis and model building process.

## License
This project is licensed under the terms of the MIT license.

## Acknowledgments
This analysis was inspired by the comprehensive work done on the Ames Housing dataset, which has been a valuable resource for understanding real estate pricing dynamics and predictive modeling in the field of data science.
