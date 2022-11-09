# DC Motor Ctrl

## Description

In this lab, we will use L293D to drive a DC motor and make it rotate clockwise and counterclockwise. 
Since the DC Motor needs a larger current, for safety purpose, here we use the Power Supply Module to supply motors.

## HardWare Connection

Plug the power supply module in breadboard, and insert the jumper cap to pin of 5V, then it will output voltage of 5V. 
Connect pin 1 of L293D to B27, and set it as high level. 
Connect pin2 to B18, and pin7 to B27, then set one pin high, while the other low. Thus you can change the motor’s rotation direction.

![hw_connection](https://user-images.githubusercontent.com/52802567/200905957-bcbb005e-4c10-410b-9730-3e4acbcb7fa1.jpg)

## Source Code

Please refer to lab7_motor.py

## How to run?

    python3 lab7_motor.py


## Youtube Link

https://youtube.com/shorts/gX7LUTnj0jE
