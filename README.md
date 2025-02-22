# CMOS Inverter Simulation – PSpice  

## Overview  
This project simulates a CMOS inverter using PSpice, with equal width-to-length (W/L) ratios for both PMOS and NMOS transistors. The simulation analyzes the transient response of the inverter when driven by a square wave input signal.  

## Circuit Design  
- **Technology:** CMOS  
- **Transistor Models:** PMOS and NMOS (MbreakP, MbreakN)  
- **W/L Ratio:** 10µm/10µm for both transistors  
- **Power Supply:** 5V  
- **Input Signal:**  
  - V1 = 5V, V2 = 0V  
  - Rise time (TR) = 1ns  
  - Fall time (TF) = 1ns  
  - Pulse width (PW) = 5ms  
  - Period (PER) = 10ms  

## Simulation Parameters  
- **Analysis Type:** Transient Analysis  
- **Time Step:** 1ns  
- **Total Simulation Time:** 50ms  

## Expected Output  
- When the input is high (5V), the output is low (0V).  
- When the input is low (0V), the output is high (5V).  
- The transient response captures the switching characteristics of the inverter.  

## Results  
The simulation confirms the expected behavior of the CMOS inverter, showing proper voltage transitions and switching delays.  

## Tools Used  
- **Software:** PSpice A/D Lite (Cadence)  
- **Components:** MOSFETs (MbreakP, MbreakN), Voltage Source, Ground  

## How to Run  
1. Open the project in PSpice.  
2. Load the schematic.  
3. Set the transient analysis parameters.  
4. Run the simulation and observe the waveforms.  

## Screenshots  
![Circuit Schematic] ![Screenshot 2025-02-22 134404](https://github.com/user-attachments/assets/d6236e29-41bd-400b-adea-9b872a632100)
  
![Simulation Output] ![Screenshot 2025-02-22 134328](https://github.com/user-attachments/assets/762afd5e-6312-4cd2-be4d-d992348af60c)


## Author  
Naman Sood 

---

This README provides a structured and professional description of your project for GitHub. Let me know if you need modifications! 🚀  
