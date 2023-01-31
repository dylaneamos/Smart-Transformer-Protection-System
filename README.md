# Smart-Transformer-Protection-System
A high level overview on creating a Smart Transformer Protection System that can be used in real life situations.
Here's a high-level overview of the steps that can be followed to develop a smart transformer protection system using C++:
1. Collect data from sensors: To meet objective 1, the system must be able to collect data from different sensors that monitor the transformer, such as current and voltage sensors, temperature sensors, and pressure sensors.
2. Analyze data: To meet objectives 2 and 3, the system must have the ability to analyze the collected data and detect potential issues such as an overcurrent, an overload, and high temperature or pressure.
3. Trigger actions: Based on the data analysis, the system should be able to take action to isolate the fault, prevent damage to the transformer, and provide diagnostic information.
4. Communicate with remote control center: To meet objective 4, the system should be able to communicate with a remote control center, allowing utilities and power companies to monitor and control the transformer from a distance. This can be done by sending data to the control center and receiving commands from it.
5. Store data and logs: The system should store data and logs to provide a history of the conditions of the transformer and any actions taken by the system.

This code is a simple monitoring system that continuously collects data from 4 sensors (current, voltage, temperature, and pressure) and analyzes the data to detect any issues. If an issue is detected, the system triggers an action based on the issue type. The actions are specified in the "trigger_action" function. The system runs in a loop and waits for 5 seconds before collecting data again.
