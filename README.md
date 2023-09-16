# AQI-Monitor
The Web-Dashboard for IoT based Air Quality Monitoring System

## Project Overflow
Data Collection: The Arduino UNO, equipped with gas sensors (MQ-135 and MQ-7) and a PM2.5 particle monitoring module, collects data about various air quality parameters.

Data Processing: The collected data is processed to calculate the Air Quality Index (AQI), which provides a standardized measure of air quality.

Data Transmission: The ESP-8266 module ensures that the AQI data is securely transmitted to the ThingSpeak Cloud over the internet.

Data Storage: ThingSpeak Cloud stores the incoming data, making it accessible for analysis and visualization.

Dashboard: Using the Django framework and Bootstrap, a user-friendly dashboard is created. This dashboard allows users to continuously monitor air quality in real-time.

Please checkout the drive folder for all insights :- [Link](https://drive.google.com/drive/folders/1gW_MA22gwtRV6PDYBx1qHF7VTrSrI0Ul?usp=sharing)
