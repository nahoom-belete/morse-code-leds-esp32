# ESP32-Based Morse Code Simulator

A simple ESP32 project that uses three LEDs to visually transmit Morse code messages. The LEDs indicate dots, dashes, and message status through timed light patterns.

## Description

This project demonstrates Morse code encoding on an ESP32 using LED outputs. It showcases GPIO control, timing, and basic communication concepts using the PlatformIO framework.

## Features

- Morse code message transmission
- Three-LED visual output
- Configurable messages
- Built with PlatformIO and Arduino

## Demo

![Demo](assets/demo.gif)

[View a simulation on Wokwi](https://wokwi.com/projects/466894920272286721)

## Hardware Requirements

- ESP32 development board
- 3 LEDs
- 3 current-limiting resistors (220 Ω)
- Breadboard
- Jumper wires
- USB cable

## Installation

Clone the repository:

```bash
git clone https://github.com/nahoom-belete/morse-code-leds-esp32.git
```

Open the project in Visual Studio Code with the PlatformIO extension installed.

First build and upload the FileSystem Image:

```bash
pio run --target buildfs
pio run --target uploadfs
````

Build and upload the firmware:

```bash
pio run
pio run --target upload
```

## Usage

1. Connect the LEDs according to the wiring configuration.
2. Upload the firmware to the ESP32.
3. Power the board.
4. Observe the LED sequence as Morse code is transmitted.

## Configuration

Update the message and GPIO pin assignments in the source code to customize the behavior.

## Project Structure

```text
.
├── include/
├── src/
├── lib/
├── data/
├── platformio.ini
└── README.md
```

## License

This project is licensed under the MIT License.