# Investigation

Generally my solution tends towards a [Servomotor](https://en.wikipedia.org/wiki/Servomotor). Some reasoning can be found at the bottom of this document. The investigations for each part of a servo got its own chapter.

## 1) Commercial Servos

Servos are used in model airplanes and simple robot arms for up to $1000. Here are the advantages and disadvantages

## 2) Reducer - cycloidal drive, harmonic drive and epicyclic gearing

- Epicyclic gearing - planetary gear
- Harmonic drive or strain wave gear

## 3) Brushless DC motor or stepper motor?

Comparison power/volume and power/mass of both

## 4) ESC for BLSC

How does it work

## 5) Controller for ESC with STM32F103 or ESP32

The F103 is $1.50 but the F401 is only $2.05 - should I upgrade? 32bit is great, no 8bit ATMEGA. But ESP32? Wifi not needed!

## 6) Connector standardization

XT60 as the ___ from MIT ?

## 7) Bus protocoll on CAN bus

Defined as

## 8) ESC - Electronic control unit - how?

...

## 9) Software interface to control and drive

... waypoints defined how? smooth movement, acceleration in the ESC, controller or actuator? inverse kinematics realized how?

- Chilipepr has a web interface, you can connect your XBOX controller. But then you need TinyG for further steps ...
