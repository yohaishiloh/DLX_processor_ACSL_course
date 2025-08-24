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
- **`Programming assignment/`** - the final stage of the project to demonstrate its functionallity by performing multiplication between two integers
  - `Programming assignment` - the requirements file given by the lab's stuff
  - `ACSL Programming assignment report` - the submitted report, contains the solution(in assembly language), explanations and demonstrations of the execution 
- **`src/`** – Verilog source files for the processor components:
  - `control_FSM.v` – control unit FSM.
  - `MAC_STM.v` – Multiply–Accumulate unit.
- **`tb/`** – testbenches for simulation:
  - `DLXcontrol_tb.v` – testbench for the control unit.
- **`bitstream/`** – FPGA bitstreams (e.g., `top_level.bit`).
- **`docs/`** – documentation and reports:
  - Full project report (PDF).
  - Poster and slides (if available).
- **`README.md`** – this document.
---

## 🎯 Purpose
This project demonstrates the **design and validation of a simplified DLX processor**, focusing on:
- Control FSM design in Verilog.   
- Simulation with testbenches.  
- FPGA synthesis and deployment.  

It forms the foundation for more advanced DLX-based designs, such as multicore and cache-coherent processors.
