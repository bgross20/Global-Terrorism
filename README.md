# Global-Terrorism
A data analysis project using open-source data and supervised and unsupervised machine learning to identify patterns in global terrorism from 2000-2017 using Tableau, Excel, and Python.

## Background 
Terrorism which is defined as "the threatened or actual use of illegal force and violence by a non-state actor to attain a political, economic, religious, or social goal through fear, coercion, or intimidation," is a global threat. Terrorism is and always will be an ongoing threat. This is the final assignment for the CareerFoundry bootcamp. 

## Objectives

To build an interactive dashboard that will visually showcase well-curated results of an advanced exploratory analysis conducted in Python.

## Data 

I was able to choose which open-source data I wanted to work as long as it met certain requirements which are listed below. The data is open-source data from Kaggle. It consists of 181,691 rows and 135 columns. The data consists of columns such as country_txt (name of country), nkill (number of individuals killed), and iyear (year of attack). The data can be found at: [https://www.kaggle.com/datasets/START-UMD/gtd]. 

The requirements for choosing data were: 

- Be open-source.
- Come from an authentic/authoritative source.
- Include non-anonymized column names.
- Be recent (ideally, no more than 3 years old. However, this factor is not essential - if
you’ve found a perfect data set for your purposes, it could be older too, but not more
than 10 years old).
- Contain at least 2-3 continuous variables (apart from index variables, ID variables, dates,
years, etc).
- Contain at least 2-3 categorical variables (apart from index variables, ID variables, dates,
years etc).
- Contain at least 1,500 rows.
- Include a geographical object of some kind: for instance, a column relating to a country,
continent, or something similar. If the information from the data set refers to the US, for
example, there should be a column containing the names/abbreviations of the states.
Note: there should be at least a couple of different values in this column. This is
important for the geospatial analysis you’ll be conducting. Of course, you can also use
data sets with latitude and longitude.
- In the course of the Achievement you will source a time series data set too, but this
procedure will be explained explicitly in the corresponding Exercise, so you don’t need to
worry about it now.


## Tools 

Language: Python

Libraries: NumPy, pandas, matplotlib, seaborn, quandl, statsmodels.api, datetime, rcParams, adfuller, LinearRegression, mean_squared_error, r2_score, plot_acf, plot_pacf, sklearn, KMeans, StandardScaler

Tools: Jupyter notebooks, Excel, Tableau 

## Skills Demonstrated 

**Data Wrangling and Cleaning:** dropped columns, renamed columns, addressed mixed or incorrect data types, found and addressed missing values, and removed duplicates

**Exploratory Analysis:** Explored basic descriptive statistics (max, min, quartiles, mean, standard deviation) for each variable. Also used scatterplots, correlation heatmaps, pair plots, and categorical plots to explore the distributions of data.

**Conducted geospatial analysis using a shapefile:** Exploring Relationships, Data prep for Regression Analysis, Regression Analysis Standadizing the data, The elbow technique, k-means clustering, Subsetting of the Data Time series analysis: Decomposition Testing for stationarity ( Dicky-Fuller Test / Autocorelation Test )¶ Stationarizing the Data

**Regression analysis:** Split data into a training and test set in order to conduct linear regression from scklearn.linear_model library. Checked the performance statistics using the MSE and R2 score. 

**Cluster analysis:** Used elbow technique to determine appropriate number of clusters to run k-means algorithm with. Visualized clusters with scatterplots and calculated the descriptive statistics. 

**Time-series analysis:** Decomposed a line chart, conducted a Dickey-Fuller test to check for stationarity, conducted several rounds of differencing to made data stationary, checked autocorrelations. 

**Reporting Results:** Created a story in Tableau to display outcomes. [https://public.tableau.com/app/profile/brittney.gross/viz/TerrorismProject_16988831396080/TerrorismStory?publish=yes]
