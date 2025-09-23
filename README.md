# Famicom Open AV MOD

Famicom Open AV is an open-source hardware project that provides custom PCB designs to add composite AV output to the original Nintendo Famicom.  
The project is based on the research and documentation from [Miko’s Famicom AV-mod guide (archived)](https://web.archive.org/web/20250321162602/https://miko.mobi/famav.htm), which explains how to tap into the Famicom’s video and audio signals safely.

Boards Compatibles are: Motherboard HVC-CPU-07 and Motherboard HVC-CPU-GPM-02  

---

## Sources Files
Sources files are included in the repo. Use https://easyeda.com/ to read them


---


---

## Pictures

Motherboard HVC-CPU-07:
<img width="1222" height="1088" alt="PCB" src="https://github.com/user-attachments/assets/de180c95-e2cf-4c1f-9922-96a7f855b452" />
<img width="330" height="272" alt="Schematic_2025-09-10" src="https://github.com/user-attachments/assets/4ce4c8be-71f5-42e2-8a8b-57a3ae6c1ebf" />

![Solder points](https://github.com/user-attachments/assets/a11e1a89-39f7-4dc6-bddb-a17cd2afe74f)

![Easyeda](https://github.com/user-attachments/assets/f8b8df23-ecab-48ad-91e0-c31432ce1a4d)
![EBA709E9-3618-4619-840C-9AB0BED597FA](https://github.com/user-attachments/assets/3bb137f6-1c00-491a-b757-cb2e38130d60)
![D5736E42-56C4-4168-A829-D1B4C7EF8856](https://github.com/user-attachments/assets/16b88c0c-def2-4f55-9e05-f0cd15e21526)
![92E8E763-5859-4164-8901-EBFCD4604465](https://github.com/user-attachments/assets/cf424e0e-2447-4413-81f4-fc00f0e71c48)
![4048EB79-C422-4F37-93AC-4F4874021D53](https://github.com/user-attachments/assets/ff463b0a-6b49-4a55-b39a-20460518b869)
![90C5C1C5-AD85-47DB-96FB-20E9B8BA2977](https://github.com/user-attachments/assets/621fde2d-d500-4213-ad2c-fd41594073a4)
![F4870D2B-16A6-4A92-A535-9D700B99D0C2](https://github.com/user-attachments/assets/1ce9e6d4-0c84-48ac-ac85-013547123145)


Motherboard HVC-CPU-GPM-02
![PCB-3D](https://github.com/user-attachments/assets/93bc5642-9e75-4ab3-897b-beeffadcbc87)
![PCB View](https://github.com/user-attachments/assets/b62fc047-e1e1-4dad-8045-79ceff128847)
![screenshot 2025-09-19 à 09 58 55](https://github.com/user-attachments/assets/355e7210-4fee-42ae-a290-8ee5ca259201)



---

## Features

- **Two PCB versions available:**
  - *Through-hole version*: retro-style design using classic DIP components, ideal for hobbyists who prefer traditional soldering.
  - *Surface-mount version*: modern design using SMD components, more compact and easier to assemble professionally.
- **Gerber files included**: ready to send to a PCB manufacturer.
- **Compatibility**: currently tested with the motherboards models HVC-CPU-07 and  HVC-CPU-GPM-02

---

## Required Parts (based on Miko’s original guide) for Motherboard HVC-CPU-07

To build the circuit manually or verify your PCB assembly, you will need:

- 2 × Female RCA jacks (1 yellow for video, 1 white for audio).  
  *Note: Famicom is mono sound. If you want stereo, you can solder both L and R wires to the audio pin to route sound to both speakers.*
- 4 × Wires (preferably in 3 different colors)  
- 1 × Transistor: **2SC1815** (or equivalent NPN transistor)  
- 2 × Resistors: **22 kΩ**  
- 1 × Electrolytic capacitor: **0.47 µF 50V**

  
## Required Parts for Motherboard HVC-CPU-GPM-02

To build the circuit manually or verify your PCB assembly, you will need:

- 2 or 3 × Female RCA jacks (1 yellow for video, 1 white (and if you want 1 red) for audio).  
  *Note: Famicom is mono sound. If you want stereo, you can solder both L and R wires to the audio pin to route sound to both speakers.*
- Video Capacitor 47µF 16V 
- Audio Capacitor 220µF 16V
- resistor 120 Ω 1/4 W Takman 
- Ceramic Capacitor 1µF
- Wires. You can also use a simple AV cables
---

## Advantages

- No drilling or irreversible modifications required.  
- Low-risk soldering points  
- Clean composite output, far better than the original RF output.  

---

## Disclaimer

This is an **open-source, community-driven project**.  
Use at your own risk: modifications involve soldering and handling fragile vintage hardware. Neither the author nor contributors are responsible for potential damage to your console.

---

## Support

You can support me and donate:  
- **Ethereum (ERC20):** `0x46bA02317f92aFd973d9F80568719CFf30059846`  
- **Cardano (ADA Network):** `addr1vxlw694cy35msf3nu7pjjph6akhjlyuatyh9tu5ua48u9ws7xr62r`  

---

