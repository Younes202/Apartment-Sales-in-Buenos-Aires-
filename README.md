# Predicting Apartment Sale Prices in Buenos Aires! 
🚀 Welcome to this project, which involved analyzing a dataset of 21,000 properties to discern the impact of size versus location on real estate prices. I imported and cleansed data from a CSV file, unveiling key insights. Additionally, I explored the dataset through data visualization techniques, analyzed the relationship between home prices and area, and mapped the geographic distribution of properties.

## Objective
🏢📍 Our main goal was to develop a predictive model that accurately forecasts apartment sale prices in Buenos Aires. To achieve this, we followed a structured approach consisting of three main steps:

### Project Overview 

 I. Prepare Data
🔍 **Import:** We imported and meticulously cleaned the dataset, ensuring accuracy and consistency.
📊 **Explore:** Delved into exploratory data analysis (EDA) techniques to understand underlying patterns and trends in apartment sales data using matplotlib and plotly.
➡️ **Split:** The dataset was divided into features (surface covered in m², latitude, longitude, neighborhood) and the target variable, which is the price in USD.

II. Build Model
📈 **Baseline:** Established a baseline model to gauge performance, incorporating features and the target variable.
🔄 **Iterate:** Employed iterative model building techniques, experimenting with different algorithms and features such as OneHotEncoder for handling categorical variables, SimpleImputer for managing missing data, and machine learning algorithms like Linear Regression and Ridge Regression.
📊 **Evaluate:** Evaluated model performance using advanced metrics like mean_absolute_error to ensure robustness and reliability.

III. Communicate Results
In this section, we discuss two practical deployment strategies for our predictive model:
1. **Function Deployment:** We encapsulated our model in a function called `make_prediction`, enabling users to input apartment attributes and receive price predictions.
2. **Interactive Dashboard:** Utilizing Jupyter Widgets, we created an interactive dashboard for dynamic exploration of price predictions by adjusting input parameters.
