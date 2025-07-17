# Stock-Price-Prediction-using-AI

This repository is a group project focused on predicting stock prices using artificial intelligence. The main analysis is performed in a Jupyter Notebook, where various machine learning models are used to forecast stock prices based on historical data.

## Project Overview

- **Data Source:** Historical stock data is fetched using the Yahoo Finance API (`yfinance`).
- **Data Analysis:** The dataset includes price and volume information for stocks (example: Apple Inc., ticker `AAPL`). Descriptive statistics and visualizations (such as distribution plots and price trends) are used to understand the data.
- **Models Used:** Three main regression models are implemented:
  - Linear Regression
  - Decision Tree
  - Random Forest
- **Evaluation Metrics:** Models are evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score. Direction-based classification metrics (Accuracy, Precision, Recall, F1 Score) are also used for trend prediction.
- **Findings:** For stable stocks like Apple, Linear Regression performs best. For more volatile stocks, Decision Tree or Random Forest may be preferable.

## Highlights

- The code is written in Python and uses libraries such as `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `seaborn`.
- The notebook includes code for data preprocessing, visualization, model training, and comparison of results.
- Visual outputs include distribution plots, price trends, and bar charts comparing model performance.

## Important Notes

- The project demonstrates practical approaches to stock price prediction using regression methods.
- All findings and code are based on data and analysis present in the notebook.
- The repository is designed for educational purposes as part of a college curriculum.

## Additional Information

For more details and updates, visit the [GitHub repository](https://github.com/Akshat0612/Stock-Price-Prediction-using-AI).
