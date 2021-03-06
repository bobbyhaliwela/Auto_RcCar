# AutoRcCar

**AutoRcCar** is a personal project of the author to develop a better understanding on how deep learning can be used for self driving car. 

The project used a 1/10 scale Tamiya RC car to represent a real life car and a raspberry pi as its brain. The project aim to use both behavioral clonning and reinforcement learning technique to drive the car autonomously. For the time being, only behavioral clonning has been implemented. A convolutional neural network is used to generate both steering angle and throttle values for the car to drive itself around the track. The project used Nvidia PilotNet architecture to do this. You can read more about Nvidia PilotNet here: https://arxiv.org/pdf/1704.07911.pdf

## Acknowledgements

**Uvindu J Wijesinghe's RCAutopilot** project, which helped build the foundation of this project, which is to control the rc car using PS4 controller and labelling the training data. This project used his code to implement this. You can read more about his project here: https://github.com/UvinduW/RCAutopilot

## Prerequisites

If you wish to build a similar project, these are the pre-requisites for both hardware and software.

### Hardware

- Raspberry Pi 3
- Raspberry Pi Camera - fish eye is preffered
- 1/10 RC Car
- ESC - usually comes with the RC Car
- Servo
- PS4 controller
- 7.2v 5000mah NiMH battery - min 3000mah is preffered
- Jumper wire - Male to Female

**Note: You can use XBox controller as well but you need to install the driver for the controller on ubuntu.**

### Software

You don't have to install the exact same version of these packages, but be sure to see the documentation if you are running a newer version and make the necessary changes to the code.

- Ubuntu 16.04
- Python 3
- Scipy 1.1.0
- OpenCV 3.1.0
- Numpy 1.15.4
- PIL 5.3.0
- Matplotlib 3.0.1
- PyGame 1.9.4
- TensorFlow 1.11.0
- Keras 2.2.4
- pigpio - install only on raspberry pi: http://abyz.me.uk/rpi/pigpio/download.html
- jstest-gtk - to calibrate PS4 controller

## How To
### Wiring

Follow these instructions carefully if you don't want your raspberry pi get fried!

