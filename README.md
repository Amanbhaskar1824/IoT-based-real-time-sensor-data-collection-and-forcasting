# IoT-based-real-time-sensor-data-collection-and-forcasting
# IoT-Based Real-Time Data Collection

This project demonstrates real-time data collection using IoT devices and cloud-based storage for visualization and further analysis. The system integrates hardware (like NodeMCU ESP8266) and software (Firebase and Python with LSTM model) to build a pipeline from sensor data acquisition to machine learning-based prediction.

##  Features

- Real-time data collection using NodeMCU ESP8266.
- Data uploaded to Firebase Realtime Database.
- Historical sensor dataset support.
- LSTM model implemented in Google Colab for time-series forecasting.

##  Project Structure

```
iot_based_real_time_data_collection.py
```

- Python script that implements:
  - Data fetching from Firebase.
  - Preprocessing and normalization.
  - LSTM model training and prediction.
  - Visualization of prediction results.

##  Tools & Technologies

- **Hardware**: NodeMCU ESP8266
- **Cloud**: Firebase Realtime Database
- **Programming**: Python 3 (Google Colab)
- **Libraries**: TensorFlow/Keras, Pandas, NumPy, Matplotlib, Sklearn

##  How It Works

1. **Sensor Setup**: NodeMCU collects data from sensors (e.g., temperature, humidity).
2. **Data Upload**: Data is pushed to Firebase in real time.
3. **Python Script**: Fetches the data from Firebase or loads a local dataset.
4. **LSTM Model**: Predicts future sensor values based on time-series trends.
5. **Output**: Plots are generated showing actual vs. predicted values.

##  Requirements

Install required Python libraries if running locally:

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn
```

##  Usage

Run the notebook or Python script in Google Colab for best results. You can modify the Firebase URL and dataset path as needed.
