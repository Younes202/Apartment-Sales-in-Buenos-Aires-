# Predicting Apartment Prices in Buenos Aires! 🏙️

🚀 Welcome to this project focused on Predicting Apartment Sale Prices in Buenos Aires!

Our endeavor aims to develop predictive models for estimating apartment sale prices

in the bustling city of Buenos Aires. With a commitment to rigorous analysis

and methodical modeling, we seek to provide accurate forecasts that contribute

to informed decision-making within the real estate market of this dynamic city.


## Project Overview 

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
