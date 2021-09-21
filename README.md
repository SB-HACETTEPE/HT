# An Iot Model for measuring temp and humidity of the room, The device is an ardiiuno platform with STM32F103RC microcontroller, we use an led screen in order to print the sensors values, the model is connected to ENC28J60 Ethernet model, in order to be connected to the internet,
An image of the model connected to the microcontroller is shown below;
![alt text](https://github.com/SB-HACETTEPE/HT/blob/main/ENC.png?raw=true)








As the Microcontroller works as server of a basic html page, there is basic html page code in the head of the "main" file;

MIAN FUNCTIONS:
In order to Read/Write over EEPRON Memory, there are "EEPROM_string_write", and  "readStringFromEEPROM" function which takes offset as parameter, and takes string to write in write function.

"PrintScreen" function takes string as parameter and prints it to the led screen.

Please refere to the details in the codes to see the fuul program functions.
