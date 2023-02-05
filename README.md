# House-Prices
This project aims to identify the 10 key (features) that have the highest impact on house prices. The real estate dealer provides sales data and the task was to determine which parameters are the most important in selling a house. 

The project uses a data science workflow to analyze the data and make findings. The steps include acquiring the data, preparing the data (cleaning, checking for null values), and analyzing the data (feature selection, model selection). 

The data is loaded into a pandas dataframe, the data types and missing values are checked, and the data is cleaned by dropping certain columns and filling null values. A variance threshold is applied to identify quasi-constant features, and the correlation matrix is used to identify correlated features. The data is then split into training and test sets, and the 10 best features for a Linear Regression model are determined using the Sequential Feature Selector.

