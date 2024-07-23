# PROJECT SMART LOCK SYSTEM


## AIM

To create a smart lock  system using LCD and keypad interfaced with arduino.


## COMPONENTS

1) Arduino UNO R3
2) LCD 16*2 Module
3) Keypad 4*4
4) Jumper Wire
5) USB Cable


## CONNECTION

### Matrix 4*4 keypad Module

 ![4x4-keypad-pinout](https://github.com/user-attachments/assets/dc83c5ce-cfc7-42b1-bf37-a125abce1cc1)

<br> R1 ---->  10&ensp;&ensp;C1 ---->  6
<br> R2 ---->  11&ensp;&ensp;C2 ---->  7
<br> R3 ---->  12&ensp;&ensp;C3 ---->  8
<br> R3 ---->  13&ensp;&ensp;C4 ---->  9	

### LCD 16*2  Module
 
![LCD 16,2](https://github.com/user-attachments/assets/ea945f49-f252-4be1-a027-1b8c65f92841)

<br> RS ---->  A0&ensp;&ensp;Power supply  ---->  5V
<br> EN ---->  A1&ensp;&ensp;GND   ---->  GND
<br> D4 ---->  A2&ensp;&ensp;D6 ---->  A4
<br> D5 ---->  A3&ensp;&ensp;D7 ---->  A5


## PROCEDURE

<br> Step 1 : Interface Arduino board to Arduino IDE using port.
<br> Step 2 : Interface Arduino board with keypad and print key values on serial monitor.
<br> Step 2 : Interface Arduino board with LCD I2C and to print on display.
<br> Step 3 : Modify the program to get desired outputs on display of LCD I2C


## OUTPUT

![IMG_1](https://github.com/user-attachments/assets/d91ea7ef-ddce-4b4a-b91b-2932dd2e5b11)


## REFERENCE

<br> LiquidCrystal 16x2 library : https://github.com/arduino-libraries/LiquidCrystal
<br> LiquidCrystal 16x2 code : https://docs.arduino.cc/learn/electronics/lcd-displays/
<br> Keypad library : https://github.com/Chris--A/Keypad
<br> keypad 4*4 code : https://www.electronicwings.com/arduino/4x4-keypad-interfacing-with-arduino-uno
