# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools
NAME : JAYA VISHAL M
212223060102
## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-03-24 122239](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)


## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

   ![WhatsApp Image 2025-04-27 at 06 50 44_d0d8fc6b](https://github.com/user-attachments/assets/261ea585-28ba-4f30-bd51-4042045e6bb5)


![WhatsApp Image 2025-04-27 at 06 50 45_e90911e7](https://github.com/user-attachments/assets/14f243d9-653f-4f96-9942-fff705bbc301)



## Output
#### 1. Transient Analysis Output:

  ![WhatsApp Image 2025-04-27 at 06 50 44_ae71906a](https://github.com/user-attachments/assets/500d8cad-13cb-4032-bc14-fc44b850f70b)
  ![WhatsApp Image 2025-04-27 at 06 50 45_57034d9a](https://github.com/user-attachments/assets/36d4e6ef-6e22-4537-bd08-51c7dc1c474f)




## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


