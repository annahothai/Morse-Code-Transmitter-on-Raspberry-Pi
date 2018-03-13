# Morse-Code-Transmitter-on-Raspberry-Pi

To those outside of Mr.Walker's class, this is a school project for my Computer Science class.

###Direction
## Setting up the breadboad
Before doing anything, make sure to disconnect the Raspberry Pi. You can damage your Raspberry Pi or fry your LEDs if you assemble the parts incorrectly. 

1. Connect the cobbler and ribbon to the Raspberri Pi and the breadboard.
 
2. Place the LED on an empty column on the breadboard (a column that isn't connected to the cobbler), both legs should be in the same column (vertical).

3. Then, take the resistor, connect one end to the same row (horizontal) as the short (cathode) leg of the LED. Connect the other end to one of the "ground" (GND) pins 

The finished product should look like this: 

![]https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Set%20Up%20Image/setup5.jpg)

![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Set%20Up%20Image/setup4.jpg)

![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Set%20Up%20Image/setup3.jpg)

5. You're done with the setup! Let's get to the code
 
 
 ## Python
 1. You can now plug in your Raspberri Pi
 2. Log into your Raspberry Pi account. Then, create a python file. This is done by right clicking on your desktop --> New --> Text Document(or text file), name it what ever you want with a ```.py``` extension after the name. I called mine MC.py (for Morse Code).
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python2.png)
 
 A blank Python file will appear on your desktop, double click on it to edit the file
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Pyhon1.PNG)
 
 3. Copy and paste the code from [MC.py](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/MC.py)
 (The code was not created by me. It was by [Steven Childrey](https://github.com/Stevenchi36/LED-Morse-Code-for-Raspberry-Pi) and I give all the credits to him).
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python3.png)
 
4. Save it!
 
5. Open the terminal and type in
 ```sudo python (whatever path you save your MC.py file on) ``` 
(For your path, you can right click on your file and "Copy Path" and then paste it onto the terminal)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python4.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python4.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python6.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python7.jpg)
 
6.Press Enter, enter your password for you sudo access
 
7. Your screen will ask for a text that will be transmitted to a morse code! Type a word or something in!
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python8.jpg)
 
 ![](https://github.com/annahothai/Morse-Code-Transmitter-on-Raspberry-Pi/blob/master/Python%20Scripting%20Images/Python9.jpg) 
 
 8.  The LED will blink morse code! (.... . ._.. ._.. ___ __. ___ ._. ._.. _.. reads HELLO WORLD)
 Here's a [video](https://youtu.be/c72rko-nqZQ) of it blinking! (Yes, I realize I filmed vertically, who cares. The video quality isn't super good.) 
 
