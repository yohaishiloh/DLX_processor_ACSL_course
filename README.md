# Simplified DLX Processor – ACSL Course Project

This repository contains the implementation and documentation of a **simplified DLX processor** developed as part of the **Advanced Computer Structure Lab (ACSL)** course at Tel Aviv University.

---

## 📋 Overview
- **Processor type:** Simplified DLX.  
- **Components implemented:**  
  - Control unit with a **Finite State Machine (FSM)** in Verilog.  
  - **MAC** unit.  
  - Integration of control + datapath at the top level.  
- **Deliverables:** Verilog code, testbench, FPGA bitstream, and detailed project report.

---

## 📂 Repository Contents
- **`control_FSM.v`** – Verilog implementation of the control FSM.  
- **`MAC_STM.v`** – Verilog implementation of the MAC unit.  
- **`DLXcontrol_tb.v`** – a version of a testbench for the control FSM.  
- **`top_level.bit`** – FPGA bitstream file for the full design.  
- **`ACSL Handout 7 PostLab B2 B24.pdf`** – full written report (71 pages) including schematics, explanations, and design details.  
- **`README.md`** – this documentation.

---

## 🎯 Purpose
This project demonstrates the **design and validation of a simplified DLX processor**, focusing on:
- Control FSM design in Verilog.   
- Simulation with testbenches.  
- FPGA synthesis and deployment.  

It forms the foundation for more advanced DLX-based designs, such as multicore and cache-coherent processors.
