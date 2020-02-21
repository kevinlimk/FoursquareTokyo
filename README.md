FoursquareTokyo
---

Given a [data set](https://www.kaggle.com/chetanism/foursquare-nyc-and-tokyo-checkin-dataset#dataset_TSMC2014_TKY.csv) of 573,703 check-ins of Foursquare users in Tokyo, Japan between April 2012 to February 2013, this project aims to predict a user's check-in venue class from among 247 classes given the current time, the user's GPS location, and the user's previous check-in history.

Using Logistic Regression, a test accuracy of 86% is achieved.

This project is organized into 4 Jupyter Notebooks:

* [01_datawrangling.ipynb](https://github.com/kevinlimk/FoursquareTokyo/blob/master/01_datawrangling.ipynb) - Data cleaning to introduce datetime index and encode venue as a numeric feature. 
* [02_eda.ipynb](https://github.com/kevinlimk/FoursquareTokyo/blob/master/02_eda.ipynb) - Exploratory data analysis to examine the temporal and spatial patterns of check-ins among all users and for specific users.
* [03_featureengineering.ipynb](https://github.com/kevinlimk/FoursquareTokyo/blob/master/03_featureengineering.ipynb) - Exploratory data analysis to examine the temporal and spatial patterns of check-ins among all users and for specific users.
* [04_machinelearning.ipynb](https://github.com/kevinlimk/FoursquareTokyo/blob/master/04_machinelearning.ipynb) - Multiclass classification to predict check-in venue class for the month of February 2013.
  
Installation
---

  * Install Jupyter Notebook using Anaconda.
  * Install the Python requirements with `pip install -r requirements.txt`.
