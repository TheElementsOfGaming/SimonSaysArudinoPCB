# Simon Says Game PCB

This repository hosts the KiCad and Gerber files needed to create a barebones Arduino-compatible board designed to play the Simon Says game. This project aims to provide enthusiasts and learners with an easy way to build and understand a classic game using modern electronics. The design is straightforward, making it an excellent project for those new to PCB design and electronics.

## Introduction

The Simon Says Game PCB is a fun and interactive way to get into electronics and programming. Using KiCad files, users can modify the design according to their needs, while the provided Gerber files are ready for manufacturing, allowing anyone to order a PCB directly from a fabricator.

## Getting Started

### Prerequisites

- KiCad 5.0 or later for editing the PCB design files.
- A PCB manufacturer to produce the board using the provided Gerber files. I use JLCPCB, but feel free to use whatever is most comfortable for you.

### Installation

1. Clone this repository to your local machine
2. Open the KiCad project file to view, modify, or export the design.
3. Use the Gerber files to order PCBs from your preferred manufacturer (These currently aren't available since only the schematic has been created). 

## Hardware Requirements

To assemble and use the Simon Says Game PCB, you will need the following components:

- 1x Atmega328P-PU Microcontroller
- 4x LED (Red, Blue, Green, Yellow)
- 4x 220 Ohm resistors
- 1x Buzzer
- Miscellaneous: Solder, wire, power supply

## Usage

1. After assembling the PCB with the necessary components, upload the Simon Says game code to the microcontroller. You can find example Arduino sketches online or we can write your own. 
2. You'll also need to burn an Arudino bootloader onto the Atmega328P microcontroller. There are plenty of turtoials online to do this or you can purchase a microcontroller that already has the bootloader on it. 
