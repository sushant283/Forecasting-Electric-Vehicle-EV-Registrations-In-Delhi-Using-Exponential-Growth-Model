# Forecasting-Electric-Vehicle-EV-Registrations-In-Delhi-Using-Exponential-Growth-Model
he objective of this analysis is to forecast future electric vehicle (EV) registrations using an exponential growth model. The data provided includes annual EV registrations from 2005 to 2024, and the goal is to predict registrations for the years 2025 to 2030 while assessing the accuracy of the model

Methodology
Model Selection:
An exponential growth function was selected to fit the data: 
y=a*e^x        
a is the initial value
b is the growth rate
x is the time in year
Data Preparation:
Data from 2005 to 2024 was used to fit the model.
The year values were normalized by subtracting the minimum year (2005) to simplify calculations.
Curve Fitting:vThe curve_fit function from SciPy was used to estimate the parameters a and b that best fit the data.

Forecasting: The fitted model was used to predict EV registrations for the years 2025 to 2030.

Accuracy Assessment:vMetrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) were calculated to evaluate the accuracy of the model.Actual and predicted values were compared to visualize model performance.

Results

Accuracy Metrics:
Mean Absolute Error (MAE):  4833.717083919999
Mean Squared Error (MSE): 48401565.68720798
R-squared (R²): 0.9259474930620037
The MAE and MSE are low relative to the data's scale, indicating good accuracy.The R² value (0.9259) suggests model explains the majority of the variance, confirming it is well-suited for forecasting EV registrations.


Conclusion
The exponential growth model provides a reliable framework for forecasting EV registrations. The model shows good accuracy as indicated by the evaluation metrics, and the forecast aligns with the observed growth trend in the data. However, it is important to note that external factors (e.g., policy changes, market saturation) may influence future trends and should be considered in future analyses.Analysing this, here onward we got one more factor influencing the Future load on the power grid of delhi due to increase in EV Cars in delhi .
