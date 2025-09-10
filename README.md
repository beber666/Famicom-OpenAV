Famicom Open AV

Famicom Open AV is an open-source hardware project that provides custom PCB designs to add composite AV output to the original Nintendo Famicom.<br />
The project is based on the research and documentation from Miko’s Famicom AV-mod guide (archived https://web.archive.org/web/20250321162602/https://miko.mobi/famav.htm ), which explains how to tap into the Famicom’s video and audio signals safely.<br />
<br />
For the moment, it's only compatible wih the Famicom's HVC-CPU-07 board. There is a "manual" hack for the recent boards versions there: https://famicomania.net/famav3.html . Once I will have this type of board, I will do another Gerber file
<br />
Features<br />
	•	Two PCB versions available:<br />
	•	Through-hole version: a retro-style design using classic DIP components, ideal for hobbyists who prefer traditional soldering.<br />
	•	Surface-mount version: a modern design using SMD components, more compact and easier to assemble professionally.<br />
	•	Gerber files included: ready to send to a PCB manufacturer.<br />
	•	Compatibility: currently tested with the HVC-CPU-07 motherboard revision.<br />
Other versions may require adaptation.<br />
<br />
Required Parts (based on Miko’s original guide)<br />
<br />
To build the circuit manually or verify your PCB assembly, you will need:<br />
	•	2 × Female RCA jacks (1 yellow for video, 1 white for audio) Famicom is mono sound. If you want you can solder L and R wires on the audio pin to route the audio on the both speakers<br />
	•	4 × Wires (preferably in 3 different colors)<br />
	•	1 × Transistor: 2SC1815 (or equivalent NPN transistor)<br />
	•	2 × Resistors: 22 kΩ<br />
	•	1 × Electrolytic capacitor: 0.47 µF 50V<br />
<br />
How It Works<br />
<br />
The circuit taps into the Famicom’s motherboard signals (VIDEO, AUDIO, GND, VCC).<br />
	•	The capacitor and transistor are used to condition the video signal.<br />
	•	Resistors ensure proper biasing and signal stability.<br />
	•	Audio is taken directly from the motherboard, then routed to the RCA jack.<br />
	•	The result is a clean composite video and mono audio output that bypasses the RF module.<br />
<br />
Advantages<br />
	•	No drilling or irreversible modifications are required.<br />
	•	Low-risk soldering points, following the tested procedure from Miko’s guide.<br />
	•	Clean composite output, far better than the original RF output.<br />
<br />
Disclaimer<br />
<br />
This is an open-source, community-driven project. Use at your own risk: modifications involve soldering and handling fragile vintage hardware. Neither the author nor contributors are responsible for potential damage to your console.<br />
You can support me and donate there 0x46bA02317f92aFd973d9F80568719CFf30059846  (ETH20) or Cardano on ADA Network addr1vxlw694cy35msf3nu7pjjph6akhjlyuatyh9tu5ua48u9ws7xr62r
