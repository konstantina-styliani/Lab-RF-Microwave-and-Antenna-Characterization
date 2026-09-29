# Antennas & Microwave Engineering Laboratory

This repository contains two laboratory exercises focused on the experimental characterization of antennas, microwave transmission lines, and microwave components.

The exercises involved hands-on measurements using a **Spectrum Analyzer, Microwave Generator, Oscilloscope, Slotted Line, and Frequency Meter**, with the aim of understanding the practical behavior of antennas, waveguides, and transmission lines.

## **Exercise A — Experimental Characterization of Dipole Antennas**

### **Objective**

Experimental characterization of **λ/2 dipole antennas** using a **Spectrum Analyzer** and a **Microwave Generator**.

The exercise focused on both the **circuit parameters** and **radiation characteristics** of the antennas.

### **Antenna Measurements**

The measurements included:

- **Reflection coefficient**
- **Input impedance**
- **Operating frequency**
- **Operating frequency range**
- **Radiation pattern**
- **Antenna gain**
- **Directivity**
- **Half-Power Beamwidth (HPBW)**

The reflection coefficient was measured using a **frequency sweep**, comparing the reflected signal from the antenna with a reference measurement using a short circuit.

The antenna operating frequency and frequency range were determined from the measured reflection characteristics.

### **Radiation Characteristics**

Two identical **λ/2 dipole antennas** were used to establish a free-space microwave link.

The measurements included:

- **Received and transmitted power**
- **Antenna gain using the Friis transmission equation**
- **Far-field conditions**
- **Half-Power Beamwidth (HPBW)**
- **Radiation pattern**

The receiving antenna was rotated to measure the variation of received power with angle and determine the **HPBW**.

The received power was also measured with the antennas rotated by **90°** to examine the reduction in received signal due to antenna orientation.

## **Exercise B — Slotted Line Measurements**

### **Objective**

Measurement of the main characteristics of a microwave transmission line (**waveguide**) using a **Slotted Line, Oscilloscope, Frequency Meter, and Microwave Generator**.

The measurements included:

- **Operating frequency**
- **Guided wavelength (λ_g)**
- **Standing Wave Ratio (SWR)**
- **Input impedance (Zin)**

### **Frequency and SWR Measurements**

The operating frequency was measured using a **Frequency Meter**, while the **SWR** was determined by measuring the maximum and minimum voltage along the waveguide using the **Slotted Line** and **Oscilloscope**.

Measurements were performed for different load conditions, including a **matched load**, a **non-perfectly matched load**, and an **open waveguide**.

The SWR was also measured at different frequencies, including **8 GHz, 10 GHz, and 12 GHz**, to investigate its variation with frequency.

### **Guided Wavelength Measurement**

The **guided wavelength (λg)** was determined from the distance between consecutive voltage minima along the waveguide.

A **short circuit** was used to locate and record the positions of the minima. The measured guided wavelength was then used to obtain another estimate of the operating frequency.

### **Input Impedance Measurement**

The **input impedance** of microwave loads was determined indirectly from measurements of the **reflection coefficient**, **SWR**, and the position of the voltage minimum.

The measured impedance was used to investigate the behavior of different loads and distinguish between **inductive, capacitive, and resistive** loads.

### **Dielectric Constant Measurement**

The **relative dielectric constant** of two material samples was determined by placing the samples inside a waveguide and measuring the resulting input impedance.

Two configurations were measured:

- **Material sample directly terminated by a short circuit**
- **Material sample followed by a λg/4 section and a short circuit**

The impedance measurements from both configurations were combined to calculate the **relative dielectric constant** of the materials.

A short **MATLAB code** was also developed to calculate the dielectric constant from the measured impedance values.

## **Skills & Equipment**

### **Equipment**

- **Spectrum Analyzer**
- **Microwave Generator**
- **Oscilloscope**
- **Slotted Line**
- **Frequency Meter**
- **Waveguides**
- **λ/2 Dipole Antennas**
- **Microwave Loads**
- **Short Circuit**

### **Topics**

- **Antenna Measurements**
- **RF & Microwave Measurements**
- **Reflection Coefficient**
- **Input Impedance**
- **Operating Frequency**
- **Radiation Patterns**
- **Antenna Gain**
- **Directivity**
- **Half-Power Beamwidth (HPBW)**
- **Friis Transmission Equation**
- **Far-Field Measurements**
- **Transmission Lines**
- **Standing Waves**
- **SWR**
- **Guided Wavelength**
- **Waveguide Measurements**
- **Impedance Measurements**
- **Inductive and Capacitive Loads**
- **Dielectric Constant**
- **MATLAB Data Processing**
