# DC–DC Boost Converter Design (12 V → 24 V)

## Project Overview
This project focuses on the design, simulation, and hardware implementation of a **DC–DC boost converter** to step up a 12 V input to a stable 24 V output at 30 W power rating. The system is designed in **Continuous Conduction Mode (CCM)** with low output voltage ripple (≤2%) and robust load regulation.

The project demonstrates **end-to-end power electronics design**, including component sizing, inductor/capacitor selection, MOSFET and diode selection, simulation, and hardware prototyping.


## Features
- Real-time boost converter design for 12 V → 24 V step-up  
- Open-loop simulation of voltage and current waveforms  
- Component selection and sizing (inductor, capacitor, MOSFET, diode)  
- Low output voltage ripple and efficient energy transfer  
- Voltage-controlled implementation (planned)  
- Hardware prototype (planned)  


## Technical Details
- **Input Voltage:** 12 V DC  
- **Output Voltage:** 24 V DC  
- **Power Rating:** 30 W  
- **Operating Mode:** Continuous Conduction Mode (CCM)  
- **Switching Frequency:** 50–100 kHz (lab feasible range)  
- **Key Components:** Inductor, MOSFET, Fast-recovery diode, Output capacitor  

**Key Equations:**
1. Duty Cycle: \( D = 1 - \frac{V_{in}}{V_{out}} \)  
2. Inductor Value: \( L = \frac{V_{in} \cdot D}{\Delta I_L \cdot f_s} \)  
3. Output Capacitor: \( C = \frac{I_{out} \cdot D}{\Delta V_{out} \cdot f_s} \)  


## Progress
- **Completed:** Converter design and open-loop simulation (Deliverables A & B)  
- **Ongoing:** Voltage-controlled implementation and hardware prototyping (Deliverables C & D)  


## Tools and Technologies
- **Simulation:** PLECS 
- **Hardware:** MOSFET, diode, inductor, capacitor 
