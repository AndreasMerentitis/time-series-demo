# Time series demo

The goal is to forecast 12 months of future samphoo sales data with SARIMAX as well as Prophet 
and NeuralProphet. We visualize the predictive intervals when possible. We use plotly to make 
the visualizations easier to explore. 

The dataset describes the monthly number of sales of shampoo over a 3 year period.
The units are a sales count and there are 36 observations. The original dataset is credited 
to Makridakis, Wheelwright, and Hyndman (1998). 

The example is tested using python 3.8. You can run the demo either directly (natively) or use 
repo2docker to configure and run in docker.

```bash
# Example usage (natively): 
$ pip install -r requirements.txt
$ jupyter notebook 
```

```bash
# Example usage (in docker): 
$ sudo service docker restart
$ jupyter-repo2docker https://github.com/AndreasMerentitis/time-series-demo
```
After this step copy the link that will be produced to your web browser and run the example from there

Shampoo sales with SARIMAX:
![relative path 1](/Shampoo_sales_SARIMAX.jpeg?raw=true "Shampoo_sales_SARIMAX.jpeg")

Shampoo sales components with Prophet:
![relative path 1](/Sahmpoo_sales_components_Prophet.png?raw=true "Sahmpoo_sales_components_Prophet.png")

Shampoo sales components with NeuralProphet:
![relative path 1](/Sahmpoo_sales_components_NeurProphet.png?raw=true "Sahmpoo_sales_components_NeurProphet.png")

# Using data or code and extending the basic idea from these sources:
* https://raw.githubusercontent.com/jbrownlee/Datasets/master/shampoo.csv
* https://machinelearningmastery.com/tune-arima-parameters-python/
* https://machinelearningmastery.com/grid-search-arima-hyperparameters-with-python/
* https://facebook.github.io/prophet/
* https://neuralprophet.com/
* https://github.com/ourownstory/neural_prophet
* https://plot.ly/python/v3/continuous-error-bars/



