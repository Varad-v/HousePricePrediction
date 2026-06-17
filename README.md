# House Price Prediction

## Project Overview
This project focuses on predicting house prices using Machine Learning techniques. The dataset contains various property features such as area, bedrooms, bathrooms, parking facilities, furnishing status, and other amenities.

## Objectives
- Perform data exploration and preprocessing
- Build and compare regression models
- Evaluate model performance using MAE, RMSE, and R² Score
- Visualize key insights through charts

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

## Models Implemented
1. Linear Regression
2. Random Forest Regressor

## Results

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 970,043 | 1,324,507 | 0.653 |
| Random Forest Regressor | 1,021,546 | 1,400,566 | 0.612 |

## Key Insights
- Area was the most influential factor affecting house prices.
- Bathrooms, air conditioning, parking, and number of stories also contributed significantly.
- Linear Regression outperformed Random Forest Regressor on this dataset.

## Repository Structure

HousePricePrediction/
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── README.md
└── Charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png

## Author
Varad Khatavkar
