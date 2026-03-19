# VD-LED-thing
My goal is to build some sort of a loading screen LED. So I want each LED to fade out after the one before. When I flip the switch it just restarts again in that cycle.

<img width="1036" height="353" alt="image" src="https://github.com/user-attachments/assets/2d265fe0-200c-4d67-8844-8748f885d136" />

<img width="1105" height="387" alt="image" src="https://github.com/user-attachments/assets/625cb49c-2b22-45b6-946a-3c4d3d974d77" />




Link to try: https://is.gd/qvNzSK


Components- 
1 Voltage source
1 Switch
3 Diodes
4 capacitors
1 resistor
7 Wires


What Happens in the circuit
-The Switch controls the power supply to all the LEDS, so when the switch is flipped theres nothing to power the LEDS and vice versa. The capacitors are used to store the energy coming from the voltage source so that when the flip is switched the lights will be able to stay on and fade away as the light drains energy from the capacitors(Each capacitor has a higher value to store more energy, so that the LEDS will stay on longer for each one. This prevents all the LEDS from fading away at once, and gives it that delayed fade effect.) I used the resistor at the very end to ensure that the very last LED would stay lit up the longest because of the RC timing. The wires were used to connect all the sources back to the ground at the voltage source to make sure everything stays connected.

Some things/errors noticed while working.
- While working on the design, in the beginning i noticed how the farther LEDs on the left would die out first and I realised this was because initally I put a resistor for each LED, causing the energy to drain out from two points the LEDS designated capacitor and resistor. By removing the extra resistors and raising the capacitor value, I was able to swap the order making the LEDS fade away in order. 


This actually took longer than expected and I learned a lot while doing this challenge. I hope you like the design- Vaibhav D
