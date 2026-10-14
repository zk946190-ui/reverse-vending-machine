# Reverse Vending Machine (Arduino Mega)

An academic smart-recycling prototype that supports segregation of plastic, metal and glass waste and rewards users via SMS.

## Features
- Detects and segregates plastic, metal and glass waste
- User identification and reward workflow
- SMS reward notifications through a GSM module
- Bluetooth admin panel
- Status display on an LCD

## Hardware used
- Arduino Mega
- Load cell
- IR sensor
- Metal sensor
- Servo motor
- 16x2 LCD
- GSM module (SIM800L/SIM900A)
- HC-05 Bluetooth module
- hexa keypad 

## How it works
1. using blutooth application admin will add user using his details such as contact and name and then provide a registration number to user
2. user can enter that registration number using hexa keypad and LCD
3. After that he can insert any waste item such as metal glass or plastic
4. here we used metal sensor for metal detection and load cell for plastic and glass item machine segregate based on item using servo motor
5. user receive sms notification on his registered mobile number he received points everytime he insert waste item as reward.

## Future improvements
here we can also provide location of the machine to garbage when collector when machine get full so they can collect waste item from Machine 

## Author
Bibi Zainab – [LinkedIn](https://www.linkedin.com/in/bibi-zainab-dhalayat-929b2b41a)
