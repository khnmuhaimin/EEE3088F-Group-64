# EEE3088F Micromouse Design Project

## Overview

This repository contains the design and implementation of the sensing and power subsystems for a micromouse project. The sensing subsystem is responsible for detecting walls and approximating distances to these walls using infrared (IR) sensors. The power subsystem is responsible for supplying power to the rest of the micromouse and controlling the motors used to move the micromouse around. This README provides an overview of the project.

## General Micromouse Features

- **Wall Detection**: Detects the presence of walls in three directions: forwards, left, and right.
- **PCB Design**: Includes the design of a custom PCB that integrates with the micromouse.
- **Autonomous Navigation**: Explores and solves a maze autonomously.

## Necessary Additional Components
- **STM32L476 microcontroller**
- **Motherboard PCB with PIN connections**
- **Wheels and motors for movement (multi-rotational drawing approximately 200mA each**
- **Battery LiPo 800mAh 3.7V**
- **Battery, Power and Sensing headers need to be purchased and soldered on during assembly**
- **5V Power supply for charging**
- **Device capable of running MATLAB**

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/khnmuhaimin/EEE3088F-Group-64.git
    ```

2. Navigate to the project directory:

    ```
    cd EEE3088F-Group-64
    ```

3. Use KiCad to open up the project files for the custom PCB design.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributors (Group 64)

- Luke Carter(CRTLUK001)
- Muhaimin Khan(KHNMUH063)
