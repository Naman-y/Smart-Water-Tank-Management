# Smart-Water-Tank-Management
A project using the STM32F401CCU6 microcontroller designed to manage a water tank's water level efficiently. This system monitors water levels and controls a pump to ensure appropriate water levels while providing real-time feedback via LEDs.

### Features:
- Monitors water levels using an ultrasonic sensor (HC-SR04).
- Controls a mini SP pump via a relay module to maintain desired water levels.
- Displays water levels using LEDs.
- Provides wireless control/monitoring capabilities through a Bluetooth module (HC-05).
- Protects the system from back current using a diode.

### Components Used:
- Microcontroller: STM32F401CCU6
- Bluetooth Module: HC-05
- Ultrasonic Sensor: HC-SR04
- Relay Module: 1 Channel (5V)
- Mini SP Pump
- Power Supply: 9V Battery
- Diode: To prevent back current when the relay is off
- LEDs: Indicate water level
- Resistors: For LED connections and circuit stability
- Breadboard: For prototyping
- Dispaly via mobile app : For water level dislay and controlling the pump
