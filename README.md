# LabVIEW HEX Data Conversion VI

A small NI LabVIEW VI that accepts numeric input from the front panel and displays the value in hexadecimal format in real time.

## What it does

- Reads numeric input from LabVIEW front panel controls
- Converts the input value to hexadecimal format
- Displays the hexadecimal result on the front panel
- Useful for quick data representation checks and debugging small values

## How to run

1. Open NI LabVIEW.
2. Open `src/HEX.vi`.
3. Run the VI.
4. Enter a numeric value in the front panel control.
5. Observe the hexadecimal output.

## Requirements

- NI LabVIEW
- LabVIEW Virtual Instrument support (`.vi` files)

## Context

Built while learning LabVIEW data handling and front panel interaction. The same LabVIEW fundamentals were later applied during my internship at Benchmark Electronics, where I developed a driver for the QL TTI 355 programmable power supply.

## Screenshots

### Front Panel

![Front Panel](docs/screenshots/front_panel.png)

### Block Diagram

![Block Diagram](docs/screenshots/block_diagram.png)
