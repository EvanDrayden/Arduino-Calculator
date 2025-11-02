This project implements a fundamental four-function calculator (Addition, Subtraction, Multiplication, and Division) using an Arduino Uno or compatible microcontroller. Input is managed via a 4x4 Keypad, and all feedback and results are presented on a 128x64 I2C OLED Display (SSD1306).
The design focuses on clear, large text for input and includes utility features such as a loading animation, input clearing, and a dynamic blinking cursor.
1 x Arduino Uno (or compatible board)

1 x 128x64 I2C OLED Display (SSD1306, I2C Protocol)

1 x 4x4 Membrane Keypad

Jumper Wires for connections

Wiring and Connections

OLED Pin              Arduino Pin
GND                   GND
VCC                   5V
SCL                   A5 (Analog Pin 5)
SDA                   A4 (Analog Pin 4)


Keypad Pin               Arduino Pin
Row 1                    Digital Pin 9
Row 2                    Digital Pin 8
Row 3                    Digital Pin 7
Row 4                    Digital Pin 6
Column 1                 Digital Pin 5
Column 2                 Digital Pin 4
Column 3                 Digital Pin 3
Column 4                 Digital Pin 2

You can change the watermark with your name.

If the keypad is malfunctioning, check out the code of my Keypad Testing post. You may need to change the keypad rows and cols in the code.
