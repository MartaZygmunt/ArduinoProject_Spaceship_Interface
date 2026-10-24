Spaceship Interface
​This project is called Spaceship Interface, based on the classic Arduino setup. It uses three LEDs and a push button to build a basic control panel interface.
​When the button is not pressed, one green LED stays turned on. Once the button is pressed, the two red LEDs start blinking back and forth with a short delay.
​For the hardware setup, I used an Arduino Uno board connected to a breadboard with a push button, three LEDs, a 10k resistor for the button, and 220 ohm resistors for the LEDs.
​The code is saved in Project02.ino. It reads the input from digital pin 2 with digitalRead() and controls the outputs using a simple if/else condition with digitalWrite() and delay().