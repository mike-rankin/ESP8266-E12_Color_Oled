# ESP8266-E12 Color Oled
ESP8266-E12 Color Oled

Revision 1 of this design appears to work fine so far.

Assembly instructions

-send the gerbers to OSH Park to have the board manufactured https://oshpark.com/shared_projects/nUYMQMXi the price for three 4 layer pcbs is $12.50
-follow the bom when ordering and hand stuffing components, solder on the oled display but do not tape it down
-burn in the bootloader using the Segger J-link, Digi-Key #899-1008-ND, 899-1012-ND
-follow the bootloader instructions: https://learn.adafruit.com/proper-step-debugging-atsamd21-arduino-zero-m0/restoring-bootloader
-pogo pins are needed for the bootloader: MILL_MAX 855-22-010-10-001101
-connect the board to the Arduino IDE, load in the sketch and if the display works tape it down
