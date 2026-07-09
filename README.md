# Pollock Drawing Robot

GPL-2.0 3D-printable autonomous drawing robot for BBC Micro:bit or Arduino-class microcontrollers; simple candidate for refreshed education kit.

## Installation / quick start

## Project

Pollock Drawing Robot

GPL-2.0 3D-printable autonomous drawing robot for BBC Micro:bit or Arduino-class microcontrollers; simple candidate for refreshed education kit.

## Quick start

1. Download the printable files from Printables: https://www.printables.com/model/1776630-pollock-drawing-robot
2. Download this GitHub repository as a ZIP, or clone it:

   ```bash
   git clone https://github.com/ToolKnox/hawkridge-pollock-drawing-robot.git
   ```

3. Use `source/upstream/` for the mirrored software, firmware, PCB, CAD-source, and upstream documentation.
4. Use the Bill of Material PDF attached to the Printables Documentation section for parts planning.
5. Read the project-specific notes below before powering electronics or uploading firmware.

## Software / firmware setup

- Open the `.ino` sketch from `source/upstream/` in Arduino IDE, install libraries listed in the upstream README/source, select the target board/port, then upload.
- Desktop/control utilities are under `source/upstream/`; use the upstream README and project files there for dependencies and launch commands.

## Main software/config files

- `source/upstream/arduino/Basic_Robot_Commands.ino`
- `source/upstream/arduino/Pollock.ino`
- `source/upstream/microbt/pollock.py`

## PCB / electronics design files

- No PCB/manufacturing files detected.

## Upstream documentation mirrored here

- `source/upstream/README.md`

## Original source

https://github.com/seancuttlefish/pollock


## Where to find things

- Printables model and printable files: https://www.printables.com/model/1776630-pollock-drawing-robot
- Bill of Material: `Pollock Drawing Robot Bill of Material.pdf` in the Printables Documentation section
- Full mirrored upstream source/software/PCB files: `source/upstream/`
- Source asset index: `docs/source-assets.md`
- Standalone install/build guide: `docs/INSTALLATION.md`

