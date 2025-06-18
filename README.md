# ARM_Tech_Assessment_Thermal_Modelling_Engineer

This repository contains the technical assessment completed as part of the recruitment process for the Thermal Modelling Engineer position at ARM.

## Content:

- `Etienne_Poueyo_Tech_Assessment_Thermal_Modelling_Engineer_arm.pdf` : Complete technical assessment in PDF format,
- `Etienne_Poueyo_Tech_Assessment_Thermal_Modelling_Engineer_arm.ipynb` : Complete technical assessment in notebook format.

## Description:

The assessment includes:

1. **Objective**:  
   Simulate and analyse the thermal response of a CPU using a simplified RC thermal network, under two operational scenarios:
   - **Free-running mode**: constant nominal voltage/frequency.
   - **DVFS-controlled mode**: dynamic voltage and frequency scaling based on temperature threshold (85°C).

2. **Key elements covered**:
   - Dynamic and leakage power modelling.
   - Node-based thermal transient equations.
   - Simple binary DVFS controller.
   - Simulation of temperature evolution over time.
   - Visualisation of CPU temperature, DVFS activity, thermal balance.
   - Optional thermal design space analysis (steady-state map).

3. **Requirements**:
   - Python (3.11.9)
   - NumPy
   - Matplotlib

4. **Installation**:
   ```bash
   pip install -r requirements.txt
