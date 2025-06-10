# Smart-IOT-Plant-Watering-System

## Project Overview

This project presents an **Automated Plant Watering System** using the **ESP8266 Microcontroller**, designed to monitor and manage soil moisture levels, enhancing plant care through precise irrigation control. The system integrates soil moisture sensors to detect real-time moisture levels, sending data to the ESP8266 board. When the soil moisture drops below a set threshold, we will activate the water pump through blink interface, ensuring plants receive adequate water.

Additionally, the system is IoT-enabled, allowing users to monitor and control the watering process remotely via blynk interface application. This is efficient, low-cost system helps reduce water waste and labor by only watering plants when needed, making it ideal for both residential and commercial applications. The project emphasizes sustainable gardening practices through automated irrigation, leveraging IoT to achieve smarter plant care solutions.
___
## Components Required

- NodeMCU ESP8266
- Mini water pump
-	5V DC Relay module
-	Soil moisture sensor
-	9V Battery
-	Breadboard
-	Jumper wires

## Work Flow
1. **Initialization:**
    - The soil moisture sensor is continuously powered and ready to measure the moisture level in the soil.The NodeMCU connects to the Wi-Fi network, allowing remote access and control via blynk interface

2. **Soil Moisture Measurement:**
    - The sensor measures the soil’s water content through electrical resistance: the more moisture in the soil, the lower the resistance; the drier the soil, the higher the resistance.

3. **Decision to Water the Plant:**
    - The NodeMCU processes the data from the sensor and compares it to a predefined moisture thresholds. If the soil moisture is below 1st threshold (i.e., the soil is dry), the NodeMCU determines that the plant needs water.If the moisture is above the 2nd threshold (soil is wet enough), the system does nothing, and the watering process is skipped.

4. **Activating the Water Pump:**
    - When the soil moisture is below 1st threshold value, the NodeMCU triggers the relay module to activate the water pump.The relay module acts as a switch, allowing the NodeMCU to control the high-power water pump safely.

5. **Watering the Plant:**
    - The water pump, powered by the battery or an external power supply, draws water from a reservoir (e.g., a water tank or container) and delivers it to the plant through tubing or a drip irrigation system.The system continues to pump water until the soil moisture level reaches the optimal threshold, ensuring the plant gets the right amount of water.

6. **Monitoring and Remote Control:**
    - The NodeMCU ESP8266 can communicate with Blynk IOT over Wi-Fi. This allows users to monitor the moisture levels in real time, check the status of the system, and manually override the watering process if needed.

____
## Core Features
1. **Automatic Watering**
    - Uses soil moisture sensors to detect dryness.
    - Automatically activates a water pump to irrigate plants when needed.
2. **Water Level Monitoring**
    - Continuously monitors the water level in the reservoir using a water level sensor.
    - Sends alerts if the water level is too low.
3. **Blynk IoT Integration**
    - Real-time data visualization (soil moisture, water level) via the Blynk app.
    - Remote monitoring and control from anywhere using your smartphone.
    - Notifications/alerts through the Blynk app (e.g., low water level, watering started/stopped).
4. **Live Dashboard on Blynk**
    - Visual widgets (gauges, LEDs, charts) showing real-time sensor data.
    - Manual override to start/stop watering from the app.
____

## Applications
  - **Indoor Plant Care:** Automatically water houseplants while monitoring soil moisture and water reservoir level.
  - **Home Gardens:** Maintain balcony or backyard gardens without daily manual watering.
  - **Small-Scale Farms:** Helps farmers optimize water usage and reduce manual labor.
  - **Greenhouses:** Maintain ideal moisture levels in controlled environments for better yield.
___

## Getting Started
1. Clone the Repository:
2. Upload the Code:
   - Code is available at 





