# 7.FREQUENCY-RESPONSE-OF-SERIES-AND-PARALLEL-RESONANCE-CIRCUITS


**AIM:**

To study the behavior of series and parallel RLC circuits at resonance and to determine the resonant frequency, bandwidth, and Q factor  of the given RLC circuit using Multisim Simulator.

**APPARATUS REQUIRED:**

<img width="504" height="276" alt="image" src="https://github.com/user-attachments/assets/2716f700-2960-4ba2-9e8f-7fa1cebda461" />


**THEORY:**

A resonant circuit, also called a **tuned circuit** consists of L and C. Resonant circuits allow us to select a desired signal from the vast number of signals that are around us at any time. A network is in resonance when the voltage and current are in phase and the network's input impedance is purely resistive. Considering the Parallel RLC circuit, the steady-state admittance offered by the circuit is:
Y = 1/R + j(ωC-1/ωL)
Resonance occurs when the voltage and current at the input terminals are in phase. This corresponds to a purely real admittance, so that the necessary condition is given
by ωC-(1/ωL) = 0
The resonant condition may be achieved by adjusting L,C or ω . Keeping L and C constant, the resonant frequency ω0 is given by:
ω0 = 1/√LC
fo = 1/2π√LC
Frequency Response is a plot of output voltage or current of a resonance circuit as function of frequency. The response reaches a maximum value in the vicinity of the natural resonant frequency, and then drops again to zero as f becomes infinite .The 
 
frequency response is shown in figure 2.The two additional frequencies  f 1 and f 2 are also indicated which are called half power frequencies. These frequencies locate those points on the curve at which the voltage response is 1/√2 or 0.707 times the maximum value. They are used to measure the band-width of the response curve. This is called the half – power bandwidth of the resonant circuit and is defined as:  ΒW =f2 - f1

**CIRCUIT DIAGRAM:**


<img width="1600" height="1183" alt="image" src="https://github.com/user-attachments/assets/eb85dfab-d96f-4d2e-ab82-a19c835b9bed" />


**Model graph:**


<img width="1600" height="988" alt="image" src="https://github.com/user-attachments/assets/84c6fe43-b289-4f28-a37b-924306f1f1cc" />


**TABULATION:**
<img width="1600" height="610" alt="image" src="https://github.com/user-attachments/assets/fc69ddba-1722-4811-a7ad-7c72d43e5e03" />


**PROCEDURE:**

1.	Construct Series resonance circuit shown on breadboard.
2.	Connect CRO Ch1 to input and Ch2 to output.
3.	Set the input voltage to 4Vp-p.
4.	Vary the frequency from 500Hz to 3 KHz in small steps to get a maximum output voltage magnitude. The frequency at this maximum voltage Vm is the resonance frequency.
5.	If Vcutoff = Vm/√2, vary the frequency again until the output voltage equals Vcutoff. This frequency is the cut-off frequency. There should be 2 cut-off frequencies on either side of resonant frequency.
6.	Calculate the bandwidth by subtracting the 2 cut-off frequencies.
7.	Calculate the Q factor
8.	Repeat steps 1 through 7 for Parallel resonance circuit  shown.

**Mark split up:**

<img width="824" height="540" alt="image" src="https://github.com/user-attachments/assets/44b71cfa-e3f3-45ef-8de0-47b0cf17bbc7" />

**RESULT:**

Thus the phenomenon of resonance in RLC circuit was studied and the following were determined using Multisim Simulator.










