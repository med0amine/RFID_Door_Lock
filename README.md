This is a door lock with a passcode and RFID access. 

For the hardware, I used an Arduino Uno, a 3x4 keypad, an RFID-RC522, a 100 OHM resistor, a 1N4148 diode, an NPN transistor, and a 16x2 LCD screen with an I2C LCD adapter. 

The following is the hardware design

![RFID_door_lock](https://github.com/med0amine/RFID_Door_Lock/assets/151380756/4cf7e93b-c6d0-46d5-8718-4dbd85eb34da)

![RFID_door_lock_schem](https://github.com/med0amine/RFID_Door_Lock/assets/151380756/9e56266c-7287-4161-85dd-103e4be3e313)

The hardware design was done with Fritzing, while the programming was done in Arduino IDE.

The pre-installed passcode is 1234 and you can change the passcode or assign an RFID card as showing in the menu down below

*000 : to change the passcode

*001 : to aasign the first RFID card

*002 : to assign the second RFID card

*003 : to assign the third RFID card

