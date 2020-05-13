# Phone-Gesture-Controlled-RC-Car
Use your phone's IMU to control your car with intuitive hand gestures via bluetooth. 

Please visit https://os.mbed.com/users/achandec/notebook/ece-4180-Al-AlFredo/edit for the code and detailed explanation of the project.

## Introduction
In this project, we use our phone's IMU to control the RC car. The IMU data is sent via bluetooth and received by the mbed LPC1768 though Adafruit's Bluefruit LE module. The mbed the processes this data to control the speed of each motor individually to move as the user desires. 

We have made the controls of the car very intuitive and user friendly. Tilt your phone forward, backward, left, or right and your car will go forward, backward, turn left, or right. 

Furthermore, we have added a collision prevention sensor, two set of battery packs, and a micro LCD (uLCD) screen. You can find a  sonar located in the front of the car. One easily-accessible battery pack located on the side of the car allows easy swap of batteries, and the other is used for back-up. Last but not least, a uLCD is located on top of the car allowing debug and status tracking while mbed is not connected to a computer's serial port.