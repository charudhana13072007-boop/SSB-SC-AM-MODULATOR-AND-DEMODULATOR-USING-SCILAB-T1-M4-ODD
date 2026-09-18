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

<img width="463" height="1280" alt="WhatsApp Image 2026-09-18 at 11 39 55 PM" src="https://github.com/user-attachments/assets/cbf3876e-8b4b-4819-a96d-e9aa042b9409" />


## Calculation
<img width="720" height="1280" alt="WhatsApp Image 2026-09-18 at 11 40 28 PM" src="https://github.com/user-attachments/assets/330d339d-4ca3-4dc9-bbb5-b1bb526385ed" />
<img width="720" height="1280" alt="WhatsApp Image 2026-09-18 at 11 40 42 PM" src="https://github.com/user-attachments/assets/8e66ca00-c793-4c7f-a442-7fd616b64c21" />

## Output
<img width="1917" height="1020" alt="Screenshot 2026-09-18 234413" src="https://github.com/user-attachments/assets/de9d280c-f72d-49b6-9fd7-1bef404ab528" />


## Result
Successfully performed SSBSC modulation and demodulation using SCI LAB.








