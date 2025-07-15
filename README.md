**Voice-Controlled Bluetooth Car**

**Overview**

The **Voice-Controlled Bluetooth Car** is an innovative project that combines voice recognition with Bluetooth technology to control a robotic car. Built using an Arduino Uno, HC-05 Bluetooth module, and L293D motor driver, the car responds to voice commands sent via a smartphone app, enabling movements like forward, backward, left, right, and stop. This project was developed by P. Govardhan and P. Pattabi Ram under the supervision of Dr. S. Rooban at K L University for the B.Tech program in Electronics and Communication Engineering.

**Resources**

**Project Report and Demo Video:** Access the detailed project report [Voice_Control_Car.pdf](Drive Link) and demonstration video on Google Drive. 

**Project Details:** docs/project_details.md contains the project description, methodology, and more.

**Source Code:** src/car_control.ino contains the Arduino code for car control.

**Features**

Voice-controlled operation via a smartphone app.

Wireless Bluetooth communication using HC-05 (up to 10 meters).

Bidirectional motor control with L293D driver.

'''Extensible for additional sensors (e.g., ultrasonic, cameras).'''

Educational platform for learning embedded systems and robotics.

**Demo**

View the full demo video on Google Drive. 
Installation

**Clone the Repository:**

git clone https://github.com/your-username/Voice-Controlled-Bluetooth-Car.git
cd Voice-Controlled-Bluetooth-Car


**Set Up Hardware:**

Assemble the car with Arduino Uno, L293D motor driver, HC-05 Bluetooth module, chassis, and battery holder (refer to docs/project_details.md).
Upload src/car_control.ino to the Arduino using Arduino IDE.


**Install Mobile App:**

Pair your smartphone with the HC-05 module and install the voice control app (see project report for details).



**Usage**

Power on the car and connect the smartphone to the HC-05 module.
Use the mobile app to issue voice commands (e.g., “Go forward,” “Stop”).
Monitor via the Arduino Serial Monitor (baud rate: 9600).

**License**

This project is licensed under the MIT License. 
For Education Purpose only.

**Contact**

P. Govardhan: padmasali.govardhan.p@gmail.com

P. Pattabi Ram: rampattabhi09@gmail.com

**GitHub:** https://github.com/PadmasaliGovardhan

