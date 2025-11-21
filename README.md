✈️ Airline Passenger Forecasting
This project focuses on analyzing, modeling, and forecasting airline passenger demand using Machine Learning and Time-Series Forecasting techniques. It uses a synthetic dataset of over 3200 monthly records, including pricing, weather, holiday frequency, fuel cost, and passenger numbers.
📊 Project Objectives
Analyze passenger trends and seasonal patterns
Understand the impact of ticket price, fuel cost, holidays, and weather
Build predictive models to estimate passenger numbers
Forecast future passenger demand using time-series methods
📁 Dataset Overview
Feature	Description
Date	Monthly time series
Avg_Ticket_Price	Average flight ticket price
Fuel_Price	Aviation fuel cost
Weather_Index	Scaled weather conditions (favorable → higher)
Holidays	Number of holidays in that month
Passengers	Target variable (number of flyers)
Dataset contains 3200+ monthly observations.
🔍 Exploratory Data Analysis (EDA)
Key findings:
Seasonal trends: Higher passenger counts during holidays/festivals
Negative correlation: Higher ticket prices → fewer passengers
Indirect effects: Fuel price affects ticket pricing and demand
Weather influence: Favorable weather → more travel
Consistent upward trend in overall air travel from 2015 to 2023
Graphs include:
Line chart (Passengers over time)
Scatter plots (Price vs Passengers)
Bar charts (Holiday effect)
Correlation heatmap
⚙️ Models Used
1. Linear Regression
Used to predict passengers based on:
Ticket Price
Fuel Price
Weather Index
Holidays
Performance:
R² Score ≈ 0.90
Low RMSE
Strong linear relationship between features and passenger count
2. ARIMA (AutoRegressive Integrated Moving Average)
Used for 12-month future forecasting.
Steps:
Time-series indexing
Stationarity testing (ADF Test)
Differencing
Selecting p, d, q using ACF & PACF
Forecast generation
Result:
Clear upward trend in forecast → strong growth in airline travel.
📈 Model Evaluation
Linear Regression
R² = 0.90+ → explains over 90% of variation
Low RMSE → predictions are very close to real values
ARIMA
Forecast line follows historical pattern
Residuals show no pattern → model is stable
Accurate long-term forecasting
🧪 Technologies Used
Python
Pandas
NumPy
Matplotlib & Seaborn
Scikit-Learn
Statsmodels
Jupyter Notebook
📌 How to Run the Project
Clone the repository:
git clone https://github.com/yourusername/Airline-Passenger-Forecasting
Install required libraries:
pip install -r requirements.txt
Open the notebook:
jupyter notebook Airline_Passenger_Forecasting.ipynb
📂 Project Files
Airline_Passenger_Forecasting.ipynb — Full notebook
dataset.csv — Dataset used
images/ — Graphs & visuals
ppt/ — Project presentation slides
README.md — This file
⭐ Conclusion
This project demonstrates how predictive modeling and time-series analysis can be used to forecast airline passenger demand.
The models provide actionable insights for:
Pricing strategies
Holiday scheduling
Fuel cost planning
Forecasting peak travel seasons
