# UAV Data Acquisition with Ground Telemetry
# Project description:
The project is to create sensor device for quadcopter drones (e.g Mavic Pro DJI drone) that acts just like some of the flight instruments used in crewed aircraft. This device collects data on temperature, pressure, altitude, and drone orientation and then transmits these real-time data to ground-based telemetry. Another device for the project is the ground-based telemetry. Commands and communication can be made wirelessly between drones and ground station via transceiver modules of same RF band. Examples of the commands from ground station to drone sensors are resetting altitude to 0m and calibrating drone orientation before drone takes off.

2 devices will be made in this project: the drone sensors and the telemetry on ground station. Components used in this project include:
+ Microcontroller: Arduino Nano
+ Sensors: IMU (MPU-6050) & Barometric sensor (BMP280)
+ Transmitter & Receiver: 433/868/915MHz Transceivers (nRF905)
+ Telemetry: LCD2004 displaay with I2C

Onboard sensors and ground-based telemetry are made on PCB circuit boards with specific electronic devices’ modules and enclosed in 3D printed housings. Onboard sensors and ground-based telemetry are designed to have successful communication from at least 1000m in distance and 100m in height. The 3D housings of the completed PCB circuit board for onboard sensors must fit to the quadcopter drone and the installation must be ensured not to violate thermodynamic operation of the drone and not to affect the IMU. The project product – drone sensors and telemetry – will be tested and demonstrated in accordance with Drone Rules established by the Australian Civil Aviation Safety Authority. The project is sponsored by Flight One Academy - Archerfield, QLD, Australia.
 
