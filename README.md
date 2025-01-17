# SIBOOR-Voron-2.4-AUG  

[1. Assembly Manual 2.4r2](#1-assembly-manual-24r2)  
 
[2. TAP Assembly Tutorial](#2-tap-assembly-tutorial)  

[3. Stealthburner Assembly Tutorial](#3-stealthburner-assembly-tutorial)  
 - [Y-axis limit](#y-axis-limit)  
 - [Display assembly](#display-assembly)

[4. Wiring and Inspection](#4-wiring-and-inspection)  

[5. Nevermore Installation](#5-nevermore-installation)  

[6. Networking and Configuration](#6-networking-and-configuration)  
 - [Connect to WiFi](#connect-to-wifi)
 - [SSH Tools PUTTY](#ssh-tools-putty)

[7. Connect the motherboard and EBB CAN Board](#connect-the-octopus-pro-mainboard)  

 - [Connect the Octopus Pro Mainboard](#connect-the-octopus-pro-mainboard)  

 - [Connect the EBB CAN Board](#connect-the-ebb-can-board)  

[FAQ](#faq)  

## Assembly Guide
### VORON 2.4, designed by VORON DESIGN, represents an enhanced CoreXY design featuring a stable bed and a gantry that moves vertically along the Z-axis. Notably, this design introduces added complexity, incorporating features like 4-point gantry tramming for precise alignment with the print surface, additional stepper motors, and other unique elements. Furthermore, it is crafted to operate within a fully enclosed environment, making it exceptionally proficient in printing ABS or similar filaments.
### Thank you for purchasing the V2.4 [AUG] 3D printer kit from SIBOOR. Due to version differences, please carefully read the following steps. If you encounter any issues or difficulties, please contact us promptly. Wishing you a smooth experience ahead.
### Join our Discord and WeChat groups to receive after-sales support.

 <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/DISCORD.jpg width="1080"/><br/>  

### Please read in the order presented on this page.

### 1. Assembly Manual 2.4r2

- [Assembly_Manual 2.4r2 SIBOOR Annotation Version.pdf](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Manual/Assembly_Manual_2.4r2%EF%BC%88SIBOOR%20Annotation%20Version%EF%BC%89.pdf)  
- Pay close attention to manual comments. After downloading, open the file using a browser or PDF software to view the annotation content!  
- Green-highlighted sections denote variances between SIBOOR V2.4 [AUG] and VORON's official BOM.  
- Red-highlighted sections indicate differences in metal structural components between SIBOOR V2.4 [AUG] and VORON's official BOM.  
  
![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(15).jpg)  

### 2. TAP Assembly Tutorial  

- [Assembly_Manual_Tap.pdf](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Manual/Assembly_Manual_Tap.pdf)  

- Currently, TAP has been upgraded to the RCB version. See the differences in assembly with the old version in the following images.  
  
- **Belt handling:**
  The belts are now handled by looping around Tap_center, and secured with a printed belt cover and M3x8 BHCS:  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(2).jpg)  

- **Extra Stiffening:**
  The 2 M3x50 bolts are threaded up into Tap_Center, and serve to provide extra stiffening:  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(8).jpg)  

- **Vibration Resistance:**
  The heatset inserts for the center are moved back 4 mm to provide extra vibration resistance:  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(4).jpg)  

- **Secure with Screws:**
  So they will need to be secured with M3x12 and M3x16 SHCS (The top is still secured by M3x6 SHCS):  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(6).jpg)  

- After completing the TAP module, go directly to page 132 of the "Assembly_Manual 2.4r2 SIBOOR Annotation Version.pdf.  

### 3. Stealthburner Assembly Tutorial  

- Install the heating rod and thermistor.  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(16).jpg)  

- [Assembly_Manual_Stealthburner.pdf](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Manual/Assembly_Manual_SB%EF%BC%88SIBOOR%20Annotation%20Version%EF%BC%89.pdf)  

- Set up the CAN board, illustrate wiring, and set jumpers.  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(5).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(7).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(1).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(3).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(9).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(18).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(17).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(10).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(11).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(12).jpg)
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/SIBOOR%20V2.4%20AUG%20Wiring%20Schematic_01.jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/SIBOOR%20V2.4%20AUG%20Wiring%20Schematic_02.jpg)

### Install the Y-axis limit switch.  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(21).jpg)  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(20).jpg)  

- Install CAN board cables and steel wires.  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(19).jpg)  

### 4. Wiring and Inspection  

- Versions shipped by December 13, 2023  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/Octopus_Board_Wiring/0928%20SIBOOR%20V2.4%20R2%20AUG%20Wiring%20Diagram.jpg)  

- Versions shipped after December 13, 2023  
  ![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/Octopus_Board_Wiring/1213%20SIBOOR%20V2.4%20R2%20AUG%20Wiring%20Diagram.jpg)

## Version Update Notice: Board Output Adjustment

In this version, a significant upgrade has been implemented by successfully adjusting the board output from `BED_OUT` to `HE1`. This change aims to further optimize system performance.

### Debugging Consideration: Bed Heating Issues

If you encounter difficulties with bed heating during debugging, carefully inspect the `printer.cfg` file for bed configuration. Ensure that the bed heating pin is correctly set to `PA3`. Here is an example of the relevant configuration:

```yaml
[heater_bed]
heater_pin: PA3              # (BE0)
``` 

### The official VORON assembly manual, pages 174-209 are skipped in their entirety, and you are directed to a separate PDF created by SIBOOR.  
  [SIBOOR V2.4 AUG Wiring Schematic.pdf](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/Octopus_Board_Wiring/SIBOOR%20V2.4%20AUG%20Wiring%20Schematic.pdf)) 

### 5. Nevermore Installation  

- [Nevermore V6 Assembly Manual.pdf](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Manual/Nevermore%20V6%EF%BC%88SIBOOR%EF%BC%89.pdf) 

### 6. Networking and Configuration  

### Connect to WiFi
   - Prior to powering on the device, it is absolutely crucial to meticulously verify all electrical connections, ensuring strict adherence to the instructions, with 
   particular emphasis on the correct polarity of the power supply. Neglecting this essential step may lead to irreversible and severe consequences, causing irreparable 
   damage to the electrical equipment. It is imperative to follow these instructions without compromise for the safety and proper functionality of the device.
   - Connect the power cord, turn on the switch, and wait for the display screen to light up.
   - Tap on the "Menu" on the display screen.
   - Click on "Network."
   - Locate your WiFi network and tap the button on the right.
   - Enter the password and click "Save."
   - After returning to the previous level, find the device's IP address in the upper right corner.
  
   ![Network Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/network.jpg)

   After obtaining the IP address of the device, you can enter the control page by typing the IP into the browser using a computer or cell phone in the same LAN. Before officially starting debugging, please continue reading.
    
     
### Log in to SSH
### SSH Tools PUTTY

Putty is a Windows SSH client with a long history. It is available as a free download [here](https://www.putty.org/).

To connect with Putty:

- Open Putty
- Enter your username and hostname in the “hostname” field, in the format `<user>@<host>`, for example, `biqu@BTT-CB1`,
- Certainly. You can also connect to the device directly using the IP address, for example: `pi@192.168.50.87`.  
- Press the “Open” button  

   ![Putty Image 1](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/ssh1.jpg)

- Since this is your first time connecting to this remote machine, you will encounter a security warning. It should be safe to just click accept.  

   ![Putty Image 2](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/ssh2.png)

### Putty Security Alert

- You will then find yourself with a black window and a password prompt. Type your password and press enter. It is normal for nothing to appear on the screen while you are typing the password.
- (Linux applications traditionally hide passwords completely rather than the more familiar dots or stars)  

   ![Putty Image 3](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/ssh3.png)

*Note: Account and password are case-sensitive.*


### Connect the Octopus Pro Mainboard
   - To use the SSH tool to obtain the UUIDs and establish a connection with the OCTOPUS PRO mainboard and EBB 2209 CAN board, make sure to disconnect the cables between the EBB 2209 CAN board and the OCTOPUS PRO mainboard 
   before you begin. This will facilitate the differentiation of the UUIDs for these two boards.
   - Enter the following commands:
     ```bash
     cd ~/CanBoot/scripts
     python3 flash_can.py -i can0 -q
     ```  
   <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/connect1.png width="1080"/><br/>  
   
   - The displayed UUID is the mainboard's UUID. Copy and paste it into the corresponding location in the configuration file (cfg) document.

   <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/connect2.png width="1080"/><br/> 

### Connect the EBB CAN Board  
   - Reinstall the cables that were just removed onto the OCTOPUS PRO mainboard. Next, let's proceed to read the UUID of the EBB 2209 CAN board.
   - Run the following command again:
     ```bash
     python3 flash_can.py -i can0 -q
     ```  
   <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/connect3.png width="1080"/><br/>  
   
   - Obtain the UUID for the EBB CAN bus, copy it, and paste it into the corresponding location in the configuration file (cfg).  
   
   <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/connect4.png width="1080"/><br/> 
   
   - Click Save and restart to complete the device connection.

   <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/connect5.png width="1080"/><br/>

   <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/connect6.png width="1080"/><br/>  

### Congratulations on reaching this point! You've done an excellent job. With the hardware assembly now complete, the next step involves device debugging. This is a phase that requires patience and a bit of learning. We recommend returning to the community for guidance on the upcoming steps.
   - https://docs.vorondesign.com/build/startup/

   -![Image](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/To_add_to_the%20page/supplementary%20page%20%20(22).jpg) 

   
## FAQ

- Where can I find the BOM list for SIBOOR V2.4 [AUG] to verify my package?  
  [Access the BOM list for SIBOOR V2.4 [AUG]](https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/SIBOOR_V2.4_AUG_BOM.md)).

- Is it necessary to burn the system and firmware?  
  The Pi's built-in system is pre-matched with the mainboard and CAN bus. Avoid version upgrades unless issues arise. 

- Why are some metal structural components unused?  
  Certain parts are designed for the Afterburner version and are not applicable here. Remove them before assembly.  

  <br/><img src=https://github.com/Lzhikai/SIBOOR-Voron-2.4-AUG/blob/main/Images/untitled.338.jpg width="1080"/><br/>  

- Why are some screws in different positions from the official instructions?  
  Due to metal processing and weight reduction, some screws differ. See red annotations in Assembly_Manual_2.4r2.

- What are the Klipper account credentials?  
  Username: biqu, Password: biqu (Note: Case-sensitive)

- Why can't my Dragon hotend be installed on the printed part?  
  Remove the cylindrical joint on top of the Dragon hotend before installation. See illustration below.

- Why is there only one drag chain in my kit?  
  SIBOOR V2.4 [AUG] uses a CAN board, eliminating the need for X and Y axis drag chains. Wires will hang inside the chamber, reducing wear and poor contacts.

- Why can't my Z-axis reach the top due to the length limit of the Z-axis drag chain?  
  Removing the X and Y axis drag chains increases visible space, but printing height is still limited. For example, the 300 model can print up to around 280mm, and the 350 model up to around 330mm.

- Why are there no honeycomb skirts and fixed box panels in the kit?  
  If you didn't purchase decorative parts separately, you need to 3D print them.  [Download here](link).

- Why are the motor wires for the X-axis and Y-axis not long enough?  
  This brand of motor has a standard wire length of one meter and requires the use of the red cable and JST terminal extension included in the kit. (X) B motor is recommended to be extended to 2 meters, and Y (A) 
  motor is recommended to be extended to 1.5 meters.

- Why does the hotend lower to 150℃ before raising to the printing temperature during pre-print preparation?  
  This is to prevent damage to the print bed in the event that the hot end heats up to high temperatures.

- Where can I download the system if mine is damaged?  
  [System](https://drive.google.com/file/d/1oGNcbJPUD5zyJWyPYAsPpvsBOQSKj1cR/view?usp=sharing) 

## Links
- VORON Official Website: [https://vorondesign.com/](https://vorondesign.com/)
- Klipper Official: [https://www.klipper3d.org/](https://www.klipper3d.org/)
- BTT Official: [https://github.com/bigtreetech](https://github.com/bigtreetech)
