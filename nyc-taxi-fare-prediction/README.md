# Fare Modeling in Practice — A Regression-Based Approach to NYC Taxi Pricing

## 📊 Project Summary

This project builds a multiple linear regression model to predict NYC taxi fares based on pre-ride features.  
It was completed as part of the Google Advanced Data Analytics program.

### 🔍 Key Steps
- Exploratory data analysis
- Feature engineering (e.g., mean_distance, rush_hour)
- Model building with scikit-learn
- Residual analysis and model evaluation (R² ≈ 0.87)

### ✅ Key Findings
- Distance and duration are the strongest predictors
- Rush hour and vendor have minor but visible effects
- Model is interpretable and deployable for real-time fare estimates

## 🖼️ Key Visualizations

All visualizations are saved in the folder `visuals_course_5/` with white background.

| Visual | Description |
|--------|-------------|
| `boxplots_trip_fare_duration.png` | Distribution of trip distance, fare amount, and trip duration |
| `duration_vs_fare_scatter.png` | Relationship between mean duration and fare |
| `correlation_heatmap.png` | Correlation matrix of selected features |
| `predicted_vs_actual.png` | Predicted vs. actual fare amounts |
| `residual_distribution.png` | Histogram of model residuals |
| `residuals_vs_predicted.png` | Residuals plotted against predicted fares |

## 📁 Files in this Repository

- `nyc_fare_prediction_regression.ipynb` – Full notebook analysis
- `Executive_Summary.pdf` – One-page summary of the project and results
- `visuals_course_5/` – Folder containing the visual assets used in this project

## 📂 Dataset Source

This project uses 2017 NYC Yellow Taxi Trip Data, publicly available from the NYC TLC.  
[Download the dataset here (ZIP)](https://www.nyc.gov/assets/tlc/downloads/pdf/trip_record_data_2017.zip)

⚠️ Make sure to extract the CSV file and place `2017_Yellow_Taxi_Trip_Data.csv` in the same folder as the notebook in order to run it.
