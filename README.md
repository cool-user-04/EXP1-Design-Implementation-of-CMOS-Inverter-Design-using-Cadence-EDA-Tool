# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. Schematic of CMOS Inverter:

![WhatsApp Image 2025-03-28 at 14 30 25_532f5140](https://github.com/user-attachments/assets/53fd81a5-3fa2-4d81-bc4a-379e6b0ab29c)


                      
#### 2. Transient Response setup

  ![WhatsApp Image 2025-03-28 at 14 39 05_18ea9aa9](https://github.com/user-attachments/assets/eaff4e67-079a-460d-9d01-697f49e39fdf)
  
#### 3. Voltage Transfer Characteristic (VTC)  Setup:

![WhatsApp Image 2025-03-28 at 14 30 01_71829875](https://github.com/user-attachments/assets/495763c2-d522-46ca-adc3-f53ab8e99fed)



  
## Output
#### 1.Transient Analysis Output

![WhatsApp Image 2025-03-28 at 14 30 32_875b4278](https://github.com/user-attachments/assets/8c89577a-6d52-467f-9230-559adda4d2c7)


 

## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











