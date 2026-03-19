

# VD LED loading

[Preface] My goal is to build some sort of a loading screen LED. So I want each LED to fade out after the one before. When I flip the switch it just restarts again in that cycle.

## Date - 3/19/2026

While working through the introduction, I realized that we learned how to make one LED start to fade already. My next step was to figure out how to attach another LED and make that fade away after the first one. 
![[Pasted image 20260319131341.png]]
I assumed that if I copied the structure once more with another capacitor and resistor it would fade away after, as my Capacitor constant was larger. However that wasn't the case because the LED on the left faded before the one on the right. I was stuck for a while on this trying to figure out why this could happen because if the RC was larger on the left it should take longer to dim. after taking a close look at how the energy, and researching online, I realized that the issue wasn't with the capacitor size but it was with the discharge path. The circuit above has a resistor in parallel with the left capacitor which was draining the energy through two paths. By removing the extra resistor the energy was forced to flow only through the LED, which caused the capacitor to do its job and keep the left LED longer than the right one
[[Pasted image 20260319132158.png]!
![[Pasted image 20260319132158.png]]

I attempted to create a type of circle shape for the LED fading to make it look like a loading circle
-> ![[Pasted image 20260319143711.png]]

but it didn't really work out, because some lights were fading together instead of after one another.
![[Pasted image 20260319141828.png]]

Because this wasn't working out I decided to rearrange/reformat the LEDS to look nicer
![[Pasted image 20260319143059.png]]
When I reformatted the design, it was easier for me to see the flow of energy through the circuit and because in the beginning from how I figured out how to create a delay in the fading, I was able to make the LEDS fade away one by one.

I think the biggest thing I learned from this is that formatting is important. When I tried to format it like a circle, I kept getting confused on how the energy was flowing and I kept running into errors such as some LEDS being more dim than others, and some of the LEDS fading away at the same time. 



### Time Spent: 30 Mins Journaling
### Time Spent: approx 90 minutes working on the design/building the circuit

### Total Time: 2 hours.


https://is.gd/qvNzSK