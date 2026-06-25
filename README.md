# FPGA Security Watchdog

A digital logic prototype simulating hardware-level security against DMA (Direct Memory Access) attacks. 

## Overview
This project implements a "Hardware Watchdog" using digital logic gates.
It monitors the memory access frequency on a bus.
If the access threshold is exceeded (simulating a high-speed malicious data extraction attempt), the system triggers an alarm and blocks further access.

## Features
- Hardware-based anomaly detection.
- Utilizes 8-bit counters and comparators.
- Real-time simulation of security triggers.

## How to use
1. Open the project in **Logisim-evolution**.
2. Use the **Poke** tool to simulate clock pulses (memory access requests).
3. Observe how the LED triggers once the threshold (3) is exceeded.
