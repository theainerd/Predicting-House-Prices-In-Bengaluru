# Predicting-House-Prices-In-Bengaluru

# Project Name
Short Project Description

### Install

This project requires **Python3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included

## Project Structure
- data
	- raw
		- train.csv
		- test.csv
-  00_house_prices.ipynb

### Run

In a terminal or command window, navigate to the top-level project directory `` (that contains this README) and run one of the following commands:

```bash
jupyter notebook __.ipynb
```
or
```bash
ipython notebook __.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

## Architecture
### Models used

1. Xgboost

### Data

The dataset used in this project is included as ``. This dataset is provided by MachineHack and contains the following attributes:

**Features**
- `Area_type` : describes the area
- `Availability` : when it can be possessed or when it is ready(categorical and time-series)
- `Location` : where it is located in Bengaluru
- `Price` :  Value of the property in lakhs(INR)
- `Size` : in BHK or Bedroom (1-10 or more)
- `Society` : to which society it belongs
- `Total_sqft` :  size of the property in sq.ft
- `Bath` : No. of bathrooms
- `Balcony` : No. of the balcony

**Target Variable**
- predict the price of houses in Bengaluru.

# Note
If there is any issue running the code, please post it in the issue tracker.
