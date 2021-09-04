# Module 11 Time Series

## Using Google Collab, we import jupyter notebook to understand the process of using a public notebook to increase out knowledge when wanting to do collaborative work with others.Using time series data we are to write code in a way to read customer data to make predictions to how we can increase the company's revenue. 

###### To begin, we needed to upload all the necessaries dependencies for the Google Collab
> ```from IPython.display import clear_output
try:
  !pip install pystan
  !pip install fbprophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')
```
