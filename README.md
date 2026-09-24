# SSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION
<img width="1600" height="1039" alt="image" src="https://github.com/user-attachments/assets/13b182bc-ec82-491d-9646-3986e613ca54" />



## Calculation
<img width="1600" height="1360" alt="image" src="https://github.com/user-attachments/assets/63d614c4-cfc4-4b90-9f1d-ce3a93380864" />


## Output
<img width="1917" height="1020" alt="Screenshot 2026-09-18 234413" src="https://github.com/user-attachments/assets/de9d280c-f72d-49b6-9fd7-1bef404ab528" />

## mark splitup
<img width="1539" height="792" alt="image" src="https://github.com/user-attachments/assets/428f03f0-3c55-42e4-bc6a-b192a06dd401" />


## Result
<img width="1599" height="621" alt="image" src="https://github.com/user-attachments/assets/532817da-0f22-4812-b2e8-fcb4f9ff2d04" />









