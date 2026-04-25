
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**
<img width="960" height="1280" alt="WhatsApp Image 2026-04-25 at 11 42 26 AM" src="https://github.com/user-attachments/assets/43700aeb-e237-4939-a8e8-d9819eb69732" />


---

## Graphs

<img width="722" height="732" alt="image" src="https://github.com/user-attachments/assets/2847679a-dd34-4076-99f9-0a79474117f0" />
<img width="694" height="734" alt="image" src="https://github.com/user-attachments/assets/9a61c5a3-5eb3-4499-a328-670e631de03b" />
<img width="701" height="731" alt="image" src="https://github.com/user-attachments/assets/31d2c8db-3dbe-4077-9e96-f8ec2066f795" />
<img width="711" height="738" alt="image" src="https://github.com/user-attachments/assets/5b0d4769-d6fa-4d79-9992-05db1a538d4b" />
<img width="728" height="737" alt="image" src="https://github.com/user-attachments/assets/288b8593-1471-4bb7-a7f2-3f70f79501e1" />
<img width="728" height="737" alt="image" src="https://github.com/user-attachments/assets/513f2e9d-a5b3-455d-a187-28e16a71fbb9" />

---

## RESULT
The simulation was completed successfully for different fiber lengths (50 km to 150 km).

As the fiber length increases, the received power decreases due to signal loss. The Q factor also decreases, showing poorer signal quality, while the BER increases, indicating more errors.

The eye diagram becomes more closed as the fiber length increases, showing signal distortion.

Thus, the system performance reduces as the fiber length increases.
