---
layout: about
title: Use-Cases
---

The DDK is an open-source hardware and software toolchain designed with hardware reverse-engineering and security analysis in mind.
This page provides an overview of the DDK's core features as well as a several use-cases.
If you're interested in a more detailed description of what the DDK can be used for, please reffer to our [WOOT 2013 paper](http://www.sec.t-labs.tu-berlin.de/~nedos/woot2013.pdf).

## Key Features

* Low cost development and attack-platform
* ARM MCU + FPGA + FTDI USB UART
* Easy access to I/O
  - RJ-45 expansion jacks with +5V and GND
  - Standard headers for breakout
  - Buffered, protected 3V/5V tolerant I/O
  - ARM JTAG and FPGA JTAG
* 5V USB-Bus-powered device, optionally over a USB Y-Cable

### LPC17 family Cortex-M3 ARM

* Up to three bi-directional UARTs to the FPGA
* Dedicated UART interface to the PC via FTDI USB
  - Provides Command Line Interface for user interaction
  - Non-Interactive mode for transferring data
  - On-chip boot-loader for USB upgradable firmware
* Control and configuration of all onboard- and FPGA-peripherals

### FPGA

* USB upgradable bit-stream
* 48 GPIO, eight channels with six bi-directional lines
* Wishbone compatible internal bus
* Extensive expansion capabilities

## Example Use-cases

* Parallel analysis
  - Fuzzing
    * Automatic target crash detection
    * Automatic hardware reset of target

  - Glitching
    * Expansion jacks provide easy interface to targets
    * Onboard input protection
            
    
* Instrumentation
  - Passive/Active analysis of embedded busses
  - Timing-critical analysis applications
  - Hardware triggering
  - Analysis of proprietary protocols

* Hardware-offloading
  - Real time analysis
  - Hardware event filters
  - Serialized output of relevant data
