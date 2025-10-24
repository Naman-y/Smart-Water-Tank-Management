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

### Circuit Description
1. The **ultrasonic sensor (HC-SR04)** measures the water level by calculating the time taken for sound waves to reflect back from the water surface.  
2. Based on the water level, **LEDs** indicate the current water status using 5 LEDs.  
3. The **relay module** acts as a switch to control the **mini SP pump**, isolating the pump's high-power circuit from the STM32 board.  
4. A **diode** is placed across the relay to block back current and protect the microcontroller.  
5. The **Bluetooth module (HC-05)** allows wireless monitoring and control of the water pump.  
6. The circuit is powered using a **9V battery** for portability.
