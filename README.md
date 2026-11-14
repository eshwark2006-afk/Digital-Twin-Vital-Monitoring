# Digital Twin for Vital Parameter Monitoring

## Project Overview
An IoT-based digital twin prototype designed to monitor vital parameters using ESP32 and sensor technology. The system explores real-time data acquisition, cloud-based visualization, and machine learning-based health status classification.

## Objectives
- Monitor heart rate and SpO₂ using the MAX30102 sensor.
- Acquire vital parameter data using ESP32.
- Transmit sensor readings through MQTT.
- Visualize real-time data using ThingsBoard.
- Explore machine learning-based normal and abnormal classification.

## Hardware Components
- ESP32
- MAX30102 Pulse Oximeter Sensor
- OLED Display
- LED Indicator

## Technologies Used
- Embedded C / ESP-IDF
- Python
- MQTT
- ThingsBoard
- XGBoost
- Wi-Fi and IoT

## System Workflow
1. The MAX30102 sensor collects vital parameter readings.
2. ESP32 processes the sensor data.
3. Data is transmitted to the cloud using MQTT.
4. ThingsBoard displays the collected readings.
5. A machine learning model explores the classification of normal and abnormal readings.

## Project Status
Development and prototype testing in progress.

## Note
This is an academic engineering prototype and is not intended for clinical diagnosis.

## Future Improvements
- Improve sensor measurement reliability.
- Enhance real-time visualization.
- Evaluate machine learning model performance.
- Explore remote health monitoring applications.
