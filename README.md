# Wireless Sensor Networks (WSNs) Security: ML & Blockchain Integration  

## Overview  
Wireless Sensor Networks (WSNs) are a critical enabler for IoT but face significant cybersecurity challenges due to their unique constraints. This repository explores lightweight security solutions for WSNs by integrating **Machine Learning (ML)** and **Blockchain (BC)** technologies.  

## OBJECTIVES
1. To develop a secure, decentralized Wireless Sensor Network (WSN) simulation integrating anomaly detection using Machine Learning and secure logging with Blockchain technology.
2. To implement federated anomaly detection using multiple locally trained Isolation Forest models on sensor nodes with majority voting for intrusion prevention.
3. To measure system performance and security impact through real-time transaction latency benchmarking and live visualization within a simulated network environment.

## Design Challenges & Solutions  
- Discusses trade-offs in resource-constrained WSN environments.  
- Recommends efficient BC/ML combinations for scalable security and anamoly detection. 

## Tech Stack 
1. Programming Language: Python 
2. MQTT (Message Queue Telemetry Transport): paho-mqtt — Used in both scripts for MQTT messaging to publish (mqtt_publisher.py) and subscribe (wsn.py) to sensor data.
3. Machine Learning: scikit-learn — Specifically IsolationForest for anomaly detection in wsn.py.
4.Cryptography: cryptography — Used in wsn.py for RSA key generation and digital signing.
5. Blockchain (Custom): A custom lightweight blockchain implementation is embedded in wsn.py for secure data logging.
6. Data Handling & Visualization: 
  a. pandas — For data manipulation and structuring sensor values.
  b. matplotlib — For basic static plotting.
  c. plotly — For dynamic/animated visualization of metrics over time.
7. Concurrency and Events: threading.Event — To handle MQTT message reception control flow in wsn.py.
8. Logging: logging — For simulation activity tracking.
<img width="829" alt="Screenshot 2025-05-20 at 6 27 45 PM" src="https://github.com/user-attachments/assets/2c3d76a6-5b7d-4ee7-81d7-070693bf8d58" />
