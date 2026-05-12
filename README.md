# final_iot_project

#Smart Door Lock System Using RFID Authentication and Telegram-Based Alert Mechanism

#Overview

This project is an IoT-based smart security system using Arduino Uno, RFID, OTP verification, ESP8266, and Telegram alerts. The system provides two-factor authentication for secure door access.

When a valid RFID card is scanned, an OTP is sent to Telegram through ESP8266. The user enters the OTP using a keypad. If the OTP is correct, the servo motor unlocks the door. Unauthorized access attempts generate Telegram alerts.

#Features
RFID authentication
OTP verification
Telegram alerts
Servo motor door lock
LCD status display
Two-factor authentication
Unauthorized access detection

#Hardware Used
Arduino Uno
ESP8266
MFRC522 RFID Module
RFID Card/Tag
16x2 LCD
4x4 Keypad
Servo Motor
Breadboard & Jumper Wires

#Software Used
Arduino IDE
Embedded C/C++
Telegram Bot API

#Working
Scan RFID card
System verifies UID
OTP is sent to Telegram
User enters OTP through keypad
If OTP is correct → Door unlocks
If wrong OTP/card → Access denied

#Security Features
Two-factor authentication
OTP-based access
Wrong card alerts
System lock after multiple failed attempts

#Applications
Homes
Offices
Laboratories
Hostels
Restricted areas

#Future Scope
Fingerprint authentication
Face recognition
Mobile app integration
Cloud database support

#Conclusion

The project successfully provides a smart and secure door lock system using RFID authentication and Telegram-based OTP verification with IoT technology.
