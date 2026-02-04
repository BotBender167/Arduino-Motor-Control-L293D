Bi-Directional DC Motor Control via L293D and Arduino
This project demonstrates the interfacing of an Arduino Uno with an L293D H-Bridge Motor Driver to control a DC motor's direction and speed. It serves as a foundational project in embedded systems, showcasing logic gate applications and Pulse Width Modulation (PWM).

🛠 Features
Bi-directional Rotation: Control of clockwise and counter-clockwise movement using digital logic.

Speed Regulation: Utilizing PWM signals to manage voltage levels and motor velocity.

Circuit Protection: The L293D provides internal kickback protection for the microcontroller.

🔌 Hardware Components
Microcontroller: Arduino Uno

Motor Driver: L293D IC

Actuator: 3-6V DC Motor

Power Source: USB or External 9V Battery

Connecting Wires & Breadboard

🗺 Circuit Schematic
The circuit utilizes an H-Bridge configuration. Digital pins on the Arduino are used as signal inputs to the L293D to determine the current flow through the motor.

Note: The current setup (shown in the repository image) uses Digital Pins 9 and 10 for logic control, which are PWM-enabled pins on the Arduino Uno.

💻 How to Run
Clone this repository:

Bash
git clone https://github.com/YOUR_USERNAME/Arduino-Motor-Control-L293D.git
Open motor_control.ino in the Arduino IDE.

Connect your Arduino Uno via USB.

Select the correct Port and Board, then click Upload.
