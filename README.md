# LED-blinker-using-Arduino
This code can be used to make LED blinker using Arduino.This code is also compatible with ESP8266P microcontroller.
Mainly three funtions are used in this code-
pinMode()-To define the pin and set the LED for basic Input/Output response.
delay()-This function is use to produce delay in time(milliseconds),without delay function blinking action cannot be done as microcontroller processes each function very quickly and it becomes impossible for us to observe the response.
digitalWrite()-It is used to put the LED in ON and OFF state. 

The last two functions should be written in void loop() as these are the set of statements which we want to repeat again and again for
blinking.
Moreover the first function pinMode() should be written in void setup() as we want to define or set a digital pin for LED.If we will not set the pin for LED and the mode -how we want to use it i.e. either as a input or output then in that case we will not be able to blink that LED even if we have written correct logic for blinking in void loop().
