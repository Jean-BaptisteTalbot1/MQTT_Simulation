# Simulate IMUs by Sending MQTT Messages
This is a basic simulation meant to perform manual testing. It only sends fake IMU data over MQTT.

# Installation
1. Install [Mosquitto](https://mosquitto.org/download/)
2. Start Mosquitto service
    2.1 Type in command prompt : brew services start mosquitto (for Mac)
3. Launch MQTTnet-IMU-Sim in Visual Studio

# Configuration
1. Set server IP in IbNavClientOptionsBuilder.cs
2. Set IMUs frequency by assigning taskRateHz in TimerTask method in Program.cs
