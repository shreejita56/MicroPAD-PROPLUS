# MicroPAD-PROPLUS
<img width="487" height="600" alt="Screenshot 2026-10-09 155643" src="https://github.com/user-attachments/assets/0f80bf00-f66a-4303-bbc4-1b731e5a9a8a" />


So I made a custom 3x3 Micropad based on Xiao RP2040 and it has  a rotor encoder on top . We have used diodes to prevent ghosting , the Switches are hot-swappable and it has a compact design.
<br>
The PCB Design was made on Kicad. Here I used the SMD Footprint for the Xiao Rp2040 and Hot-Swappable Footprint for the Switches . The rotor encoder at the top of the matrix also works as a switch . So In total We can use this MicroPad for 9 different Shortcuts and the rotor encoder can be used as a Volume Controller.Also It has per switch LEDS as well <br>

We have also used a Diode with each Switch , So that we can prevent Ghosting. The PCB also have few connection holes which helps it to connect with the CASE Properly.
<br>
I have tried to make the PCB design as compact as I could <br>

Then Comes the CAD . Which was Done in fusion . I Tracked the boundary of the PCB with come relief space then marked the Connection hole on the PCB as well . After which I designed the Bottom Case onto which the PCB Rests and Then I made a 3X3 Center case to hold the Switches and a Top case to add the finish and at the end I made hole for the USB-C connection and made the Base case in a angle so that It sits on a angle on the table.
<br>

Lastly I made the Firmware for the PCB which I wrote completely in C language .

### Features
- 3x3 Switch Design with rotor encoder on top
- Per switch LED and Diode for ghosting
- Compact Design
- Three layered Case with base (Structured at an angle )

  ## User Built Instructions

  So 'first I Soldered the Hot-Swapes onto the board and after that I soldered the diodes onto the other side ,prior to that I Soldered the LEDS and then at the END I soldered the Rotor Encoder and the Xiao Rp2040. After that I assembled the PCB onto the base and then I added the Switch assembles with the Middle layer onto the PCB and at the End I added the top layer CAD and added the KeyCaps. 
  


## Schematics 
<img width="1382" height="551" alt="Screenshot 2026-10-07 182451" src="https://github.com/user-attachments/assets/f6f3b2b8-67b5-4acd-8971-091573b7cb45" />

## PCB 

<img width="847" height="820" alt="Screenshot 2026-10-07 191313" src="https://github.com/user-attachments/assets/f6691c2c-79c6-408b-a002-555928de5e12" />
<img width="850" height="776" alt="Screenshot 2026-10-07 191327" src="https://github.com/user-attachments/assets/66cfb720-bd34-46c5-bc77-bc2f113616fd" />

## 3D Design 
<img width="570" height="505" alt="Screenshot 2026-10-07 192611" src="https://github.com/user-attachments/assets/ea0700a5-42fd-44a4-af9e-c5aaf7474bb3" />
<img width="710" height="615" alt="Screenshot 2026-10-07 193816" src="https://github.com/user-attachments/assets/0d82d09f-8743-40dd-b9eb-f27d74dcc350" />

## Built View 
<img width="487" height="600" alt="Screenshot 2026-10-09 155643" src="https://github.com/user-attachments/assets/90c1da94-e67d-4749-aa88-4ef7016055b0" />
<img width="771" height="611" alt="Screenshot 2026-10-09 155454" src="https://github.com/user-attachments/assets/6653f551-dad9-4575-bdf4-55f79182543e" />

## Demo Link
youtube.com/shorts/5VS75XL_3SE?feature=share
