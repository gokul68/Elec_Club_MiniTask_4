# Elec_Club_MiniTask_4
# 1. Smart Glove Computer Mouse
The pipeline of this project is:

Sensors (accelerometer/pushbutton) => Microcontroller => Bluetooth module => Python code

So the problem will be in one of the following modules:

1. Sensor module

2. Bluetooth module

3. Code

**Sensor module:**

Since we are using both accelerometers and pushbuttons, we'll know if there is a problem with the sensors if it works for clicks and not movement and vice versa. If clicks are registered properly and motion is not, then the problem must be with the accelerometer and vice versa.

First, we should ensure that there are no short circuits or loose connections using a multimeter. Then, we should check if the connections are correctly made. If the connections are fine, you should connect the microcontroller to your computer and print the sensor values on the serial monitor. If it is showing incorrect values, it is likely to be a faulty sensor.

**Bluetooth module:**

If there is no problem with the sensors, we move on to the bluetooth module. Just like before, we ensure that there are no short circuits or loose connections and that the connections are correct. If the connections are fine, we should write a python code to print the values it receives from the bluetooth module. If this doesn't work then there must be some problem in establishing the bluetooth connection or the bluetooth module is faulty.

**Code:**

If the sensors and bluetooth module are fine, then you should check the code. Make sure that all the data is received and transmitted properly in the Arduino code. In the python code make sure that all the data is received in the right form and processed properly.
