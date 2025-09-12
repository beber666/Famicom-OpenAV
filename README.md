# Famicom Open AV

Famicom Open AV is an open-source hardware project that provides custom PCB designs to add composite AV output to the original Nintendo Famicom.  
The project is based on the research and documentation from [Miko’s Famicom AV-mod guide (archived)](https://web.archive.org/web/20250321162602/https://miko.mobi/famav.htm), which explains how to tap into the Famicom’s video and audio signals safely.

For the moment, it's only compatible with the **HVC-CPU-07** board.  
There is a "manual" hack for the more recent board versions [here](https://famicomania.net/famav3.html). Once I have this type of board, I will design another Gerber file.
---

## Sources Files
Sources files are included in the repo. Use https://easyeda.com/ to read them


---


---

## Pictures
<img width="1222" height="1088" alt="PCB" src="https://github.com/user-attachments/assets/de180c95-e2cf-4c1f-9922-96a7f855b452" />
<img width="330" height="272" alt="Schematic_2025-09-10" src="https://github.com/user-attachments/assets/4ce4c8be-71f5-42e2-8a8b-57a3ae6c1ebf" />

![Solder points](https://github.com/user-attachments/assets/a11e1a89-39f7-4dc6-bddb-a17cd2afe74f)

![Easyeda](https://github.com/user-attachments/assets/f8b8df23-ecab-48ad-91e0-c31432ce1a4d)


---

## Features

- **Two PCB versions available:**
  - *Through-hole version*: retro-style design using classic DIP components, ideal for hobbyists who prefer traditional soldering.
  - *Surface-mount version*: modern design using SMD components, more compact and easier to assemble professionally.
- **Gerber files included**: ready to send to a PCB manufacturer.
- **Compatibility**: currently tested with the HVC-CPU-07 motherboard revision. Other versions may require adaptation.

---

## Required Parts (based on Miko’s original guide)

To build the circuit manually or verify your PCB assembly, you will need:

- 2 × Female RCA jacks (1 yellow for video, 1 white for audio).  
  *Note: Famicom is mono sound. If you want stereo, you can solder both L and R wires to the audio pin to route sound to both speakers.*
- 4 × Wires (preferably in 3 different colors)  
- 1 × Transistor: **2SC1815** (or equivalent NPN transistor)  
- 2 × Resistors: **22 kΩ**  
- 1 × Electrolytic capacitor: **0.47 µF 50V**

---

## How It Works

The circuit taps into the Famicom’s motherboard signals (**VIDEO, AUDIO, GND, VCC**):

- The capacitor and transistor condition the video signal.  
- Resistors ensure proper biasing and stability.  
- Audio is taken directly from the motherboard and routed to the RCA jack.  
- Result: a **clean composite video and mono audio output** that bypasses the RF module.

---

## Advantages

- No drilling or irreversible modifications required.  
- Low-risk soldering points, following the tested procedure from Miko’s guide.  
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

## Images

SOON
