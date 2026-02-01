# Circuit-Breaker

For this project, Ioannis and Daniel collaborated and design a circuit breaker using LTspice and conducted testing on the circuit breaker using simulations and physical testing using a breadboard.

**Creation of circuit breaker:** When creating the circuit breaker the components that were used are an LM358 (Dual Package Op-amp), potentiometer, NPN transistor BC547, resistors, capacitors and an LED. Once the components that are required were determine creating on LTspice was the next step. As the images below show the LTspice circuit:

**Testing simulation:** Once the circuit was created on LTspice the next step was to run simulation testing on the circuit. As the images down below show the different types of testing that had occurred.
LT SPICE SImulation
To verify the inital design's feasability, LT SPICE simulations were run with outputs determining the expected behaviour of each segment. Comparison between the sine input and output confirm the two comparators correctly allow the desired voltage ranges to trigger the BJTs.

<ins> Relay Section: <ins/>
<img width="2559" height="1381" alt="image" src="https://github.com/user-attachments/assets/2c6fd94b-4084-4644-921f-7c26ce1c2846" />

<ins> BJT section: <ins/>
<img width="2559" height="1425" alt="image" src="https://github.com/user-attachments/assets/01631155-4b5e-45f8-ae27-a0c3399f66cb" />


**Testing physical:**
Physical testing confirmed the behaviour matched the expected behaviour from the simulations, as shown using waveforms to verify and probe at specific areas. This confirmed correlated behaviour between the input controlled via an input sine wave as well as the potentionmeter. A simple LED served as a tangible indicator of cutoff.  
<img src="IMG_0836.jpg" width="700" >

<ins> Potentionmeter Lowest: <ins/>
<img width="1689" height="693" alt="Screenshot 2026-02-01 102708" src="https://github.com/user-attachments/assets/f633a8b5-236b-4d05-93d6-516350c6d6ff" />


<ins> Potentionmeter Medium: <ins/>
<img width="1666" height="613" alt="Screenshot 2026-02-01 102822" src="https://github.com/user-attachments/assets/a1560171-4a08-4746-845e-86724d5f02e8" />


<ins> Potentionmeter Highest: <ins/>
<img width="1679" height="728" alt="Screenshot 2026-02-01 103119" src="https://github.com/user-attachments/assets/c27dfc10-89f4-443e-8e84-f19b8c4c4662" />







