Analysis of Speed Control Performance of Slip Ring Induction Motor Using IGBT-Based Slip Power Recovery Drive

Project Overview

This project focuses on the analysis and implementation of a Slip Power Recovery Drive (SPRD) for speed control of a three-phase Slip Ring Induction Motor (SRIM).

The system recovers slip power from the rotor circuit instead of dissipating it as heat through external rotor resistance. The project investigates converter-based speed control and compares conventional SCR-based and IGBT-based slip power recovery schemes using MATLAB/Simulink.

Project Objectives

- Model and simulate an SCR-based slip power recovery drive.
- Develop an IGBT-based PWM slip power recovery model.
- Analyse rotor current distortion and harmonics.
- Compare electromagnetic torque and torque ripple.
- Evaluate power factor and supply-side harmonic performance.
- Study the performance of the drive under sub-synchronous operation.

System Overview

The proposed system consists of the following stages:

1. Rotor Slip Power Extraction
2. AC-to-DC Conversion
3. DC-Link Formation
4. PWM Inverter
5. Digital Control Using Arduino UNO

Simulation and Performance Analysis

Two converter models are studied using MATLAB/Simulink:

- SCR-based slip power recovery scheme.
- IGBT-based active converter scheme.

The simulation results are analysed based on:

- Rotor current waveform.
- Electromagnetic torque response.
- Torque ripple.
- Harmonic distortion.

The active converter model demonstrates smoother rotor current and reduced torque fluctuations compared with the conventional rectifier model.

Hardware Components

- Arduino UNO
- BTN7960 High-Current Half-Bridge Modules
- SN54HC244 Octal Buffer IC
- DC-Link Capacitor Bank
- Power Electronic Converter Circuit

Digital Control

- Sinusoidal Pulse Width Modulation (SPWM)
- Arduino UNO-based PWM generation
- Timer1 Phase Correct PWM mode
- Sinusoidal lookup-table-based duty-cycle generation
- PWM carrier frequency: 5 kHz

Motor Specifications

- Motor Type: Three-Phase Slip Ring Induction Motor
- Rated Voltage: 415 V
- Rated Speed: 1440 RPM
- Number of Poles: 4
- Supply Frequency: 50 Hz
- Operating Range: 70%–100% of synchronous speed

Tools and Technologies

- MATLAB
- Simulink
- Arduino IDE
- Arduino UNO
- Power Electronics
- Slip Power Recovery
- Sinusoidal PWM (SPWM)

Project Outcome

The project studies the performance differences between conventional SCR-based and IGBT-based slip power recovery schemes. Simulation analysis indicates improved rotor current waveform quality and reduced torque ripple with the active converter approach.

Project Documentation

The complete project report is available in this repository.


## Project Documentation

[View Full Project Report](Slip_Ring_Induction_Motor_Report_Without_College_Name.pdf)


