# NYC Taxi Fare Prediction — Multiple Linear Regression

This project builds a multiple linear regression model to estimate NYC taxi fares based only on pre-ride features. The model is based on 2017 trip data provided by the NYC Taxi and Limousine Commission (TLC) and was developed as part of the Google Advanced Data Analytics Certificate (Course 5).

## 📊 Project Objective
Estimate taxi fare amounts using features that are known before the ride starts. This supports real-time pricing, better customer transparency, and regulatory audits.

## 📁 Dataset
- **Source:** [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Year:** 2017
- **Size:** ~1 million rows (filtered sample)

## 📈 Features Used
- `mean_distance` (km)
- `mean_duration` (min)
- `rush_hour` (binary)
- `passenger_count`
- `VendorID_2` (binary encoded)

## 🧠 Model
- **Type:** Multiple Linear Regression
- **R² score:** 0.87
- **Diagnostics:** Residual normality, constant variance, no major multicollinearity

## 📊 Key Visualizations

All visualizations are saved in the folder `visuals course 5/` with white background.

### 📦 Visual 1–3: Distribution Boxplots
![Boxplots](visuals%20course%205/boxplots_trip_fare_duration.png)

### 📈 Visual 4: Duration vs Fare
![Scatterplot](visuals%20course%205/duration_vs_fare_scatter.png)

### 🔥 Visual 5: Correlation Heatmap
![Heatmap](visuals%20course%205/correlation_heatmap.png)

### 📊 Visual 6: Predicted vs Actual
![Prediction Accuracy](visuals%20course%205/predicted_vs_actual.png)

### 📉 Visual 7: Residual Distribution
![Residual Histogram](visuals%20course%205/residual_distribution.png)

### 🧮 Visual 8: Residuals vs Predicted
![Residuals vs Prediction](visuals%20course%205/residuals_vs_predicted.png)

> ℹ️ All plots have been saved with a **white background** to ensure clear readability on GitHub in light/dark mode.

## 🛠 Tools Used
- Python (Pandas, NumPy)
- Seaborn, Matplotlib
- Scikit-learn

## 📄 Executive Summary
A formatted summary of the project is available in `Executive_Summary.pdf`.

## 👤 Author
Jonatan Zemedebrhan  
Google Advanced Data Analytics Certificate — Course 5  
Project: NYC Taxi Fare Prediction
