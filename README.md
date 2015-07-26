# barebone-attiny85-duino
I wanted to create my own little Arduino, so I build one that uses the attiny85.

I designed the PCBs in Eagle and ordered them from oshpark.
My board only needs two passives: one *.1 uF smoothing cap*, a *10K reset resistor* and a *4K7 resistor* for the LED.
The LED is attached to the pin 0 of the attiny, which is also the MOSI pin.

The arduino is programmed via ICSP. You can get a ICSP programmer for under 3 USD on aliexpress.

If you have questions, I`m @eliabieri on twitter.

![alt tag](https://raw.githubusercontent.com/eliabieri/barebone-attiny85-duino/master/image.jpg)
