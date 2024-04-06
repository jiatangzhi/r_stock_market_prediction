# Stock Market Prediction

## Overview
This project focuses on predicting stock returns using time series analysis and machine learning. The goal is to build a regression model that can forecast future stock returns based on historical data.

## Methodology
Two main approaches were taken in this project:

### ARIMA for Univariate Time Series Analysis
- **ARIMA (AutoRegressive Integrated Moving Average)**: Utilized for modeling and forecasting the time series data of stock returns.
- The ARIMA model was used to analyze the temporal structure of the stock returns and to generate short-term forecasts.

### LightGBM for Regression Modeling
- **LightGBM (Light Gradient Boosting Machine)**: Employed for its efficiency and accuracy in handling large datasets and its importance in feature selection.
- Developed a regression model to predict stock returns, which is the last column in our dataset.
- Calculated feature importance to identify the most influential factors affecting stock returns.

## Dataset
The dataset contains historical stock prices and features that potentially influence stock returns, including market capital indicators, volatility measures, and financial ratios.

## Files
- `stock_market_prediction.Rmd`: Contains the R Markdown analysis script used for the ARIMA and LightGBM modeling.

## Results
The project successfully demonstrated the ability to predict stock returns using ARIMA and LightGBM. The feature importance analysis provided insights into the key drivers of stock performance.

## Usage
The analysis can be replicated or extended by running the `stock_market_prediction.Rmd` script in RStudio or a similar R environment.

## Requirements
- R and relevant packages (forecast, lightgbm, dplyr, etc.)
- An understanding of time series analysis and machine learning concepts.

## Contributing
Feel free to fork the project, submit pull requests, or send suggestions to improve the models or analyses.

## License
This project is open source and available under the [MIT License](LICENSE.md).

## Contact
For any additional questions or comments, please contact @jiatangzhi.

## Acknowledgments
- Thanks to all the contributors and the open-source community for the tools and libraries used in this project.
