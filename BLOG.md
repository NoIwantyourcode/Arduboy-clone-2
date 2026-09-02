<img width="3472" height="4624" alt="IMG_20260902_182203" src="https://github.com/user-attachments/assets/b2678e44-a9e9-4bda-b5ae-c94dd3e9ec26" /># Blog

# What went wrong?
I fully assembled the project but ran into an issue where the USB port wouldn't work because my dumb ahh forgot to wire the ATMega32u4's VREF pin to 5v disabling the USB communication lines because the ATMega32u4 thought it was running off battery, hence the project didn't work and it was impossible to program the thing, further more, while trying to bridge the VREF pin to 5v, I shorted 2 pins straight to ground and fried the board. Now, Even though JLCPCB gives you 2 boards I couldn't swap all my components over to the other board because I lifted a pad while trying to swap the USB D+/D- Resistors as I had the wrong resistors on this made the board unusable.

# What can I do to prevent it from happening again?
DON'T RUSH PROJECTS, READ DATASHEETS CAREFULLY AND PLEASE DO YOUR RESEARCH BEFORE DESIGNING THE PROJECT

# Current picture of the Arduboy:
<img width="3472" height="4624" alt="IMG_20260902_182203" src="https://github.com/user-attachments/assets/9f6a1dc1-c17f-44d6-91c5-e6212d73d170" />
