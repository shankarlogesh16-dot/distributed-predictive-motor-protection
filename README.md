# Distributed Predictive Motor Protection System



A distributed motor monitoring and protection system using ESP32, CAN communication, and multiple sensors.

## 🔧 Planned Features

- Motor current monitoring
- Motor temperature monitoring
- Vibration monitoring
- CAN-based communication
- Motor health analysis
- Automatic motor protection
- IoT-based monitoring using ThingSpeak

## 🏗️ System Architecture

The system consists of two ESP32 nodes:

- **Sensor Node** – collects motor parameters
- **Receiver/Analysis Node** – processes the sensor data and determines motor health

## 📁 Repository Structure

```text
├── sensor_node/
├── receiver_node/
├── circuit/
├── images/
└── documentation/
