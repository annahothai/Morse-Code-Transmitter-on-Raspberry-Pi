# Morse-Code-Transmitter-on-Raspberry-Pi

To those outside of Mr.Walker's class, this is a beginner Raspberry Pi project for my IB Computer Science class.

## What Are We Doing?
In this tutorial, we will make an LED signal morse code with a Raspberry Pi as inspired by [Steven Childrey's code on GitHub](https://github.com/Stevenchi36/LED-Morse-Code-for-Raspberry-Pi/blob/master/README.md). For those who are unfamiliar with morse codes, you can refer to a guide from this image ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Morse%20Code%20Guide.png)

## Materials
For this project, you will need:
1. 1 Raspberry Pi 3 and SD card
2. 1 Pi Cobbler breakout and ribbon wire
3. 1 Male/Male Jumper Wire
4. 1 Resistor
5. 1 LED
6. 1 Breadboard
7. USB cable to connect your Raspberry Pi

### Direction
## Setting up the breadboard
Before doing anything, make sure to disconnect the Raspberry Pi. You can damage your Raspberry Pi or fry your LEDs if you assemble the parts incorrectly. 

1. Assemble the cobbler breakout and ribbon wire to the Raspberry Pi and the breadboard.
 
2. Place the LED on an empty row on the breadboard (a row that isn't connected to the cobbler breakout), both legs should be in the same column (vertically).

3. Take a male/male jumper wire, connect one end to the same row (horizontally) as the long (anode) leg of the LED. Connect the other end to pin number 21. 

4. Then, take the resistor, connect one end to the same row (horizontally) as the short (cathode) leg of the LED. Connect the other end to one of the "ground" (GND) pins 

The finished product should look like this: 

![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Set%20Up%20Image/setup5.jpg)

![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Set%20Up%20Image/setup4.jpg)

![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Set%20Up%20Image/setup3.jpg)

5. You're done with the setup! Let's get to the code
 
 
 ## Python
 1. You can now plug in your Raspberry Pi with the USB cable.
 2. Log into your Raspberry Pi account. Then, create a Python file. This is done by right clicking on your desktop --> New --> Text Document(or text file), name it what ever you want with a ```.py``` extension after the name. I called mine MC.py (MC for Morse Code).
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python2.png)
 
 A blank Python file will appear on your desktop, double click on it to edit the file.
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Pyhon1.PNG)
 
 3. Copy and paste the code from [MC.py](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/MC.py)
 (The code was not created by me. It was by [Steven Childrey](https://github.com/Stevenchi36/LED-Morse-Code-for-Raspberry-Pi) and I give all the credits to him).
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python3.png)
 
4. Save it!
 
5. Open the terminal and type in
 ```sudo python (whatever path you save your MC.py file on) ``` 
(For your path, you can right click on your file and "Copy Path" and then paste it onto the terminal)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python4.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python5.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python6.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python7.jpg)
 
6.Press Enter, enter the password for your sudo access
 
7. Your screen will ask for a text that will be transmitted to a morse code! Type something in!

 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python8.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python9.jpg) 
 
 8.  The LED will blink morse code!
 Here's a [video](https://youtu.be/c72rko-nqZQ) of it blinking! (Yes, I realize I filmed vertically, who cares. The video quality isn't super good.) 
 
 
 ## Changes you can make to the code
If you used a different pin than pin#21, you can change the number on line 7 in the code to whatever pin you used
```led = LED(21)```

To change the speed of the morse code, you can change the percent of the speed in line 8
```speedPercent = 100```
The lower the number, the slower it will be.
