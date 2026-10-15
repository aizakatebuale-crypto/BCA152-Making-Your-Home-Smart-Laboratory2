# ESP32 BLE Mesh Smart Home Laboratory

This repository contains the source code and configuration for a three-node BLE Mesh smart home system developed using the ESP-IDF framework on ESP32 microcontrollers.

## Node Architecture
1. **Light Sensor Node**: Reads ambient light levels from a TSL2561 sensor and broadcasts mesh status messages.
2. **Switch Node**: Controls a physical relay and listens for status updates from both the sensor and gateway.
3. **Gateway Node**: Provides a local web interface via Wi-Fi to manually control the mesh switch state.