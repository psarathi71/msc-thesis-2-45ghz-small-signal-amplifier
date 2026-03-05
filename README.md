# MSc Thesis  
## 2.45 GHz Small-Signal RF Amplifier Using Customized Bandpass Filters for Impedance Matching

### Overview
This project presents the design, simulation, fabrication, and measurement of a 2.45 GHz small-signal RF amplifier integrating customized bandpass filters as impedance matching networks. The proposed architecture reduces insertion loss, improves impedance matching, and enables a compact RF front-end implementation.

### Design Architecture
Two cascaded bandpass filters were integrated within the amplifier circuit:

- **Input Filter:** Suppresses out-of-band interference and protects the amplifier from strong unwanted signals.
- **Output Filter:** Refines signal bandwidth and provides optimal impedance matching to subsequent receiver stages.

The filters were designed using direct-coupled theory to precisely control frequency response and impedance transformation.

### Tools & Technologies
- ADS (Circuit simulation & S-parameter analysis)
- PCB Design & Fabrication
- RF Measurement Equipment
- Vector Network Analyzer (VNA)

### Implementation
- Designed in ADS
- PCB fabricated and assembled
- Measured using VNA for S-parameters
## PCB & Fabrication

![PCB Layout](https://github.com/psarathi71/msc-thesis-2-45ghz-small-signal-amplifier/blob/b1e736dbdf4c61f435dbb3eb2ab617214a8d794f/Layout.png)  
*Top-view of the designed PCB layout showing input/output filters and amplifier section.*

![Fabricated PCB](https://github.com/psarathi71/msc-thesis-2-45ghz-small-signal-amplifier/blob/91e8efa245a6be320e75ccca4d515f089d8c1a4c/Fabrication.jpg)  
*Assembled PCB of the 2.45 GHz RF amplifier ready for measurement.*
## Measured S-Parameters

![S-Parameters](https://github.com/psarathi71/msc-thesis-2-45ghz-small-signal-amplifier/blob/04f743a7ac4d93ec2c63036a11377e3b50ba7b0f/S-parameters.png)  
*Measured S11 (reflection) and S21 (gain) of the 2.45 GHz RF amplifier plotted together.*
### Results

| Parameter | Simulated | Measured |
|-----------|-----------|----------|
| Gain      | 13.6 dB   | 11.3 dB  |
| S11       | < -10 dB  | -15.9 dB |

Measured performance remained within acceptable limits for ISM band applications.

### Key Contributions
- Integrated filter-based impedance matching architecture
- Reduced reflection and improved signal integrity
- Validated through physical PCB implementation
- Practical RF measurement and verification

### Applications
- 2.45 GHz ISM Band Systems
- Wireless Receiver Front-End
- Compact RF Modules
- ### Citation
If you use this design or research in your work, please cite it as:
> Partha Sarathi Mazumdar, "2.45 GHz Small-Signal RF Amplifier Using Customized Bandpass Filters for Impedance Matching," MSc Thesis,Tampere University, 2024.
