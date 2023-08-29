# LCD Controller for SPI TFT LCD (RP2040)

![LCD Controller](lcd_controller.jpg)

This repository contains a simple LCD controller project designed for an SPI TFT LCD panel, which was acquired from AliExpress. The controller is built using an RP2040 microcontroller, and the pin configuration is compatible with the original setup.

## Project Overview

The LCD controller is developed using CircuitPython from Adafruit Industries, leveraging their libraries to simplify code development. The two main libraries used in this project are:

1. `adafruit_st7789`: This library facilitates communication with the SPI TFT LCD panel.
2. `adafruit_display_text`: The library is used for rendering text on the LCD screen in a straightforward manner.

## Hardware Setup

To replicate this project, follow these hardware setup steps:

1. Connect the SPI TFT LCD panel to the RP2040 using the universal pin configuration.
2. Ensure that the pin connections match those of the original setup to maintain compatibility.

## Installation

Follow these steps to set up the project:

1. Clone this repository to your local machine.
2. Ensure you have CircuitPython installed on your RP2040. If not, follow the instructions on the [CircuitPython website](https://circuitpython.org/board/raspberry_pi_pico/) to install it.
3. Copy the required libraries (`adafruit_st7789` and `adafruit_display_text`) to your RP2040. You can find these libraries on the [Adafruit CircuitPython Bundle](https://circuitpython.org/libraries) page.
4. Upload the project code (`st7789_lcd_controller.py`) to your RP2040.

## Usage

After setting up the hardware and uploading the code, power on the system. The RP2040 will initialize the LCD panel and display the specified text using the Adafruit libraries. Feel free to modify the `st7789_lcd_controller.py` file to customize the displayed text or other features of the LCD.

## Contributing

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or a pull request in this repository.

