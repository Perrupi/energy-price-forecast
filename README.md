
# Energy Prices Prediction for Day-Ahead Trading

## Project Overview
This project aims to predict energy prices for the day-ahead market to optimize the revenue-earning potential of a battery asset. The notebook is organized into three main sections: exploratory data analysis, implementation of a predictive model, and asset optimization approaches.

## Files in the Project
1. **Energy_price_prediction.ipynb**:
   - This Jupyter Notebook provides a detailed walkthrough of the entire process. It includes sections on:
     - Importing libraries and loading datasets.
     - Exploratory Data Analysis (EDA) to understand trends and seasonalities within the data.
     - Implementation of predictive models using XGBoost and Prophet to forecast energy prices.
     - Approaches for optimizing the battery asset based on the predictions.

## How to Use
1. **Data Preparation, Analysis, and Model Testing**:
   - Open the `Energy_price_prediction.ipynb` notebook in Jupyter.
   - Follow the steps in the notebook to explore the datasets, perform data cleaning and preprocessing, and develop predictive models.
   - Adjust the notebook cells as needed to experiment with different model configurations and parameters.

2. **Model Implementation**:
   - The notebook includes the implementation of two predictive models:
     - **XGBoost**: A machine learning model suitable for time series data.
     - **Prophet**: A model designed for forecasting time series data with daily observations that display patterns on different time scales.

3. **Asset Optimization**:
   - After obtaining the predictions, the notebook provides approaches to optimize the battery asset to maximize revenue (but does not provide a functional code).

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Prophet
- Statsmodels

To install the necessary Python packages, you can run:
```bash
pip install -r requirements.txt
```

## Conclusion
This project provides a case study of predicting day-ahead energy prices using ML models. The provided notebook offers a foundation for further experimentation and improvement in forecasting and optimization.
