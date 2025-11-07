📊 YouTube Views Forecasting Project (Excel-Based)
📝 Overview

This project demonstrates time series forecasting on YouTube view count data using Microsoft Excel.
The dataset includes two key columns — Date and Views. The goal is to predict the next 7 days of YouTube views using Excel’s forecasting and trendline capabilities.

🧠 Project Objective

To explore different forecasting models and analyze how various regression and smoothing methods (Linear, Polynomial, Exponential, etc.) can be used to predict YouTube views over time.

⚙️ Tools Used

Microsoft Excel (Mac OS version)

Excel functions: FORECAST, FORECAST.ETS

Trendline analysis: Linear, Polynomial, Logarithmic, Exponential, Power, Moving Average

📈 Steps Performed

Data Preparation

Imported YouTube dataset with Date and Views columns.

Cleaned and formatted date series for continuous time intervals.

Forecasting Using Excel Formulas

Predicted 7 days of future YouTube views using:

=FORECAST(target_date, known_y, known_x)


Compared results across multiple trendline models.

Trendline Analysis

Added and analyzed the following trendlines:

Linear

Polynomial (order increased to 3)

Logarithmic

Exponential

Power

Moving Average

Displayed the R² (coefficient of determination) for model accuracy.

R² value observed: 0.68 (68% accuracy)

Polynomial Forecast Extension

Extended forecast forward by 90 days using a 3rd-order polynomial trendline.

Observed dynamic changes in the trendline’s projection (dotted forecast line).

Visualization

Created a line chart to visualize historical vs forecasted YouTube views.

Customized chart elements (trendlines, axes titles, legends, and data labels).

🔍 Key Insights

The Polynomial (Order 3) trendline provided a more flexible fit compared to the simple linear model.

R² = 0.68 indicates a moderately strong correlation between time and YouTube view trends.

Forecast extensions (90 days) reveal potential long-term growth/decline patterns, though accuracy decreases over longer projections.

🧩 Files Included

YouTube_Forecast_Project.xlsx → Excel file with data, formulas, and charts.

README.md → This documentation.

🚀 Future Improvements

Apply FORECAST.ETS for seasonality-based predictions.

Compare Excel-based models with Python (Prophet, ARIMA) implementations.

Automate dashboard updates with dynamic data inputs.

📅 Forecast Summary
Model	R² Value	Forecast Horizon	Notes
Linear	0.68	7 days	Baseline model
Polynomial (Order 3)	0.68	90 days	Captures non-linear trends
Logarithmic	-	7 days	Limited fit for fluctuating data
📎 Author

Ranit Bhattacharyya
ranitbhattacharyya07@gmail.com
