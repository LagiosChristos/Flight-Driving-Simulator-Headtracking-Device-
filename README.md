# Intro

This project is a DIY head-tracking device built using an Arduino Micro and a BNO055 absolute orientation sensor in combination with OpenTrack software, designed for use in flight and driving simulators. It captures real-time head movement and translates it into in-game camera control, providing a more immersive and intuitive experience without the need for expensive commercial hardware.

# Hardware and Software

**Hardware**

* Arduino Micro
* BNO055 9-Axis IMU
* Jumper Wires
* Case
* Velcro

**Software**

* Arduino IDE
* OpenTrack

# Advantages

The main requirement for IR Tracking to work is that you have access to a camera that can achieve at least 30 fps, ideally 60fps, in very low light conditions. This is not standard for very old and/or cheap webcams. Using an IMU (Inertial Measurement Unit) that is strapped to a headset, it is possible to use the orientation of the sensor to send the head rotation data of the user to the PC, allowing for in-game movement of the character's head.

# Demo Images and Videos

