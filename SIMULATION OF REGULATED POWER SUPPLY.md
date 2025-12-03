# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
![WhatsApp Image 2025-12-03 at 15 38 48_97b5865d](https://github.com/user-attachments/assets/6778b576-41ba-467d-90cf-5cde6b332526)


## AC INPUT WAVEFORM:
![WhatsApp Image 2025-12-03 at 15 40 04_5e094ed6](https://github.com/user-attachments/assets/a1135a41-575c-47e5-a950-bcbdc951014d)


## OUTPUT GRAPH:
![WhatsApp Image 2025-12-03 at 15 40 49_8402fb23](https://github.com/user-attachments/assets/0b8e0a87-c0ab-45cc-a7fd-2e8460e64330)

## SIGNAL OUTPUT(WITHOUT FILTER)
![WhatsApp Image 2025-12-03 at 15 41 25_e6d801f6](https://github.com/user-attachments/assets/af8aedee-97b5-4eee-9e82-612dec75192b)

## SIGNAL OUTPUT(WITH FILTER)
![WhatsApp Image 2025-12-03 at 15 41 54_f834634e](https://github.com/user-attachments/assets/23f902a5-bd7b-42b7-8892-a2347671ba49)



## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
