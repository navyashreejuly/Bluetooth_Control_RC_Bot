# Bluetooth Controlled RC Bot

## Project Overview

This project introduces a Bluetooth-controlled RC bot, a remote-controlled robot that can be manipulated using a smartphone application. The Bluetooth RC car app installed on the smartphone communicates with the robot, allowing users to control its movements in different directions.

## Table of Contents

- [Introduction](#introduction)
- [Components](#components)
- [Circuit Connections](#circuit-connections)
- [Prototype](#prototype)
- [Code](#code)
- [Conclusion](#conclusion)

## Introduction

In the realm of robotics and remote control technology, the Bluetooth-controlled RC bot showcases human ingenuity and technological innovation. This project addresses the challenge of creating a versatile and user-friendly solution for remotely controlling a robot, resulting in a remarkable prototype that bridges the gap between human desires and machine capabilities.

Bluetooth Rc car app is installed in Smartphone which helps to control the robot car, motors and motor drivers which moves robot cars in several places Bluetooth Rc car app has different common keys to move the robot in different directions with the help of Smartphone.
               
In the ever-evolving realm of robotics and remote control technology, the creation of a Bluetooth-controlled RC bot stands as a testament to human ingenuity and technological innovation. This project addresses the final challenge in achieving a versatile and user-friendly solution for remotely controlling a robot, and the result is a remarkable prototype that bridges the gap between human desires and machine capabilities.

*The app includes common keys to move the robot in different directions.*

## Components

- Arduino Uno 
![Arduino Uno](https://5.imimg.com/data5/NB/KR/OH/SELLER-19590896/arduino-uno-r3-atmega16u2-atmega328-dip-.jpg)

- L298N Motor Driver
![L298N Motor Driver](https://components101.com/sites/default/files/component_pin/L298N-Module-Pinout.jpg)

- Bluetooth Module  
![Bluetooth Module ](https://5.imimg.com/data5/SELLER/Default/2020/11/ZL/DO/GJ/15458098/hc05-bluetooth-module-500x500.jpg)

- BO Motor with Wheel
![BO Motor with Wheel ](https://www.robotbanao.com/cdn/shop/products/2-x-duel-shaft-bo-motor-with-wheel-black-and-yellow-2-sets-combo-32482981183724.jpg?v=1635000844)

- Jumper Wire
![Jumper Wire ](https://m.media-amazon.com/images/I/71DvlkHeCuL.jpg)


## Circuit Connections

### L298N Motor Driver and Arduino Uno

| L298N Motor Driver | Arduino Uno       |
|-------------------- |------------------ |
| 12V Adapter / Battery VIN | Adapter / Battery (+) |
| GROUND | Adapter / Battery (-) |
| 5V (Optional) | When using an adapter, 5V is not required. If using a battery, connect Vin. |
| IN1 | Arduino Pin 2 |
| IN2 | Arduino Pin 3 |
| IN3 | Arduino Pin 4 |
| IN4 | Arduino Pin 5 |
| ENA | Arduino Pin 9 |
| ENB | Arduino Pin 6 |

### Bluetooth Module and Arduino Uno

| Bluetooth Module | Arduino Uno   |
| ---------------- | ------------- |
| TX               | Arduino Pin 10 |
| RX               | Arduino Pin 11 |
| Ground (GND)     | Arduino Ground |
| VCC              | Arduino 3.3V   |

## Prototype

The prototype demonstrates seamless control of a remote-controlled robot through Bluetooth connectivity. This user-friendly interface adapts to various tasks, from navigating complex environments to facilitating remote surveillance. The project merges hardware and software into a harmonious and intelligent machine, responding to our desires for mobility, exploration, and innovation.

*The final challenge in this project revolves around the seamless control of a remote-controlled robot through Bluetooth connectivity. This challenge demands a user-friendly interface that can adapt to various tasks, from navigating complex environments to facilitating remote surveillance. As such, the prototype not only exemplifies a culmination of technical expertise but also demonstrates its adaptability to meet a multitude of real-world needs.*

*This prototype represents the embodiment of our endeavors in merging hardware and software into a harmonious and intelligent machine. It is a testament to the capacity of technology to respond to our desires for mobility, exploration, and innovation. In the following sections, we will delve deeper into the intricacies of this Bluetooth-controlled RC bot, exploring its design, functionality, challenges, and future possibilities. This prototype offers a glimpse into a future where remote control technology takes center stage in our everyday lives, shaping the way we interact with and manipulate our surroundings.*

## Code

[Link to Arduino Code](https://drive.google.com/file/d/1MibVhqlipPTvUA-c9KLxPG2MJyZbTV0B/view)

## Conclusion

The Bluetooth-controlled RC bot effectively meets the requirements by providing a user-friendly, wireless remote control interface. The system is customizable and expandable, accommodating various applications. Challenges like limited range and safety concerns exist, offering opportunities for learning and future enhancements. Overall, it addresses the problem of remote control in robotics, providing a practical, hands-on solution with a promising future.

*The proposed solution, a Bluetooth-controlled RC bot, effectively meets the requirements of the problem. It provides a user-friendly, wireless remote control interface, allowing for convenient and flexible operation of the robot. The system is customizable and expandable, accommodating a wide range of applications. While challenges like limited range and potential safety concerns exist, the project offers valuable learning experiences and the potential for future enhancements. Overall, it addresses the problem of remote control in robotics, offering a practical, hands-on solution with a promising future.*

Feel free to contribute, report issues, or suggest improvements!