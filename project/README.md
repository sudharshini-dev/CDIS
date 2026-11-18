# project/
- `docs/` abstract, presentation, architecture diagram
- `firmware/` ESP32 code (Arduino/PlatformIO): read sensors, publish JSON over MQTT to AWS IoT Core
- `lambda/` Lambda functions: validate data, compute per-floor usage, leak/anomaly detection, SNS alert
- `dashboard/` web dashboard (API Gateway + Cognito login)
- `hardware/` wiring diagram, bill of materials (ESP32, YF-S201, PZEM-004T)

Status: Review 1 (problem understanding, objectives, abstract) done. Implementation in progress.
