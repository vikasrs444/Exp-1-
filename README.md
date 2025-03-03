Experiment-1
Question : Given that POWER, P=100µ W; Perform DC Analysis, Transient Analysis and AC Analysis for the Given Circuit Designs and also check what happens when the width is increased or decreased of each mosfet;
Design 1:
![image](https://github.com/user-attachments/assets/3370ffee-a466-41ed-898e-84764a94762d)
Using the Formula for Power,

P=V*I

We will get the Values of Id as,

Id= 5.56 * 10^-5 A

we have to get the output current, Id for the given circuits by adjusting the values of L & W( Length and Width of the Channel of the MOSFET)

Length and Width of the Channel used to obtain the given Current is shown in the figure below;

![image](https://github.com/user-attachments/assets/a983d8c8-8874-4c9a-8e6e-dbe5fc4e3eb8)
1) DC ANALYSIS:

Procedure for Performing DC Analysis: we have to select the dc output print(DC op pnt) in the Edit Simulation Command and Run the Simulation
![image](https://github.com/user-attachments/assets/9f3975e8-c887-4a49-b488-57ac6d059476)
The Figure below shows the Values obtained from the DC Analysis :
![image](https://github.com/user-attachments/assets/ed3ae438-a8ba-41e6-9d7b-f538041b223f)
2)Transient Analysis:

Procedure for Performing Transient Analysis: we have to select the Transient Analysis in the Edit Simulation Command, Give the stop time as 1ms and Run the Simulation.

![image](https://github.com/user-attachments/assets/98fa07a2-634a-4f53-8b4e-5aa5302773a7)
The Graphs below shows the Transient Response of the Given Design;
![image](https://github.com/user-attachments/assets/f797d0d3-8cba-491f-a7d1-af61f8b728a0)
![image](https://github.com/user-attachments/assets/7a6efcef-2dac-48d3-9525-249a93bf46a1)
AC Analysis:

Procedure for Performing AC Analysis: we have to select the AC Analysis in the Edit Simulation Command, Give the values as shown in the figure beowl and Run th Simulation.

![image](https://github.com/user-attachments/assets/95e7a142-6590-4082-a4e3-9f703d033433)
RESULT( Design-1):
DC Analysis:

The calculated drain current (Id) matches the expected value based on power and voltage, Id = 5.56*10^-5 A.
By adjusting the MOSFET’s channel dimensions (L & W) where L=180nm and W= 203nm, The current requirement was succesfully achecived.
The circuit behaves as expected under DC conditions.
Transient Analysis:

The transient response graph shows how the circuit behaves over time.
The response is smooth, with no unexpected delays or distortions.
The circuit reacts well to changes, confirming its stability.
The gain obtained is 1.85.
AC Analysis:

The AC response graph confirms that the circuit remains stable at different frequencies.
The gain(2 dB) and phase shift(which is nearly 180deg) align with theoretical expectations.
The circuit maintains its performance across the tested frequency range.
INFERENCE( Design-1):
The experiment confirms that by properly selecting the MOSFET dimensions, we can control the drain current effectively.
Impact of Width Adjustments:
M1 has a influence on Id, meaning its width affects the output current.
The circuit performs well in all three analyses—DC, transient, and AC—demonstrating its reliability.
Overall, the design works as intended, following theoretical predictions and proving its practical feasibility.
Design-2
![image](https://github.com/user-attachments/assets/5c64a156-fa51-413e-9933-73957ca68116)
Using the Formula for Power,

P=V*I/n

We will get the Values of Id as,

Id= 5.56 * 10^-5 A

we have to get the output current, Id for the given circuits by adjusting the values of L & W of both the MOSFETS M1 & M2 ( Length and Width of the Channel of the MOSFET)

DC SWEEP Analysis: This analysis is done for obataing the value of Vin in Saturation range;

we have to select the DC SWEEP in the Edit Simulation Command, Give the values as shown in the figure below and Run th Simulation.
![image](https://github.com/user-attachments/assets/448233e9-e957-4e93-8102-8decbacae747)
The Graph below represents the VTC Curve and the value of the vin is selected as 0.7V as it is present in the saturation region of the VTC Curve
![image](https://github.com/user-attachments/assets/217cc8c9-bc85-46f4-b763-bdd2338c50fa).
Then the input voltage parameters are given as;
![image](https://github.com/user-attachments/assets/31a6655d-bf2a-473d-ad8a-b6767d05bbb7)
Length and Width of the Channel of the two MOSFETS used to obtain the given Current is shown in the figure below;
![image](https://github.com/user-attachments/assets/694f66f4-90e5-4eb6-8275-c8c82dea4dc0)
![image](https://github.com/user-attachments/assets/dadd2ccb-7ef7-4727-a669-adbf4c5c54e5)
Now we will be performing the DC, Transient and AC Anlaysis;

DC ANALYSIS:

Procedure for Performing DC Analysis: we have to select the dc output print(DC op pnt) in the Edit Simulation Command and Run the Simulation

![image](https://github.com/user-attachments/assets/9029a014-5ba8-4b0e-b174-9f69df377f80)
The Figure below shows the Values obtained from the DC Analysis :
![image](https://github.com/user-attachments/assets/497580ea-5b8e-4bee-823a-17c7cb14bb24)
Transient Analysis:

Procedure for Performing Transient Analysis: we have to select the Transient Analysis in the Edit Simulation Command, Give the stop time as 1ms and Run the Simulation.

![image](https://github.com/user-attachments/assets/d32879fc-8766-447f-8f44-e51de2e41c65)
The Graphs below shows the Transient Response of the Given Design;

![image](https://github.com/user-attachments/assets/c9a2c12d-fbb5-41ed-aa4d-d456e182ec65)

![image](https://github.com/user-attachments/assets/f769f588-d03a-47a6-9b59-eaefda66ae73)

AC Analysis:

Procedure for Performing AC Analysis: we have to select the AC Analysis in the Edit Simulation Command, Give the values as shown in the figure beowl and Run th Simulation.

![image](https://github.com/user-attachments/assets/357fa626-26f3-4645-8c59-5aea470d99b5)

The Graph below shows the AC Analysis of the Given Design;

![image](https://github.com/user-attachments/assets/bbe1a3e2-fee9-4eef-bb41-4dea5d61187a)
RESULT(DESIGN-2)
1.DC Analysis:

The calculated drain current (Id) aligns with the expected value based on power and voltage, where the value of Id = 5.56*10^-5 A .
By fine-tuning the channel dimensions (L & W) of both MOSFETs ( M1 & M2), the desired current was achieved,
M1 : L= 180nm , W= 1105nm.
M2 : L= 180nm , W= 1105nm.
The circuit operates correctly within the selected DC parameters.
2.Transient Analysis:

The transient response graph confirms that the circuit transitions smoothly over time.
The circuit responds effectively to input variations, indicating stable operation.
The gain obtained is 2.28.
3.AC Analysis:

The AC response graph confirms that the circuit maintains stability over the tested frequency range.
The gain(5.5 dB) and phase shift (which is nearly 180deg) align with theoretical expectations.
The circuit functions as expected under AC conditions.
Inference (Design-2):
The experiment validates that by appropriately selecting the MOSFET dimensions (L & W), the drain current can be precisely controlled.

The voltage transfer characteristics (VTC) helped in selecting the correct operating voltage (0.7V) for saturation.

Impact of Width Adjustments:

M2 has a stronger influence on Id, meaning its width significantly affects the output current.
M1 has a smaller influence, meaning changes in its width result in only minor variations in Id.
The design meets the expected performance criteria and follows theoretical predictions, demonstrating its feasibility in practical applications















