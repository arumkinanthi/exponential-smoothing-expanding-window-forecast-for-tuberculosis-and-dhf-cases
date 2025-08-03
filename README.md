# Analysis of Expanding Window and Exponential Smoothing for Forecasting Tuberculosis and Dengue Fever Cases
![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)

## About Project
This project is done to fulfill the WINIT 2025 - World Innovation Network of Intelligent Transformation 2025, in collaboration with the 1st GILI Conference 2025 - Global Innovation for Learning & Informatics Learning Conference 2025.
### Abstract:
The high number of tuberculosis and dengue hemorrhagic fever (DHF) cases in Mataram City requires health service preparedness, especially in the provision of disposable medical supplies (disposable medical supplies) in the health center laboratory. This study aims to find which is the best forecasting method to read the pattern of dengue hemorrhagic fever and tuberculosis patient visits data using the exponential smoothing forecasting method. The three approaches compared are Single, Double, and Triple Exponential Smoothing, with accuracy evaluation using MAE, RMSE, and MAPE through Time Series Cross Validation techniques. The results showed that the Triple Exponential Smoothing (TES) method provided the best accuracy for dengue data (MAPE = 27.88%), while the Single Exponential Smoothing (SES) method was most optimal for tuberculosis data (MAPE = 12.74%). These findings highlight the importance of selecting forecasting methods that align with the characteristics of the data to support data-driven decision-making in disposable medical supplies inventory planning.
### Research Flow
![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)
### Data Preprocessing
![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)
### TSCV Illustration
![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)
### Results
   Comparison Before and After Log Transform
- ![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)
   Comparison Before and After Outliers Capping
- ![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)
   Comparison Before and After Preprocess
- ![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)
   TES (mul, add) Forecast for NS1/IgG-IgM 
- ![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)
   SES Forecast for BTA/Sputum
- ![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)

## Tech Stacks
- Data Transformation (libraries: pandas, numpy, sklearn.model_selection, sklearn.metrics)
- Forecasting (libraries: statsmodels.tsa)
- Data Visualization (libraries: matplotlib.pyplot, seaborn)
- Tools (Visual Studio Code, Microsoft Excel)

## Setup 
1. Install the libraries used, for example:
   ```
   pip install pandas
   ```
2. Set up the tools used.
