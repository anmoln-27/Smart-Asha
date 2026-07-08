# Smart-ASHA System Architecture

Sensors:
- MLX90640 Thermal Camera
- MAX30102 Pulse Oximeter
- MPU6050 IMU
- GSR Sensor
- MQ135 Gas Sensor

↓ Data Acquisition

ESP32-S3 Edge Controller

↓ Processing

TensorFlow Lite Models

↓ Decision Layer

Risk Classification:
- Normal
- Warning
- Critical

↓ Output

- OLED Display
- LED Indicators
- ASHA Worker Recommendations
