# Battery Management System (BMS) Simulation

### Project Overview
This project details the development of a Battery Management System (BMS) model in Simulink for a 2-cell lithium-ion battery pack. The primary objective is to ensure safe and efficient operation by accurately monitoring key parameters and responding to faults such as overvoltage, overcurrent, and overheating.

### Key Features
* **SOC & SOH Estimation**: Determines remaining charge and assesses battery health/degradation using current integration and ramp blocks.
* **Real-time Monitoring**: Tracks individual cell and pack voltages, charge/discharge current, and cell temperature.
* **Fault Detection and Protection**: Identifies abnormalities using relational operators and disconnects the battery via switches and logic gates to ensure safety.
* **Cycle Counting**: Automatically counts charge and discharge cycles to predict the battery's lifespan.

### Tech Stack
* **Software**: MATLAB / Simulink.
* **Simulink Components**: Relational operators, Integrators, Gain blocks, Logic gates, Flip-Flops, and Scope.
