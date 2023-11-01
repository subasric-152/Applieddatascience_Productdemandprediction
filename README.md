# Product Demand Prediction using ARIMA Model
## Overview
The primary focus of this research is on the problems that companies face when managing their inventory and production scheduling. Accurate demand forecasting is critical to optimising resources, reducing costs, and ensuring customer satisfaction. The ARIMA (AutoRegressive Integrated Moving Average) model is a widely used time series forecasting technique that is well-known for its capacity to spot patterns and trends in historical data. By putting ARIMA into practise, we intend to provide businesses with a dependable method of predicting product demand, enabling them to make ahead of schedule plans, allocate resources efficiently, and maintain a competitive edge in their specific industries. In addition to providing a practical solution, this project serves as a teaching tool for understanding time series forecasting principles and using ARIMA in practical settings.

## Table of Contents
1.Installation

2.Usage

3.Dataset Descrption

4.Model Analysis


## Installation
To run this project successfully, please follow these installation steps:

* Python Version: Ensure you have Python 3.x installed on your system. You can download and install Python from the official Python website.

* Clone the Repository: Clone this GitHub repository to your local machine using the gitclone command.

* Install packages: pandas, matplotlib, numpy, ploty, statsmodel


## Usage
To use this project for product demand prediction, follow these steps:

* Clone this repository to your local machine.

* Ensure you have the required data (see the Data section for details).

* Run the ARIMA model on the provided data.

* The model will generate predictions and save the results in the Results directory.

## Dataset Description
You need to have the historical product demand data. The data should be in a structured format, preferably a CSV file.

DATASET : https://www.kaggle.com/datasets/saranya55/trainnew

1.Date:  
Description: This column represents the date on which the sales data was recorded.  
Data Type: Date or Timestamp

2.Store:  
Description: This column indicates the unique identifier or code for the store where the product was sold.    
Data Type: Numerical

3.Item:  
Description: This column specifies the unique identifier or code for the product/item that was sold.  
Data Type: Numerical 

4.Sales:   
Description: This column represents the quantity of the product/item that was sold on a specific date at a particular store. 
Data Type: Numerical (Integer or Float)

You can specify the data file in the config.yaml configuration file.

## Model
The ARIMA (AutoRegressive Integrated Moving Average) model is used for product demand prediction. The model parameters can be configured in the config.yaml file. You can fine-tune the model by adjusting the order of autoregressive (p), integrated (d), and moving average (q) components.

One of the key prerequisites for applying the ARIMA model is that the time series data should be stationary. Stationarity implies that the statistical properties of the time series, such as mean, variance, and autocorrelation, remain constant over time. 

we also used the adfuller hypothesis test by considering null and alternative hypothesis.






