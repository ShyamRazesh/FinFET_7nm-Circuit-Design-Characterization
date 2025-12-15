# <h1 id="header-1">📖 Scaling beyond CMOS: FinFET Devices & Innovations</h1> 

# Topics
<div class="toc">
  <ul>
    <li><a href="#header-1">1. Path to Zetta-Scale Computing</a></li>
</div>  

<div class="toc">
  <ul>
    <li><a href="#header-1">2. FinFETS</a></li>
</div>  

<div class="toc">
  <ul>
    <li><a href="#header-1">3. FEOL Innovations</a></li>
</div>  

<div class="toc">
  <ul>
    <li><a href="#header-1">4. BEOL Innovations</a></li>
</div>  


# <h1 id="header-1">1. Path to Zetta-Scale Computing</h1>	 


- This is overview of FinFET. This was first binary computer, and they occupy more room.
- The next generation computing, the problems like precision health in Medison, weather forecasting etc requires enourmus computing power.

<img width="1049" height="565" alt="image" src="https://github.com/user-attachments/assets/60622b48-aa86-4df9-a2dc-5953f822b3b2" />

- This shows exponential league of transistor. Moore's law basically say's that transistor exponentially increases.
- However, the performance of has decreased due power & the heat it releases from it.
- Alot of technology development was done due to mobile development & its vast requirement.

The below fig shows microprocessor system in next 50 years
<img width="968" height="491" alt="image" src="https://github.com/user-attachments/assets/e69215e2-159e-49fc-abdd-627051c4c3e6" />

- The primarily because we are not able to cool the systems down in a very efficient manner. After the release of iPhone, a lot of technology was directed the direction of mobile applications. These devices do not have a very well-designed cooling system.
- So, the power dissipation is less. Hence the frequency is also saturated in the curve.

<img width="900" height="492" alt="image" src="https://github.com/user-attachments/assets/7cb0e229-dd0f-4dfa-bebb-c166d2ee7f1a" />

- The key message here is that you want to use a rack of data center as a socket.
- We went from Giga flop system to Tera over 14 yrs & Tera to Peta over 9 years & so on.
- The goal is to get Zetta flop 7 to 14 years & it has more power required as 14 megawatts.

<img width="1113" height="554" alt="image" src="https://github.com/user-attachments/assets/28d966f5-76d8-418b-8ea7-5009066a1b21" />


The below fig shows changes from Patterning, channel material, interconnection material, Gate stack material, device structure, DTCO & STCO of vast change over the time.

<img width="1078" height="490" alt="image" src="https://github.com/user-attachments/assets/990b0061-0ba2-4254-8e0c-b1aa60389829" />

- Patterning EUV-13.5 nanometer wave
- Channel Material silicon will not help us scale dowm gatelenth less than 10 nm
- Interconnect material damsence process
- Gate stack material
- Device structure we started from planara devices But it could nt give us steep enough on to off switching Finfet – gave us better short channel effects so better on to of switching today – gate all around and nano sheet

# <h1 id="header-1">2. FinFETs</h1>	 

FinFET (Fin Field-Effect Transistor) is a type of 3D transistor used in modern CMOS technology nodes (typically < 22nm). Unlike traditional planar MOSFETs, where the channel lies flat on the substrate, FinFET transistors have a thin, vertical silicon fin that sticks up from the substrate, and the gate wraps around three sides of the fin. By surrounding the channel on multiple sides, the gate gets better electrostatic control over the channel → less leakage, faster switching, and lower power consumption.

<img width="889" height="569" alt="image" src="https://github.com/user-attachments/assets/4649a2af-efaa-48d0-aa53-9b8f9dd5d1aa" />

| Feature    | Planar MOSFET | FinFET (3D MOSFET)  |
| :--------  | :------------ | :---------------------- |		
|Structure	 | Flat channel	 | Vertical fin-shaped channel |
|Gate Control	 | Gate on 1 side	| Gate on 3 sides |
|Leakage Current | High at <32nm	| Very low |
|Performance	 | Limited scaling |	Higher speed, better Ion |
|Power Consumption	| Higher	| Lower |
|Technology Node	| Used ≥ 45nm	| Used ≤ 22nm (Intel, TSMC, Samsung) |
|SCE Resistance	 |Poor	| Excellent |

- FinFETs are industry standard for 22nm, 16nm, 10nm, 7nm, 5nm, and 3nm nodes. At 3nm and below, even FinFET starts struggling. The next-gen solution is Gate-All-Around FET (GAAFET), where the gate completely surrounds the channel.

- Overall, FinFET technology offers a balance of high performance, low power consumption, and robust scalability, which makes it far superior to planar MOSFETs in deep nanometer regimes.

# <h1 id="header-1">3. FEOL Innovations</h1>	 

- Front End of level Innovations through out history of CMOS technology. Because of these innovations sometimes it requies design rule changes & it effects circuit build & layout on chip.
- While moores laws states no.of transistors are integrated, the rate at which tranistor integration increases, moore's law does not scpeifiy the performance of integrated circuit i.e where Dennard scaling era comes up.

<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/b4c94271-f942-44f4-b3e7-ff19d8e835a5" />

- It was 22nm in 2011 FinFET was introduced where was controlled.

<img width="1122" height="579" alt="image" src="https://github.com/user-attachments/assets/3b2c66a1-e518-405c-8158-6de0ca224f75" />

- FEOL Region (Device Level) This is the transistor body and source/drain region.
- Symbol Meaning Description R_FEOL FEOL resistance The total resistance of the active device region (source/drain + channel).
- It includes both intrinsic and extrinsic transistor parts.
- R_EPI Epitaxial layer resistance Resistance due to the epitaxially grown silicon on which the source/drain regions are formed.
- The epi layer helps with doping control and strain.
- R_C Contact resistance The resistance between the metal contact and the semiconductor (source/drain). It depends on silicide quality (NiSi, CoSi₂, etc.) and doping level. 

# <h1 id="header-1">4. BEOL Innovations</h1>	

MOL Region (Contact + Local Interconnect) This section bridges the transistor terminals to the first metal layer.
- Symbol Meaning Description R_MOL MOL total resistance Combination of vertical and lateral resistances from the contact plugs and local interconnect. R_TS Trench silicide resistance Resistance inside the silicided trench or source/drain extension region. It reflects the quality of the silicide and local doping. R_CA-TS Contact-to-trench-silicide resistance Interface resistance between the contact plug (CA) and the underlying silicided region (TS). R_CA Contact area (plug) resistance Resistance of the metal plug itself (tungsten, cobalt, or ruthenium). This is the vertical path in the MOL stack.
- Vertical vs Lateral in MOL: Vertical → from transistor contact upward through the plug. Lateral → short horizontal interconnects that tie neighboring transistors locally before BEOL.

 BEOL Region (Interconnect Stack) This is where global metal routing happens.
- Symbol Meaning Description R_CA-BEOL Resistance between contact and BEOL layer Transition resistance where the MOL contact connects to the first BEOL metal layer (M1).
- R_BEOL BEOL total resistance Resistance of the wiring metals and vias that form the larger interconnect network. It depends on metal type (Cu, Al) and wire geometry. 

FEOL–MOL–BEOL Integration Stage Description Key Materials Purpose FEOL Transistor fabrication Si, SiO₂, HfO₂, metal gate Device formation MOL Contacts + local interconnect W, Co, Ru Bridge device to BEOL BEOL Global metal wiring Cu, Ru, low-k dielectric Signal routing Resistance Components

R_FEOL: Source/drain and channel resistance

R_MOL: Contact and local interconnect resistance

R_BEOL: Metal/via network resistance










