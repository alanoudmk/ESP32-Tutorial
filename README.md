# ESP32
The ESP32 is a low-cost, low-power system-on-a-chip (SoC) microcontroller developed by Espressif Systems. It is widely used in a variety of IoT (Internet of Things) and embedded applications due to its powerful features and capabilities.

Used in a wide range of IoT applications, such as smart home devices, wearables, industrial automation, smart city projects.


![image](https://github.com/user-attachments/assets/242542a9-17af-4c3f-b56b-87d5cfb40d37)


## Why an ESP32?

The main feature of the ESP32 microcontroller is its robust wireless connectivity capabilities. This is particularly noteworthy given the increasing demand for IoT (Internet of Things) and embedded devices that require seamless wireless communication and integration.

Here are the key wireless features that make the ESP32 a standout in the market:
  - Wi-Fi Connectivity
  - Bluetooth and Bluetooth Low Energy (BLE)
  - Dual-Mode Wireless Connectivity:
  - Low-Power Operation:
  - Integrated Antenna:

    <img src="https://github.com/user-attachments/assets/d9dd7929-81c6-4b6d-99f5-b7a8f5c9f1c6" width="330" height="200">


## How to Program?

The ESP32 can be programmed using the C++ programming language and the Arduino IDE (Integrated Development Environment). 

***


# Installing & Setting Up the Programming Environment


## Uploading ESP32 to Arduino IDE 1.8.19

1. Install Arduino IDE
   - Download [Link](https://www.arduino.cc/en/software)

2. Open Arduino IDE and GO to:
   > File -> Perfrences

3. Add ESP32 Board Support:
   
   - Copy The Link below and Paste it into the _Additional Boards Manger URLa_:
     
  ```
  https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
  ```
   <img src="https://github.com/user-attachments/assets/a0c5519c-3e37-46e5-9515-5f0881deb279" width="250" height="200">

  - Click "OK" to close the Preferences window.


***

## Select ESP32 Board:

1. Go to:
  > Tools -> Board -> Boards Manager

<img src="https://github.com/user-attachments/assets/4f2254b4-6cc4-4e6d-acaa-a86c64a51837" width="280" height="150">


2. Type _ESP32_ Then Click Install:
 
<img src="https://github.com/user-attachments/assets/ca3031bb-41a3-4403-b943-a1a8c59ada4e" width="280" height="150">

3. Now, Go Back To:
  > Tools -> Board
  
  - Select your specific ESP32 board from the list (e.g., "ESP32 Dev Module"). 

***

## Select the Port:

1. Connect your ESP32 to your Computer using a USB cable.

2. Go to:
   > Tools -> Port

3. Select the port to which your ESP32 is connected (e.g., COM3 on Windows, /dev/ttyUSB0 or /dev/ttyS0 on Linux).


***

## Testing the ESP32 (Blinking Internal LED)

This simple "Blink" example demonstrates that your ESP32 is properly set up and communicating with the Arduino IDE. 


1. Connect your ESP32 to your Computer using a USB cable.

2.  Go to:
  > File -> Examples -> Basics -> Blink

3. Run the Program

4. Upload the code and wait
  - You should see the built-in LED on your ESP32 blinking.


***
# Resources

- [ESP32 Tutorial](https://www.youtube.com/watch?v=_0eHPrRC8oc&t=49s)
