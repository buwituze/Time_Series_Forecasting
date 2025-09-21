# Time_Series_Forecasting : Air Quality Forecasting Project

Air Pollution is a serious health issue, and if we can forecast pollution levels in adavance, it can help with planning and public safety. Thus, this project.

This repo is for a Time Series Forecasting project, the goal of the project is to predict PM2.5 levels in Beijing using time series forecasting with LSTM. I trained different models on historical air quality and weather data to predict future PM2.5.

## Data:

- train.csv --> training data
- test.csv --> test data
- sample_submission .csv --> shows the format kaggle expects for submission

## Usage:

### In Google Collab: 

 - Open `air_quality_forecasting_starter_code_Benitha Uwituze Rutagengwa.ipynb`
 - Click **Open in Colab**, this will open the notebook in the Google Collab where you can run the cells in the notebook
 - In the Goggle Collab navbar click **Run all** and view results of each cell.

### In local IDE:

- Clone the (repo)[https://github.com/buwituze/Time_Series_Forecasting/new/main?readme=1.git]
- Download datasets from: https://drive.google.com/drive/folders/1T3yHZreotr3QZ3sGLAo6pjd97uQ__aDV?usp=drive_link
- Install packages in virtual env
  - Create venv : `python3 -m venv venv`
  - Run venv: `source venv/bin/activate` (Linux) or `venv\Scripts\activate`  (Window)
  - Run the first cell in the notebook 
- In the cloned repo, open the jyputer notebook `air_quality_forecasting_starter_code_Benitha Uwituze Rutagengwa.ipynb`
-  Click **Run all** located at the top navbar of the notebook
- View the outputs of each cell

## Results:

- Best model: Reguralized LSTM
- RMSE: 4415.17 (Validation RMSE: 77.78)

### Model Performance

<img width="1207" height="299" alt="Screenshot 2025-09-22 001713" src="https://github.com/user-attachments/assets/59bec62a-d62a-4826-b42f-4b999ac6ed1b" />
