
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="527" height="222" alt="image" src="https://github.com/user-attachments/assets/d2248f07-ce55-40c0-8d09-39470fb07e51" />

---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="571" height="122" alt="image" src="https://github.com/user-attachments/assets/6cbd9ecb-c2bc-43bb-8ddb-031a9a7d81f2" />


---

## TABULATION  
**Transmission through Analog Link**

![OCN_EXP41](https://github.com/user-attachments/assets/26d1b988-cb1b-42cc-bc5a-f10543f6d837)


---

## MODEL GRAPH

![OCN_EXP4](https://github.com/user-attachments/assets/77356f28-0a60-4a1f-8e30-786a3e102be4)

---

## RESULT

Thus an 660nm and 950nm fiber analog link and the frequency response of the phototransistor detector has studied and the relationship between the input signal and received signal verified.
