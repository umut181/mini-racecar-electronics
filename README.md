# mini-racecar-electronics
A custom electronics board designed to run a 2WD, IR-controlled differential robot vehicle. 
The industry standard KiCad software kit was used for development.

**Constraints and Specifications**
o Board was built into less than 100mm x 100mm space.
o Fabricated with 2-Layer Rigid FR-4, using Robotistan PCB Service.
o Supports 2S-6S Lipo battery input // (4.5V-40V  Input Voltage Range)
o Compatible to work with all 5V-based microcontrollers.
o Made to power low-reduction 3-6V TT motors with from 150 mA (no load) to 1.5A (stall) range.

## Components & Associated Footprints

C1 = 100 uf 16V
C2 = 220 uf 16V
C3 = 0.47 uf // SMD 0805
C4 = 0.47 uf // SMD  0805
C5 = 0.1 uf // SMD 0805
C6 = 0.1 uf // SMD 0805
C7 =  1 uf  // SMD 1206
C8 = 10 uf // SMD 1206
C9 = 470 uf 16V
C10 =  0.1 uf // SMD 0805
C11 = 0.47 uf // SMD 0805
C12 = 470 uf 16V
C13 = 1 uf  // SMD 1206 
C14 = 0.47 uf // SMD 0805 
C15 = 10 uf // SMD 1206 
C16 = 0.1 uf // SMD 0805

D1 = 5A 100V Schottky Diode
D2 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal  
D3 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal 
D4 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal 
D5 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal 
D6 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal 
D7 = MURS260 // Diode_SMD:D_SMB_Handsoldering
D8 = MURS260 // Diode_SMD:D_SMB_Handsoldering 
D9 = MURS260 // Diode_SMD:D_SMB_Handsoldering 
D10 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal 
D11 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal 
D12 = 1N4148 // Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal  
D13 = MURS260 // Diode_SMD:D_SMB_Handsoldering 

IR_pins1 = CUSTOM 
L1 = 33uh Inductor // Inductor_THT:L_Radial_D7.8mm_P5.00mm_Fastron_07HCP

Q1 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 
Q2 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 
Q3 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 
Q4 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 
Q5 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 
Q6 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 
Q7 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 
Q8 = IRF540N: Package_TO_SOT_THT:TO-220-3_Vertical 

R1 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder 
R2 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder 
R3 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder 
R4 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder  
R5 = 0.1 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder  
R6 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder  
R7 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder 
R8 = 0.1 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder 
R9 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder 
R10 = 10 // Resistor_SMD:R_0805_2012Metric_Pad1.20x1.40mm_HandSolder 

IR2104 (x4) = Package_DIP:DIP-8_W7.62mm

Load1, Load2, Input = TerminalBlock:TerminalBlock_MaiXu_MX126-5.0-02P_1x02_P5.00mm

IR_pins = Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical



