# Methodology

1. Collect sensor data.
2. Preprocess the signals.
3. Run TensorFlow Lite inference on ESP32-S3.
4. Fuse outputs using rule-based logic.
5. Classify patient into:
   - Normal
   - Warning
   - Critical
6. Display recommendations to ASHA worker.
