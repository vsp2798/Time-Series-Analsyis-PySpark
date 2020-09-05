# Time-Series-Analsyis-PySpark

##Predicting future sales for a company is one of the most important aspects of strategic planning and time series forecasting method overcomes that problem.In our case, time series is used to predict unit sales of a product from different categories like food, hobbies and household.Walmart would like to know the future! To be able fulfill its inventory requirements based on the next week’s sales in order to ensure they have enough stock of items.

##In this dataset, we have used hierarchical sales data from Walmart, the world’s largest company by revenue, to forecast daily sales for the next 28 days. The M5 dataset, generously made available by Walmart, involves the unit sales of various products sold in the USA, organized in the form of grouped time series. More specifically, the dataset involves the unit sales of 3,049 products, classified in 3 product categories (Hobbies, Foods, and Household) and 7 product departments, in which the above-mentioned categories are disaggregated. The products are sold
across ten stores, located in three States (CA, TX, and WI).

##Exploratory Data Analysis had been done and plotted for foods below and code snippets are shown. 

##Data preparation The data consisted of 278 weeks in total and has been split into training, validation and testing sets. First 256 weeks were used to train the model and the last 23 weeks for the testing the model. Validation set of 51 weeks has been implemented for 51 weeks for evaluating the model.

##RMSE and smape has been used to calculate the errors
