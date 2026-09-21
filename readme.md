# Intelligent PV Array Under Partial Shading

##  Project Overview

This project focuses on modeling and analyzing a photovoltaic (PV) array under partial shading conditions using MATLAB and Simulink. The project investigates the effect of non-uniform irradiance on PV power generation and explores intelligent array reconfiguration to reduce mismatch losses and improve power extraction.

##  Objectives

* Model a 3×3 PV array under different irradiance conditions.
* Analyze PV I–V and P–V characteristics under partial shading.
* Study mismatch losses and multiple power peaks caused by non-uniform irradiance.
* Investigate dynamic PV array reconfiguration using a Genetic Algorithm (GA).
* Develop a switching-based configuration approach for improved power extraction.

##  Tools & Technologies

* MATLAB
* Simulink
* PV system modeling
* Genetic Algorithm
* Photovoltaic array analysis
* Partial shading analysis

##  Current Work

The project currently includes:

* PV panel I–V characteristic modeling
* 3×3 PV array modeling
* Ideal and partial-shading simulations
* Total Cross-Tied (TCT) configuration
* Row-wise bypass diode modeling
* Analysis of I–V and P–V characteristics
* Investigation of mismatch losses and multiple power peaks

The ongoing work focuses on implementing **Genetic Algorithm-based dynamic reconfiguration** and integrating the switching matrix with the PV array model.

## 📊 Simulation

The PV array is tested under both uniform and non-uniform irradiance conditions.

Example partial-shading irradiance pattern:

|           |          |          |
| --------- | -------- | -------- |
| 1000 W/m² | 800 W/m² | 600 W/m² |
| 800 W/m²  | 600 W/m² | 400 W/m² |
| 600 W/m²  | 400 W/m² | 200 W/m² |

The simulations are used to study the reduction in available power and the appearance of multiple peaks in the P–V characteristic.

## Repository Structure

```text
Intelligent-PV-Array-Under-Partial-Shading/
│
├── MATLAB/
│   └── MATLAB scripts and functions
│
├── Simulink/
│   └── Simulink models
│
├── Results/
│   └── Simulation graphs and results
│
└── Documentation/
    └── Project documentation
```

## Future Work

* Complete GA-based dynamic PV array reconfiguration.
* Implement the switching matrix in Simulink.
* Compare conventional and reconfigured PV array performance.
* Evaluate mismatch reduction and power improvement.
* Integrate the control approach with the overall PV system.

## 📊 Project Results

### Simulation Result 1

![Simulation Result 1](/picture1.png)

### Simulation Result 2

![Simulation Result 2](Results/picture2.png)






## Author

**G.Pavithra**
B.Tech Electrical and Electronics Engineering
NSS College of Engineering, Palakkad
