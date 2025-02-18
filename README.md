# San Francisco Crime Data Analysis 📊

![R](https://img.shields.io/badge/R-4.1.0-blue)
![Dataset](https://img.shields.io/badge/Data-SF_CrimeData.csv-green)
![EDA](https://img.shields.io/badge/Analysis-Exploratory%20Data-orange)
![Time Series](https://img.shields.io/badge/Forecasting-ARIMA%20&%20ETS-purple)

## Introduction
This project analyzes crime patterns in San Francisco using **R**. The dataset (`SF_CrimeData.csv`) includes incident details such as location, category, and time of occurrence. The goal is to uncover trends, visualize crime distributions, and predict future crime occurrences using time series forecasting models.

## Dataset Description
The dataset consists of historical crime records with the following key attributes:
- **Incident ID**: Unique identifier for each crime report.
- **Category**: Type of crime committed (e.g., Assault, Robbery, Burglary).
- **Date & Time**: When the crime occurred.
- **Day of the Week**: Helps analyze patterns related to weekdays vs. weekends.
- **District**: Location where the crime took place.
- **Resolution**: Outcome of the crime (e.g., Arrest, Unsolved).
- **Latitude & Longitude**: Geographic coordinates for mapping crime hotspots.

## Technologies Used
- **Programming Language**: R (v4.1.0)
- **Libraries**: `dplyr`, `tidyr`, `ggplot2`, `forecast`, `lubridate`, `leaflet`
- **Techniques**: Exploratory Data Analysis (EDA), Geospatial Mapping, Time Series Forecasting (ARIMA & ETS)

## Data Processing & Analysis
1. **Data Cleaning**:
   - Handling missing values and outliers.
   - Formatting date-time fields for time series analysis.
   - Removing duplicates and inconsistencies.
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing crime distribution across different categories.
   - Identifying peak crime hours and most affected districts.
   - Mapping crime density using geospatial visualization.
3. **Time Series Forecasting**:
   - Applying ARIMA and ETS models to predict future crime rates.
   - Evaluating model performance using RMSE and AIC.
   - Forecasting trends for different crime categories.

## Results & Insights
- **Peak Crime Hours**: Crimes tend to occur more frequently during late evenings and weekends.
- **Most Affected Districts**: Certain areas exhibit consistently higher crime rates.
- **Seasonal Trends**: Some crime categories show periodic fluctuations.
- **Forecasting Accuracy**: ARIMA models provide reliable short-term predictions for crime rates.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sf_crime_analysis.git
Install required R packages:
 ```bash
install.packages(c("dplyr", "tidyr", "ggplot2", "forecast", "lubridate", "leaflet"))
