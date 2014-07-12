---
layout: about
title: Keep It Synple Stupid
subtitle: Utilizing Programmable Logic for Hardware Reverse-Engineering
---

## Brief Description

Performing analysis of embedded hardware often requires the correct hardware tools for the job.
In this course we focus on how to efficiently offload common hardware reverse-engineering tasks to custom logic implementations.
This course covers the theory and practical aspects of working with FPGAs and embedded ARM microcontrollers.
Participants will get acquainted with professional workflows for ARM and FPGA/ASIC development.
The course is built around the "Datenkrake" ARM/FPGA Board and each participant will receive a board alongside other course materials.

## Upcoming Events

* REC0N 2015 - Montreal, QC, Canada

## Past Events

* [REC0N 2014](http://recon.cx/2014/trainingsynple.html) - Montreal, QC, Canada
* [REC0N 2013](http://recon.cx/2013/trainingsynple.html) - Montreal, QC, Canada

## Full Description

Off the shelf solutions for high-level hardware reverse engineering inevitably fall short when it comes to analyzing proprietary protocols or where accurate timing is necessary.
Sooner or later, one is faced with the situation that custom hardware can do the job much more efficiently.
Extremely versatile hardware comparable in function to custom ASICs can be implemented by utilizing programmable logic in conjunction with an ARM microcontroller and standard peripheral interfaces.
Custom logic can be effectively used to process proprietary communications protocols and implement additional functionality in resource constrained environments and timing critical applications.

The main goal of this course is to familiarize participants with the concepts necessary to implement custom logic.
The course will cover several techniques for hardware reverse-engineering such as firmware extraction, fuzzing and glitching.
Participants will implement coprocessors on a Field Programmable Gate Array (FPGA) in Verilog HDL and interface them to the ARM microcontroller (MCU) using the C programming language.
The DDK is a low-cost opensource hardware platform consisting of an Actel FPGA and an NXP LPC1700 family ARM Cortex-M3 MCU.
Each participant will receive a DDK board for building custom HW reverse-engineering tools for specific targets.

Participants will become acquainted with the standard FPGA/ASIC development cycle, from simulation to place and route and the resulting netlist timing analysis.
Participants will also gain hands-on experience by applying the techniques introduced in the course to several embedded hardware targets.
One of the primary goals is for students of this course to become familiar with professional development workflows used by real world engineers.
Participants will also be provided an opportunity to work with professional test equipment, such as professional oscilloscopes and logic analyzers, for debugging their hardware and logic.

## Day 1: Introduction

* Theory/Basics
  - Recommended literature
  - Number systems and representations
* Machine-To-Machine Communication

* Logic 101
  - Combinatorics
  - Sequential & combinatorial logic
  - State machines
  - Logical functions & arithmetic computation
  - Logic optimization

## Day 2: FPGA Development

* Hardware Logic Implementation
  - Electronics 101
  - ASICs, TTL-Logic
  - FPGAs, CPLDs
  - Hard vs. Soft Macros

* Verilog 101

* FPGA/ASIC Development Workflow
  - Introduction to typical FPGA toolchain
    1. Behavioural simulation
    2. Synthesis
    3. Place and Route
    4. Timing simulation
  - Design constraints and optimization
  - Best practices

* Hands-on (Simulation and Synthesis)
    1. Combinatorial arithmetic logic
    2. Sequential logic
    3. State machines
    4. Implement bus-connected peripheral

## Day 3: Embedded ARM Development

* Introduction to embedded ARM
  - Introduction to the LPC176x on DDK
  - Features
  - Using compiler & debugger
  - Communication between ARM and FPGA

* Real-time OS
  - Tasks on an RTOS
  - Examples of parallel tasks (DDK)

* HW debugging 101
  - Introduction to test equipment (how it works)
    - Multimeters
    - Oscilloscopes
    - Logic analysers
  - High Level Embedded Hacking Tools

  * Hands-on (ARM Development)
    1. Debug previous day's assignments
      - Use oscilloscope and logic analyzer
    2. Implement C-code for coprocessor

## Day 4: Hardware Hacking

* HW attack vectors
  - DDK as an attack & RE platform
  - Typical fault-classes
  - Attack scenarios
  - Attack mitigation
  - Targets (t.b.a.)

* Hands-On (Attack Targets)
  - Several targets will be provided (t.b.a)
  - Using the FPGA and ARM together will yield best results

## Topics
* HDL development
* FPGA implementation and debugging
* ARM development and debugging
* Glitching, Fuzzing
* Protocol sniffing
* Extracting firmware and data from embedded devices

## Requirements
A notebook capable of running a VMware image (VMware Player, Workstation or Fusion).
Participants should be familiar with the C programming language.

This course is suitable for people that are unfamiliar with embedded development.
All the theory and concepts behind the electronics, HDL and debugging will be taught during course.

## About the Authors

Please see the [about the authors page](../authors).
