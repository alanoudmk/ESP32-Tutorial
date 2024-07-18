# Ultrasonic Distance Sensor HC-SR04
The HC-SR04 is an ultrasonic distance sensor that can be used to measure distances between 2 cm and 400 cm with an accuracy of 3 mm. It is a popular sensor for various robotics and automation projects.

This simple project demonstrates how to use an ultrasonic distance sensor to measure the distance between the sensor and surrounding objects using an ESP32 board.

   <img src="https://github.com/user-attachments/assets/f70688bb-d1cc-4d41-96ef-a92d2b510d7f" width="320" height="200">

   <img src="https://github.com/user-attachments/assets/91c0b224-e1ab-402b-98d4-5cd5e6aada54" width="350" height="200">
***

### The HC-SR04 ultrasonic distance sensor works with two main components:
1. Transmitter (Speaker):
    - Responsible for emitting the ultrasonic pulse.
    - It is connected to the ``Trig`` pin on the ESP32 board.
    - When the Trig pin is set to HIGH for 10 microseconds, the transmitter emits a short burst of ultrasonic sound waves at a frequency of 40 kHz.
2. Receiver:
    - Responsible for detecting the reflected ultrasonic pulse.
    - It is connected to the ``Echo`` pin on the ESP32 board.
    - When the ultrasonic pulse emitted by the transmitter hits an object and reflects back, the receiver detects the reflected pulse.
    - The time it takes for the pulse to travel to the object and back is measured using the pulseIn() function.




### The Distance is then calculated using the Formula:
```
  dist_in_cm = duration * speed_of_sound / 2;
```



   <img src="https://github.com/user-attachments/assets/ce20e309-940b-4809-bf46-77d97f09e79d" width="300" height="220">

***


# Simulation on WOKWi
Before getting started with ESP32 in real life. we should try to simulate everything on any online simulator. I chose WOKWI because it contains ESP32 unlike TinkerCAD which lacks of this component.


   <img src="https://github.com/user-attachments/assets/989a7ae3-ef51-48ec-ad09-7a408b2bd615" width="350" height="320">

   

## Description
The 259 project is an ESP32-based application that uses an HC-SR04 ultrasonic sensor to measure distance in centimeters. The sensor works by emitting an ultrasonic pulse and then detecting the time it takes for the pulse to reflect off nearby objects and return to the sensor. This time of flight is then used to calculate the distance.


## Components
- ESP32 development board
- HC-SR04 ultrasonic sensor
- Jumper wires




## How It Works
Connect the ESP32 board to the HC-SR04 ultrasonic sensor using the following pins:

- VCC   ->  esp: CLK
- TRIG  ->  esp: 5
- ECHO  ->  esp: 18
- GND   ->  esp: D0


## Code
```
```

