# Statistical-Applications-of-Big-Data-Coursework-2-Jonas-Schuppert
This repository shares all relevant code and data used for Coursework 2 of Statistical Applications of Big Data (COS7049-B).
The notebooks were execuded in Google Colab, it is not clear if they can be successfully executed in other IDEs.
The notebooks are meant to be rerun, i.e., if the right datasets (described below) are available the notebooks should be executable for everyone.

The file 'Data_Processing_Big_Data_Coursework_2_Jonas_Schuppert.ipynb' provides all data cleaning, processing etc. information.
The file 'Feature_Engineering_Big_Data_Coursework_2_Jonas_Schuppert.ipynb' provides feautre scaling and selection, as well as training the models, tuning the hyperparameters and model evaluation.

The Electric Vehicle (EV) data was collected from data.gov.uk: https://www.data.gov.uk/dataset/16c7326b-57fe-4803-88f8-9286c387f68a/electric-vehicle-charging-transactions
where the following datasets were downloaded: 'CityEV 2021_Q3 data.csv', 'CityEV 2021_Q4 data.csv', 'CityEV 2022_Q1 data.csv', 'CityEV 2021 Q2 data.csv', 'CityEV Charging Point Data' and 'Charge Transactions'.

The weather data was collected from a free but limited API, which provides historical hourly weather data for London (UK).
The documentation of this API can be found here: https://www.worldweatheronline.com/weather-api/api/docs/historical-weather-api.aspx
The API key from my account is provided in the 'Data Processing' notebook under the 'Weather API' section, in case the notebook needs to be rerun, however, the API key does not allow unlimited get requests.

'EV_Weather.csv' is the final dataset file with which the 'Feature Engineering' notebook can be execuded and all models are trained with.
