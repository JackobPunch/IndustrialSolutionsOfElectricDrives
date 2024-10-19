# Industrial Solutions of Electric Drives

## Overview

This repository is dedicated to the course **Industrial Solutions of Electric Drives**. It contains materials, source code, and documentation related to the use of both **FPGA** and **microcontroller** technology on the **Digilent Arty Z7-10** development board. The focus of the course is on controlling and simulating industrial electric drives, utilizing both the FPGA and the microcontroller on the board.

The current project involves a basic implementation of controlling **LEDs (diodes), buttons, and switches** using the FPGA. This introductory project helps build foundational skills for more advanced applications, such as electric drive control.

---

## Repository Structure

Currently, the repository contains the following:

- **`/zaj1_18.10.2024`**: This folder contains a Vivado project that implements basic functionality for:
  - **Controlling LEDs (diodes)** based on button and switch inputs.
  - **Reading input from buttons** and toggling outputs.
  - **Interfacing with switches** to manage LED states.

<div align="center">
   <img src="https://github.com/JackobPunch/IndustrialSolutionsOfElectricDrives/blob/main/gif.gif" alt="GIF" />
</div>

The project demonstrates how to handle basic digital I/O using the FPGA on the Digilent Arty Z7-10 board.

More folders and projects will be added as the course progresses, covering further implementations of both FPGA and microcontroller systems for controlling industrial electric drives.

---

## Requirements

### Hardware:
- **Digilent Arty Z7-10** FPGA and microcontroller development board.

### Software:
- **Vivado Design Suite**: Used for designing, simulating, and programming the FPGA.
- **Xilinx SDK**: For embedded software development on the microcontroller (if needed).
