# Telemetry Anomaly Detection  

This project explores **machine learning for anomaly detection in time-series data**, inspired by the challenges of **motorsport telemetry** and other high-performance systems. In environments like Formula 1, sensor data streams are fast, data-heavy, and critical — even small anomalies can mean the difference between success and failure.  

## Problem  
Detect anomalies in sensor/time-series data (e.g., engine health, temperature, vibration). The goal is to identify unusual behavior early and reliably in order to prevent failures or performance loss.  

## Approach  
- Collect or simulate telemetry-style time-series data (NASA turbofan engine dataset / IoT sensor data).  
- Preprocess with **Pandas** and visualize with **Matplotlib**.  
- Apply anomaly detection using **LSTM (Long Short-Term Memory)** networks and/or classical models like **Isolation Forest / XGBoost**.  
- Evaluate with standard metrics (precision, recall, F1-score) to show effectiveness.  

## Tools & Technologies  
- Python  
- Pandas, NumPy  
- TensorFlow / Scikit-learn  
- Matplotlib

## Results (in progress)  
- Initial preprocessing and visualizations, model training, and evaluation are ongoing — results will be updated.

## Roadmap  
- [ ] Repo setup + preprocessing (Ongoing)  
- [ ] Basic anomaly detection (Isolation Forest)  
- [ ] LSTM implementation for sequence prediction  
- [ ] Comparative analysis with metrics  

## Repository Structure  
telemetry-anomaly-detection/
│── data/ # Sample datasets (or links if too large)
│── notebooks/ # Jupyter notebooks for experiments
│── images/ # Plots and visualizations
│── src/ # Python scripts (if needed)
│── README.md # Project overview

## Inspiration  
Having worked on a research paper to do with **cybersecurity anomaly detection**, my interest in other applications, such as **motorsport telemetry analysis**, peaked, and I wanted to further explore the commonalities between the two. Both domains demand speed, accuracy, and resilience under pressure.  
