# Three_Button_LED_Project
An Arduino project to control 3 LEDs using 3 pushbuttons.

## 🔧 Components Used:
- Arduino Uno R3
- Breadboard
- 3x LEDs (Red, Blue, Grey)
- 3x 220Ω resistors (for LEDs)
- 3x Pushbuttons
- 3x 10kΩ resistors (for buttons - pull-down)
- Jumper wires

## ⚙️ Circuit Description:
- Each pushbutton is connected to a digital input pin (2, 4, 7).
- Each LED is connected to a digital output pin (8, 12, 13).
- Pull-down resistors ensure proper button reading.
- When a button is pressed, the corresponding LED turns on for 300ms.

## 💡 Code:
The code is in the file [`main.ino`](main.ino)

## 🔗 Tinkercad Link:
[Open Circuit on Tinkercad](https://www.tinkercad.com/)  
(📌 Add your actual Tinkercad link here)
