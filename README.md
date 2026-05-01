555 Timer Square Wave Generator

This project implements an **Astable Multivibrator using the NE555 Timer IC** to generate a stable square wave. It was designed, simulated in **LTspice**, and built on a **PCB**.

Objectives

- **Frequency:** ~650 Hz  
- **Duty Cycle:** ~65%  
- **Tools Used:** LTspice + EasyEDA PCB  

## Circuit Details

The 555 timer operates in **Astable Mode**, continuously switching between HIGH and LOW.

**Components:**
- R1 = 12 kΩ  
- R2 = 6.2 kΩ  
- C2 = 0.1 µF (Timing)  
- C1 = 0.01 µF (Bypass)  
- Vcc = 5V  

## Results

| Parameter   | Theoretical | Simulation | Hardware |
|------------|------------|------------|----------|
| Frequency  | 642 Hz     | 648 Hz     | 555 Hz   |
| Duty Cycle | 65%        | 65%        | 66%      |

**Note:** Hardware variation is due to component tolerances and PCB effects.

##  Project Structure
-/docs → Report
-/simulation → LTspice files
-/pcb → PCB design (EasyEDA)
-/images → Output waveforms & PCB photos

##  Simulation Steps
1. Open `.asc` file in LTspice  
2. Run: .tran 0 10m
3. View output waveform  

##  Team
- Nimisha Thoppil  
- Sagarika Pramod  
- Aishwarya Vaidya  
- Vaibhav Shelar  

**Guide:** Prof. Swati Patil  
Pillai College of Engineering  

## Applications

- Clock signals  
- PWM generation  
- Basic oscillators  
