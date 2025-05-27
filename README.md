# RGB-Matrix-PCB
ATmega328P-based RGB LED matrix driver inspired by Cal Poly’s iDesign project. Designed a 2-layer PCB using Altium with shift registers and Darlington transistor array for full RGB control.

## Project Details

**Project Name:** RGB Matrix PCB

**Software Used:** Altium

This project is inspired by the [RGB LED Matrix Controller from Cal Poly iDesign](https://idesign.calpoly.edu/student-projects/rgb-led-matrix-controller)

## ⚙System Architecture

### ATmega328P
- Central controller for display logic  
- Communicates with shift registers via SPI  

### SN74HC595N (x3)
- 8-bit serial-in, parallel-out shift registers  
- Used to control the Red, Green, and Blue channels of each column  


### ULN2803A
- 8-channel Darlington transistor array  
- Drives the common cathodes (rows) of the LED matrix  
- Boosts current from logic-level to suitable drive levels for LEDs  

### Power Supply
- 4x AAA batteries (~6V)  
- Regulated to 5V using 7805 voltage regulator

## Project Files
- `Altium Files` -- Altium files
- `Assembly Files` -- Assembly files
- `BOM` -- Bill of Material
- `Gerber` -- Gerber Files
- `Images` -- Images
- `Layers` -- Layers
- `NC Drill` -- NC Drill
- `STEP` -- STEP file
  

## Images

### Schematic
![RGB LED Schematic](https://github.com/user-attachments/assets/0740f46d-9db9-4f8e-9619-4a2f0f678648)

### PCB Layout
![RGB LED layout](https://github.com/user-attachments/assets/2c7009ba-868a-4963-a3ea-62bf7984103e)

![RGB LED top](https://github.com/user-attachments/assets/327258ca-8b2e-4dd2-b579-2781df0beecb)

![RGB LED bottom](https://github.com/user-attachments/assets/4e162e02-d425-40e6-b2dd-aa97b97c3894)

### 3D
![Board](https://github.com/user-attachments/assets/747abe26-e6c6-4825-b3b6-8a10b78c6ffa)

![top](https://github.com/user-attachments/assets/c6aefc5e-977a-442b-b4c6-0f63d9d4744f)

![bottom](https://github.com/user-attachments/assets/316b67ef-e19b-4007-8380-cf086b0c3231)

