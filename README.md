# ZooomVGA
An STM32 dev board complete with VGA out

# The Idea

I've been spending a lot of time on software recently and I wanted to do another hardware project. After browsing the Hack CLub slack, I saw there was a zoom call for Blueprint, the hardware program and I decided to join in. The theme was a Trace Race, where you try to make a board in the shortest amount of time. Just an hour before I saw a [VGA library](https://github.com/RoCorbera/BlueVGA) for the exact same STM32 module in the challenge and I knew what my proejct was going to be. The schematic was pretty quick to put together, using a USB C port, an ASM power regulator, the STM32F103C8, a Crystal Oscillator and the VGA port. After getting it reviewed by Kai, and improving it a little bit I moved onto the board in about an hour and a half. The board was a little harder, the VGA port is bigger than the width of a breadboard so I had to flange it out a little. But after aligning everything I started routing the pins. This was a lot harder, I put the MCU off center to get both the USB lines and the crystal to be close to it, but this caused the left side to be very cramped and a pain to route. After 2 hours of painful routing, and another half hour of polish, I finished the entire board in 4 hours. I decided on the name ZooomVGA because this is the fastest I've designed a project, and it was created mainly on the Zoom call.

<img width="980" height="736" alt="image" src="https://github.com/user-attachments/assets/508c62ee-410d-4aad-b886-4eb9091a18f9" />


# The rest of the Owl

I then created a Logo for the board, imporoved the silkscreen, added my logo and exported it to JLCPCB, coming in at around $15 with the stencil and shipping. 
While making the BOM i noticed a slight error with the VGA port, so I changed it to a female connector, did some minor rerouting and fixed the error.

<img width="574" height="820" alt="image" src="https://github.com/user-attachments/assets/3cc51ba4-0c39-4a0a-bd6d-dcabf6d473f7" />

<img width="815" height="453" alt="image" src="https://github.com/user-attachments/assets/502ddeeb-6fa1-4ca1-9ae9-23f37dccfd9b" />
