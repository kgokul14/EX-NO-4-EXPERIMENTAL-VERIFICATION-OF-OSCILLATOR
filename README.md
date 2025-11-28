# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. #**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR
![WhatsApp Image 2025-11-28 at 14 35 46_a3066e94](https://github.com/user-attachments/assets/8f88b260-22a1-425b-83a5-8244a8f08d7a)




---

## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 14 35 56_6736648a](https://github.com/user-attachments/assets/6b308bba-9cd5-4c9c-b9a2-071ef5256afc)


## DESIGN
![WhatsApp Image 2025-11-28 at 14 36 49_4f6e909b](https://github.com/user-attachments/assets/8987f0e5-b687-48ed-866f-1dad308885b8)

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION


![WhatsApp Image 2025-11-28 at 14 36 08_7a2424fa](https://github.com/user-attachments/assets/649613e9-7bfe-4274-9159-1f12e188b3d3)

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 14 38 21_f35dcc76](https://github.com/user-attachments/assets/1e212b26-94d0-428b-96f7-0ce9c6d0e476)

---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
![WhatsApp Image 2025-11-28 at 14 39 07_cd7e6702](https://github.com/user-attachments/assets/002f574a-ce68-48ac-a1fa-109a1185bdba)



---
## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 14 35 56_182cd4ac](https://github.com/user-attachments/assets/1de428f8-8ad2-4dd5-90eb-997b9b808ee0)

---

## DESIGN
![WhatsApp Image 2025-11-28 at 14 39 36_6816e7f7](https://github.com/user-attachments/assets/c87ade5a-18d3-4f72-b74b-14e9f09185fd)


## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-11-28 at 14 39 22_0cd0da68](https://github.com/user-attachments/assets/5a185ae6-ab63-4e78-a145-a17bed326587)

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 14 40 07_9f367278](https://github.com/user-attachments/assets/5637e706-2f69-4225-8ae4-8b26d056c4dd)

---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
![WhatsApp Image 2025-11-28 at 14 39 51_621d2ea0](https://github.com/user-attachments/assets/b09a4e06-7331-4cb7-959e-c2bfec6a96b0)

