**Total Time Spent: 12.5 hours**

# Recieved, assembled and realised that this project won't work (old devlog, was supposed to be devlogged almost 2 months ago)
Time: 4 hours
Date: September 2nd 2026, Wednesday
I fully assembled the project but ran into an issue where the USB port wouldn't work because my dumb ahh forgot to wire the ATMega32u4's VREF pin to 5v disabling the USB communication lines because the ATMega32u4 thought it was running off battery, hence the project didn't work and it was impossible to program the thing, further more, while trying to bridge the VREF pin to 5v, I shorted 2 pins straight to ground and fried the board. Now, Even though JLCPCB gives you 2 boards I couldn't swap all my components over to the other board because I lifted a pad while trying to swap the USB D+/D- Resistors as I had the wrong resistors on this made the board unusable. 

And even if i had succeeded, I forgot to put down ICSP pin headers so I probably still would not have been able to program the chip

So in total, I ruined both boards because of bad design

heres a picture of the board:
<img width="3472" height="4624" alt="IMG_20260902_182203" src="https://github.com/user-attachments/assets/d4e30204-53b3-4021-9df8-9d5152473b3f" />

# Routed the whole PCB, Finished BOM, Changed Display model.
Time: 4.5 hours
Date: May 24th 2026, Sunday
I completed routing the whole PCB and made the BOM and also made the case as well, When making the BOM I realised that the Adafruit display was too expensive and instead opted for a cheaper still 1.3 inch SPI display of aliexpress. 

Here is a picture of the routed PCB and the case:

<img width="463" height="751" alt="Screenshot 2026-05-24 151544" src="https://github.com/user-attachments/assets/5399dd60-e5de-4816-a278-0361c36fda5e" />
<img width="2122" height="1326" alt="Screenshot 2026-05-25 184526" src="https://github.com/user-attachments/assets/2ada4343-a494-4c7a-9014-97c00443b2f4" />


# Completed the whole Schemetics!
Time: 3 hours
Date: May 24th 2026, Sunday
Today I completed finished the schematics and will now move onto the PCB routing,
I decided to use a AAA battery power source as its widely availible and easy to put!
I also used a standard Adafruit SSD1306 display!

heres a picture of the schematic:
<img width="1146" height="751" alt="Screenshot 2026-05-24 130716" src="https://github.com/user-attachments/assets/5d2009f4-83a6-4b49-9d38-6d64180069de" />

# Added the MPU, Decoupling Capacitors, Display and Buttons!
Time: 1 hour
Date: May 23rd 2026, Saturday
Today I added the MPU and main display to the PCB, Routed all the buttons and added decoupling capacitors as well!

Here are some pictures of the current Schematics:
<img width="814" height="624" alt="image" src="https://github.com/user-attachments/assets/b8949c32-6b03-46ef-9f5d-5384399a802b" />


