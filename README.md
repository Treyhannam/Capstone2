![wine](https://github.com/Treyhannam/Springboard/blob/main/pexels-adonyi-g%C3%A1bor-1407857.jpg?raw=True)
# Wine Classification Model
The goal is to be able to categorize the price of wine given related information about the product. The intention was to build a model that would classify wine prices in a mannar where consumers can determine the relative pricing (expensive vs average) given the information they know about the wine.

## Data Source
The data used for this project is located on kaggle. The data is from the website [Wine Enthusiast](https://www.winemag.com/?s=&drink_type=wine) and was scraped in November, 2017.

-[kaggle wine dataset](https://www.kaggle.com/zynicide/wine-reviews)

## Preparing the Data
All the rows with missing data for price were dropped which was around 6%. There were missing values for some of the categorical variables and their values were replaced with 'unknown'.

For modeling all the data was encoded into numerical values.

## Model
A handful of classification modles were ran to see which ones were worth further exploration. Ultimatly the xgboost model was chosen.
![model df](https://github.com/Treyhannam/Capstone2/blob/main/classmodels.PNG?raw=True)
After the model was hyptertuned the F1 Score improved by 10% with a score of ~0.76. Below is the confusion matrix for the tuned model.
![matrix](https://github.com/Treyhannam/Capstone2/blob/main/classmodels.PNG?raw=True)

## Conclusion
The goal was to be able to categorize the price of wine given related information about the wine. The intention was to build a model that would classify wine prices in a mannar where consumers can determine the relative pricing (expensive vs average) given the information they know about the wine.
