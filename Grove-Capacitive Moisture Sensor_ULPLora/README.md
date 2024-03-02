# ULPLoRa with Grove - Capacitive Moisture Sensor Integration

This repository contains code libraries and documentation for integrating the ULPLoRa board with the Grove - Capacitive Moisture Sensor (Corrosion Resistant) for soil moisture monitoring and visualization. The ULPLoRa board, a combination of an Arduino Pro Mini with an RFM95W LoRa module, provides a versatile platform for wireless communication, while the Grove - Capacitive Moisture Sensor offers precise soil moisture measurements.

## Features

- **ULPLoRa Board:** Utilizes the MCCI LoRaWAN LMIC library for LoRaWAN communication.
- **Grove - Capacitive Moisture Sensor:** Corrosion-resistant sensor for soil moisture monitoring.
- **ChirpStack Integration:** Enables seamless connectivity with the ChirpStack server for LoRaWAN network management.
- **InfluxDB and Grafana Integration:** Facilitates data storage in InfluxDB and visualization in Grafana for effective monitoring and analysis.

## Repository Structure

- **/libraries:** Contains code libraries for the ULPLoRa board.
- **/documentation:** Includes detailed documentation on hardware setup, software configuration, and integration with ChirpStack, InfluxDB, and Grafana.
- **/program:** Contains the Arduino program for this project.

## Getting Started

To get started with the ULPLoRa with Grove - Capacitive Moisture Sensor integration, follow these steps:

1. Clone this repository to your local machine.
2. Refer to the documentation in the `/documentation` folder for detailed setup instructions.
3. Install the necessary code libraries for the ULPLoRa board.
4. Follow the provided examples to start monitoring soil moisture levels and transmitting data wirelessly.
5. Integrate with ChirpStack, InfluxDB, and Grafana for advanced monitoring and visualization capabilities.
