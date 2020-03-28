# Timeseries Demo

The goal is to forecast 12 months of future samphoo sales data with SARIMAX as well as Prophet 
and visualize the predictive intervals. We use plotly to make the visualizations easier to explore. 

The dataset describes the monthly number of sales of shampoo over a 3 year period.
The units are a sales count and there are 36 observations. The original dataset is credited 
to Makridakis, Wheelwright, and Hyndman (1998). 

```bash
# Example usage: 
$ pip install -r requirements.txt
$ jupyter notebook 
```

![relative path 1](/Shampoo_sales_SARIMAX.jpeg?raw=true "Shampoo_sales_SARIMAX.jpeg")
![relative path 1](/Sahmpoo_sales_components_Prophet.png?raw=true "Shampoo_sales_SARIMAX.png")


# Using data and extending the basic idea from these sources:
* https://raw.githubusercontent.com/jbrownlee/Datasets/master/shampoo.csv
* https://machinelearningmastery.com/tune-arima-parameters-python/
* https://machinelearningmastery.com/grid-search-arima-hyperparameters-with-python/
* https://plot.ly/python/v3/continuous-error-bars/



