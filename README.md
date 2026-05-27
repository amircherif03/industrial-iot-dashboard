# Industrial IoT Dashboard

> Personal Project — INSAT Tunis 2026 | Embedded Systems & IoT

## Overview
End-to-end industrial IoT system: sensor data acquired on Raspberry Pi,
transmitted via MQTT protocol to a Mosquitto broker, then visualized
in real-time on a Node-RED dashboard with configurable alerts.

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Hardware | Raspberry Pi 4, temperature/humidity sensors |
| Languages | C (sensor drivers), Python (MQTT client) |
| Protocol | MQTT (Mosquitto broker) |
| Dashboard | Node-RED |
| OS | Linux (Raspberry Pi OS) |

## Architecture
[Sensors]
↓
[Raspberry Pi — C driver]
↓
[Python MQTT Publisher]
↓
[Mosquitto Broker]
↓
[Node-RED Dashboard] → [Alerts]
## Features
- [ ] Sensor data acquisition in C
- [ ] MQTT publish/subscribe pipeline
- [ ] Real-time Node-RED dashboard
- [ ] Configurable threshold alerts
- [ ] Data logging

## Status
🔄 In progress — Expected completion: August 2026
