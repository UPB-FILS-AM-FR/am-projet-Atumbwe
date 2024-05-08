# Your Project Name
 Automatic trash
| | |
|-|-|
|`Author` | Your full name 
ATUMBWE FAILA GEMIMA 

## Description
The project aims to create an automatic trash can using Arduino, which opens and closes its lid automatically when an object approaches or leaves the vicinity. The system utilizes an ultrasonic sensor to detect the distance of an object and a micro servo motor to control the lid's movement.
## Motivation
This project is an innovative solution for waste management, promoting cleanliness and hygiene in public spaces. The automatic trash can reduces the need for manual intervention, making it more efficient and convenient. Additionally, it can be an engaging educational project for students and enthusiasts, demonstrating the application of sensors and actuators in real-world scenarios.
## Architecture
Hardware Components:

Arduino Nano (microcontroller board)
Micro Servo Motor (R) (actuator)
Ultrasonic Sensor (HR) (sensor)
Breadboard (prototyping platform)
Blue USB (power supply and programming interface)
Jumper wires (for connections)

Software Components:

Arduino IDE (programming environment)
Servo library (for controlling the servo motor)

### Block diagram

The ultrasonic sensor is connected to the Arduino Nano, which reads the sensor data and calculates the distance of an object.
When the distance falls below a certain threshold, the Arduino sends a signal to the micro servo motor to open the lid.
The servo motor rotates to a specific angle, opening the lid.
After a predetermined time, the servo motor rotates back to its original position, closing the lid.
The system continuously monitors the distance and repeats the process as needed.
<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic

![Schematic](schematics/kicad_schematic.png)

### Components

-Arduino Nano : 24.99 ron
-Ultrasonic sensor HC-SR04 : 6.49 RON
-Micro Servo Motor : 13.99 ron
-Breadboard kit with Wires and Power Supply : 22.00 ron
-Blue USB : 4.37 ron

<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| Activ Buzzer | Buzzer | [1.5 RON](https://www.optimusdigital.ro/ro/audio-buzzere/635-buzzer-activ-de-3-v.html?search_query=buzzer&results=61) |
| Push Button | Button | [1 RON](https://www.optimusdigital.ro/ro/butoane-i-comutatoare/1119-buton-6x6x6.html?search_query=buton&results=222) |
| Jumper Wires | Connecting components | [7 RON](https://www.optimusdigital.ro/ro/fire-fire-mufate/884-set-fire-tata-tata-40p-10-cm.html?search_query=set+fire&results=110) |
| Breadboard | Project board | [10 RON](https://www.optimusdigital.ro/ro/prototipare-breadboard-uri/8-breadboard-830-points.html?search_query=breadboard&results=145) |

### Libraries

-Arduino Nano 
-Ultrasonic sensor HC-SR04 
-Micro Servo Motor 
-Breadboard kit with Wires and Power Supply 
-Blue USB 

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May


## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)