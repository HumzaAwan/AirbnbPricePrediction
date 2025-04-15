# AirbnbPricePrediction

This repository contains a Jupyter Notebook (`AirBNB data (1).ipynb`) for predicting Airbnb listing prices using various regression models. The analysis leverages a dataset of Airbnb listings to explore factors influencing prices, applying techniques like OLS, Polynomial, Ridge, Lasso, and Decision Tree regression.

## Features
- Data preprocessing: Handles categorical encoding and checks for missing values.
- Models evaluated: OLS, Polynomial, Ridge, Lasso, and Decision Tree regression.
- Performance metrics: MAE, MSE, RMSE, and R-Squared for model comparison.
- Visualizations: Plots comparing model performance metrics.

## Dataset
The notebook uses `Airbnb_data.sav` (not included due to size/privacy; see [AirbnbDataRepo](https://github.com/username/AirbnbDataRepo) for the dataset). It includes features like `Price`, `PropertyType`, `RoomType`, `Accommodates`, `Bathrooms`, and more.

## Getting Started
1. Clone the repo: `git clone https://github.com/username/AirbnbPricePrediction.git`
2. Install dependencies: `pip install -r requirements.txt` (includes pandas, sklearn, statsmodels, seaborn, matplotlib).
3. Place `Airbnb_data.sav` in the working directory or update the file path in the notebook.
4. Run the notebook: `jupyter notebook AirBNB\ data\ (1).ipynb`

## Results
Lasso Regression performed best, with the lowest RMSE (0.76) and a reasonable R-Squared (0.38), balancing model complexity and predictive accuracy.

## Contributing
Issues and pull requests are welcome for improving code, adding models, or enhancing visualizations.

## License
MIT License
