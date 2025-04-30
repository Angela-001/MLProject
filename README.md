# MLProject
Predicting temperature trends is crucial for many sectors, including agricultural planning and climate adaptation. This project aims to apply machine learning techniques to predict temperature trends in South Carolina for 2024 using climate data from 2000 to 2023. The models were trained on a dataset of approximately 97,000 records from National Oceanic and Atmospheric Administration (NOAA) weather stations across South Carolina. 
Feature engineering involved extracting temporal features and computing rolling averages to capture seasonal patterns. The analysis was conducted in Python using Pandas for data processing, Seaborn for visualization, and Scikit-learn for modeling. The models implemented were Polynomial Regression, Random Forest, and XGBoost Regression. Results indicated that while XGBoost marginally outperformed others, overall predictive power was moderate. This highlighted challenges in predicting temperature with limited variables and highly correlated features. Ultimately, this research enhances the understanding of regional climate dynamics and provides a robust framework for building resilience to future climatic shifts in South Carolina. 


## Technologies Used

- Python 3.10
- Jupyter Notebook
- pandas, numpy
- scikit-learn
  
## Dataset

Data was sourced from NOAA's [National Centers for Environmental Information](https://www.ncei.noaa.gov/access/search/data-search/daily-summaries).

- Dataset includes ~97,000 daily weather records from 11 South Carolina weather stations, Trained using (2000–2023) data, Tested with 2024 data.
- Features selected were:
Average Dew Point Temperature 
Average Sea-Level Pressure 
Average Station Pressure 
Average Wet Bulb Temperature 
Average Wind Speed 
Average Relative Humidity 
Snow Depth 
Average Daily Temperature 
Direction of the Fastest 2-minute Wind (in degrees) 
Heavy Fog 
Hail 
Smoke or Haze 

