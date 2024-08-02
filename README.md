# pH-Monitoring-System
This system leverages the accuracy of TDS sensors and the processing power of the STM-32 board to provide real-time data on the chemical properties of water.

The pH Monitoring System detects the concentration of dissolved solids in water using a TDS sensor and calculates the pH levels. The STM-32 microcontroller processes the sensor data, displays the results, and can trigger alerts or actions based on predefined thresholds. This system is ideal for applications where water quality monitoring is critical, such as in aquariums, hydroponics, swimming pools, and water treatment plants.

Key Components: 1.TDS Sensor: Measures the concentration of total dissolved solids in the water. Higher TDS levels can indicate higher concentrations of salts and other dissolved substances. 2.pH Sensor: Measures the hydrogen ion concentration in the water, providing a direct pH reading which indicates the acidity or alkalinity of the water. 3.STM-32 Board: A high-performance microcontroller board that processes the input from the TDS and pH sensors, calculates the necessary values, and manages the system's outputs. 4.Display Module: Often an LCD or OLED screen that displays the pH and TDS readings in real-time. 5.Power Supply: Provides the necessary power for the STM-32 board, sensors, and display module. 6.Alert System (Optional): Could include LEDs, buzzers, or connectivity to send notifications when pH or TDS levels are out of the desired range.

How It Works:
1.Water Sampling: The TDS and pH sensors are submerged in the water sample to begin the monitoring process.
2.Data Acquisition: The sensors continuously measure the total dissolved solids and pH levels of the water, sending this data to the STM-32 microcontroller.
3.Signal Processing: The STM-32 processes the raw data from the sensors, applying any necessary calibrations and algorithms to ensure accurate readings. 4.Data Display: The processed pH and TDS values are displayed on the screen in real-time, allowing for continuous monitoring. 
5.Alerts and Actions: If the pH or TDS levels fall outside of the predefined safe ranges, the STM-32 can trigger alerts or even automated actions, such as adjusting the chemical balance in a water treatment system.

Features and Benefits:
1.Accurate Monitoring: Provides precise and reliable measurements of both pH and TDS levels, essential for maintaining optimal water quality.
2.Real-Time Data: Continuous monitoring and immediate display of water quality parameters ensure timely detection of any issues. 
3.Versatility: Can be used in various applications, from household aquariums to large-scale industrial water treatment plants.
4.User-Friendly Interface: The display module and optional alert system make it easy for users to understand and respond to water quality data.
5.Customizable Settings: The STM-32 can be programmed to adjust thresholds, calibration factors, and response actions based on specific requirements. 6.Data Logging (Optional): The system can be enhanced to log data over time, providing historical records for analysis and reporting.
