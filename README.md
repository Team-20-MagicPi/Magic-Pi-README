# Magic Pi

It is an unusual mirror which can help you enjoy your life.

## Table of Contents

* [Background](#Background)
* [Introduction](#Introduction)
*  [Hardware and software](##Hardware and software)
* [Contributing](#Contributing)

## Background

**Magic Pi** is an unusual mirror which can help you enjoy your life. 

Makeup mirror is an normal object in our daily life. But imagine how amazing it would be when it represents you with daily information such as calendar, weather and news, and even play music for you! 

When combining the magic mirror in the science fiction film with the real-life makeup mirror, a special product called **Magic Pi** controlled by the Raspberry Pi is born.

## Introduction

### Hardware and software

**Hardware**

* [Raspberry Pi 4 Model B](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)

**Sensors** 

* sound transducer
* Gesture Recognition Module
* Infrared sensor module 
* Temperature and humidity sensor module

**Others**

* breadboard  
* Dupont Line 
* LCD(Liquid Crystal Display) 
* mirror glass

**Software**

* [Raspberry Pi OS(previously called Raspbian)](https://www.raspberrypi.org/software/)
* [wiringPi](http://wiringpi.com/download-and-install/)

### General view

The schematic view can be found below: 

https://github.com/Team-20-MagicPi/Schematic-View

This is our finished product(prototype):

![e27278ed54091cdcc9480c2fa1f231f](https://user-images.githubusercontent.com/49462534/115292403-d1d6c880-a14d-11eb-9b7b-6365bad84a63.jpg)
![26a9eae0384ef3f3e8f50f4ba700fd0](https://user-images.githubusercontent.com/49462534/115292413-d4392280-a14d-11eb-9961-4ff49e073f49.jpg)





**Magic Pi** has multiple functions:

* Body detection to wake it up.
* Voice Detection to control the lights.
* Information display, including temperature and humidity detection, real-time weather, daily news, etc.
* Gesture sensor to control the media center.

 

### Body detection

### Voice detection

A voice sensor can detect the environmental voice and output high voltage as a signal. (However this cannot tell the exact signal of the sound)

**In this program we connect the signal pin to port 7 of the Raspberry Pi, and a led is connected to port 26.**

Thus, when we clap our hands, the voice would give a high voltage signal and raspberry pi can control the led accordingly.

More details: https://github.com/Team-20-MagicPi/VoiceDetector

### Temperature and humidity detection

Low-cost DHT temperature and humidity sensor has a general basic function, speed is not fast, but for the basic data recording enthusiasts are very suitable. DHT sensor is composed of two parts, namely capacitive humidity sensor and thermistor. 

There's also a very basic chip inside that can do some analog-to-digital conversion and read digital signals of temperature and humidity.

The digital signal is easily read with any microcontroller.

More details: https://github.com/Team-20-MagicPi/temperature-and-humidity-detection

### Gesture sensor

## Contributing

@[Touru97](https://github.com/Touru97)

@[Sei2112](https://github.com/Sei2112)

@[Zhou Shuaii](https://github.com/ZhouShuaii)

@[JiajianYou](https://github.com/JiajianYou)

Don't forget to follow our ins: https://www.instagram.com/magicm1rrorpi/
