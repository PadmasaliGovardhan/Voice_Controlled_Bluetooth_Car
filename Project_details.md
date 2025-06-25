**Voice-Controlled Bluetooth Car: Project Details**

**Introduction**

The Voice-Controlled Bluetooth Car is a robotic platform that integrates voice recognition and Bluetooth technology for wireless control. Developed as a B.Tech project at K L University, it uses an Arduino Uno, HC-05 Bluetooth module, and L293D motor driver to execute voice commands like “Go forward,” “Turn left,” or “Stop” sent via a smartphone app. This project explores embedded systems, robotics, and human-machine interaction, offering an educational and extensible platform.

**Components**

**Arduino Uno:** Microcontroller for processing commands and controlling motors.

**L293D Motor Driver:** Drives two DC motors bidirectionally, enabling forward, backward, left, and right movements.

**HC-05 Bluetooth Module:** Facilitates wireless communication between the smartphone and Arduino (range: 10 meters, baud rate: 9600).

**Robot Chassis Kit:** Includes DC motors and wheels for mobility.

**Battery Holder:** Powers the system (e.g., 9V battery).

**Methodology**

**Circuit Diagram**

The circuit connects:

HC-05 to Arduino pins 0 (RX) and 1 (TX) for serial communication.

L293D to Arduino PWM pins (e.g., 5, 6, 9, 10) for motor control.

Motors to L293D outputs, powered by a battery via Vcc2 (4.5–36V).

Arduino and HC-05 to a 5V supply via Vcc1.

Refer to the project report on Google Drive for the detailed diagram.

**Assembly**

1. Mount motors and wheels on the chassis.
2. Connect L293D to motors and Arduino.
3. Wire HC-05 to Arduino for Bluetooth communication.
4. Secure the battery holder and connect power.

Software

**Arduino Code:** src/car_control.ino handles Bluetooth commands and motor control.

**Mobile App:** A smartphone app processes voice input and sends commands to HC-05 (details in project report).

**Arduino IDE:** Used to upload code to the Arduino Uno.

**Conclusion**

This project demonstrates the successful integration of voice recognition with a Bluetooth-controlled robotic car, offering an intuitive interface for human-machine interaction. It serves as a foundation for further enhancements, such as obstacle detection or camera integration, and provides valuable experience in robotics and embedded systems.

**References**

For detailed analysis, literature survey, and theoretical component descriptions, see the project report on Google Drive.
