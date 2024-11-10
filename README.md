# IoT Smart Bin

## Overview

The IoT Smart Bin is a smart waste management solution designed to automate the process of opening and closing a garbage collector without the need for physical contact. Using IoT technology, the bin can detect a person’s proximity and open automatically when someone approaches to dispose of waste, closing shortly after to maintain cleanliness. Additionally, the bin monitors its fill level using an ultrasonic sensor. When the bin is full, it sends an alert via the Blynk app, notifying maintenance personnel that it requires emptying.

A buzzer serves as an additional alert mechanism, emitting a sound when the bin reaches maximum capacity. This sound notification helps ensure that the bin does not overflow and that waste is promptly collected, improving hygiene and waste management efficiency.



## Features
- Automatic Lid Operation: The bin lid opens automatically when a person approaches and closes after 5 seconds.
- Garbage Level Monitoring: The ultrasonic sensor measures the garbage fill level inside the bin.
- Blynk Integration: Sends notifications to municipal workers when the bin is full and prevents the lid from opening until emptied.
- Hygienic and Hands-Free: No need for manual contact with the bin, making it more hygienic and convenient.
- LCD Display: Provides real-time data on the fill level and distance of the person approaching the bin


## Components
- ESP32 Microcontroller: Handles sensor data and enables Wi-Fi connectivity.
- Ultrasonic Sensors: Measure both the garbage level and proximity of people approaching the bin.
- Servo Motor: Controls the automatic opening and closing of the lid.
- Buzzer: Alerts users when the bin is full.
- LCD Display: Shows the current fill level and the distance from the bin in centimeters.
- Blynk Application: Sends notifications and allows remote monitoring of the bin’s status.


## How It Works
1. The ultrasonic sensor detects when a person is within a set range (less than 20 cm) and opens the bin lid automatically.
2. After 5 seconds, the lid closes automatically if no one is nearby.
3. The bin’s fill level is constantly monitored. If the bin is full, the system sends a notification through the Blynk app.
4. The bin remains closed when full, preventing further waste from being added until it is emptied by authorized personnel.

## Libraries Used
- WiFi.h: For ESP32 Wi-Fi communication.
- BlynkSimpleEsp32.h: For connecting with the Blynk app.
- Servo.h: To control the servo motor.
- Wire.h: For I2C communication with the LCD display.
- LiquidCrystal_I2C.h: To manage the I2C LCD screen.

![IOT-BIN](https://github.com/Rawida-AlShereiqi/IOT-Smart-Bin/blob/refresh-2019/img/IOT-BIN.PNG)

![IOT-BIN](https://github.com/Rawida-AlShereiqi/IOT-Smart-Bin/blob/refresh-2019/img/Blynk.PNG)


### [Click here](https://wokwi.com/projects/413275697202905089)

# SMART BIN

This project is designed to work within Tinkercad, allowing users to explore and experiment with the general concept. 
You can try it out to better understand the functionality and overall idea behind the project. 


### [Click here](https://www.tinkercad.com/things/99JqoPQZ5KY-iot-smart-bin-?sharecode=pqr8HvEi0MeLVdUHV7Rw3ov7YVxDQipKlJSb1PkH68g)


![Smart-Bin](https://github.com/Rawida-AlShereiqi/IOT-Smart-Bin/blob/refresh-2019/img/Smart-Bin.PNG)


## Demo Video

[Watch the project demo video](https://drive.google.com/drive/folders/1scEsSNCpENCn8uHwS4XJMw4WXljS7Zlk?usp=sharing)

