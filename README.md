<div align="center">

<img src="https://raw.githubusercontent.com/AbishekvGuru/AbishekvGuru/main/assets/circuit-banner.svg" width="100%" alt="Abishek Guru — Electronics Engineer"/>

<a href="https://linkedin.com/in/mabishekguru2006">
  <img src="https://img.shields.io/badge/LinkedIn-mabishekguru2006-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:abishekguruwork@gmail.com">
  <img src="https://img.shields.io/badge/Email-abishekguruwork%40gmail.com-0369a1?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/Chennai%2C%20India-VIT%20Vellore-0c4a6e?style=for-the-badge&logo=googlemaps&logoColor=white" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=2600&pause=900&color=7DD3FC&center=true&vCenter=true&width=680&lines=compiling+RTL%2C+one+clock+domain+at+a+time...;routing+traces+where+signal+integrity+matters;VLSI+%2F+RTL+%C2%B7+Analog+%26+PCB+%C2%B7+Embedded+Systems;IEEE+CAS+Secretary+%40+VIT" alt="Typing SVG" />

</div>

<samp>

```
░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░
```

</samp>

## 🧾 Spec Sheet

<div align="center">

| Parameter | Rating |
|:--|:--|
| **Part Number** | AG-2027-ECE |
| **Package / Institution** | B.Tech Electronics & Comms, VIT Vellore (Class of 2027) |
| **Grade Point (typ.)** | 9.14 / 10 |
| **Governance** | Secretary, IEEE Circuits & Systems (CAS) — VIT |
| **ASIC Tape-out** | Selected — SKY130A, TinyTapeout program |
| **Hackathon Wins** | 6 |
| **Patents Pending** | 1 |
| **Operating Domains** | VLSI/RTL · Analog & PCB · Embedded Systems |

</div>

<br/>

## 🔧 Top-Level Module

```verilog
// abishek_guru.v — top-level identity module
// target application : general-purpose electronics engineering

module abishek_guru #(
    parameter DOMAIN = "VLSI/RTL | ANALOG_PCB | EMBEDDED_SYSTEMS"
) (
    input  wire         clk_curiosity,
    input  wire         rst_n,                  // never actively driven low
    input  wire  [2:0]  focus_sel,               // 000:RTL 001:PCB 010:MCU_FW 011:ML
    output reg   [7:0]  hackathons_won,
    output reg           ieee_cas_secretary,
    output reg           asic_tapeout_selected,
    output reg           patent_pending
);

    initial begin
        hackathons_won        = 8'd6;
        ieee_cas_secretary    = 1'b1;
        asic_tapeout_selected = 1'b1;   // SKY130A, TinyTapeout — tapeout pending
        patent_pending        = 1'b1;
    end

endmodule
```

<br/>

## 🔩 About This Part

I'm an Electronics & Communication Engineering student at **VIT Vellore** (CGPA 9.14/10, Class of 2027), working across **VLSI/ASIC & RTL design**, **analog + PCB hardware**, and **embedded systems**. I care about the layer where a signal actually becomes a working circuit — gate-level logic and tapeout flows on one side, instrumentation-grade analog front-ends and firmware talking to real sensors on the other. Side interests: hardware security, neuromorphic computing, and optical fiber communications.

Off the bench, I'm **Secretary of IEEE Circuits and Systems (CAS) at VIT**, running technical events and mentoring members in circuits, embedded systems and PCB design. I've also picked up industrial-side experience — assembly-line maintenance and PLC-based automation at **Toyota Kirloskar Motor**, and industrial IoT / condition monitoring at **Schneider Electric**.

<samp>

```
░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░
```

</samp>

## 🔌 Pin Configuration

```
                     ┌─────────────────────────┐
        VDD_HDL   ●──┤                         ├──●   GPIO_EMBED
        CLK_EDA   ●──┤        ABISHEK_GURU     ├──●   SIG_ML
             GND   ●──┤          (DIP-8)        ├──●   NC
                     └─────────────────────────┘
```

<div align="center">

**HDL & Languages**
<br/>
<img src="https://img.shields.io/badge/Verilog%20HDL-0c4a6e?style=flat-square" />
<img src="https://img.shields.io/badge/Python-0c4a6e?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Embedded%20C-0c4a6e?style=flat-square" />
<img src="https://img.shields.io/badge/MATLAB-0c4a6e?style=flat-square&logo=mathworks&logoColor=white" />
<img src="https://img.shields.io/badge/8051%20Assembly-0c4a6e?style=flat-square" />

<br/>

**EDA & Bench Tools**
<br/>
<img src="https://img.shields.io/badge/Cadence%20Virtuoso-075985?style=flat-square" />
<img src="https://img.shields.io/badge/Cadence%20AWR-075985?style=flat-square" />
<img src="https://img.shields.io/badge/KiCad-075985?style=flat-square&logo=kicad&logoColor=white" />
<img src="https://img.shields.io/badge/LTspice-075985?style=flat-square" />
<img src="https://img.shields.io/badge/ModelSim-075985?style=flat-square" />
<img src="https://img.shields.io/badge/Quartus%20Prime-075985?style=flat-square" />
<img src="https://img.shields.io/badge/NI%20Multisim-075985?style=flat-square" />
<img src="https://img.shields.io/badge/Keil%20uVision-075985?style=flat-square" />

<br/>

**Embedded & Hardware**
<br/>
<img src="https://img.shields.io/badge/ESP32-0369a1?style=flat-square&logo=espressif&logoColor=white" />
<img src="https://img.shields.io/badge/Arduino-0369a1?style=flat-square&logo=arduino&logoColor=white" />
<img src="https://img.shields.io/badge/UART%20%7C%20SPI%20%7C%20I%C2%B2C-0369a1?style=flat-square" />
<img src="https://img.shields.io/badge/Modbus%20RS485%2FTCP-0369a1?style=flat-square" />
<img src="https://img.shields.io/badge/Zigbee-0369a1?style=flat-square" />
<img src="https://img.shields.io/badge/PLC%20Ladder%20Logic-0369a1?style=flat-square" />

<br/>

**Signal & ML**
<br/>
<img src="https://img.shields.io/badge/1D--CNN-0284c7?style=flat-square" />
<img src="https://img.shields.io/badge/LSTM-0284c7?style=flat-square" />
<img src="https://img.shields.io/badge/LightGBM-0284c7?style=flat-square" />
<img src="https://img.shields.io/badge/Spiking%20Neural%20Networks-0284c7?style=flat-square" />

</div>

<br/>

## 🏅 Calibration Log

<table>
<tr><td>🥇</td><td><b>6× Hackathon Winner</b> — Hack-a-Tron Yantra'24, PCB Showdown Gravitas'24, ElectroHack Yantra'25, Electroutsav Hackathon, Hackulus Gravitas'25, Celestia Gravitas'25</td></tr>
<tr><td>🎓</td><td><b>Secretary, IEEE Circuits and Systems (CAS) @ VIT</b> — ran technical events, mentored members in circuits, embedded systems and PCB design</td></tr>
<tr><td>🛠️</td><td><b>Workshop Lead, "PCB Nexus"</b> — hands-on KiCad workshop for 100+ participants, schematic-to-fabrication</td></tr>
<tr><td>🙋</td><td><b>Student Volunteer</b> — VDAT 2024, ITC India 2025 & 2026</td></tr>
<tr><td>⚙️</td><td><b>Toyota Kirloskar Motor</b> — cut control-panel fault-tracing time <b>70%</b> (20 min → 6 min) via Kaizen / 5-Why standardization</td></tr>
<tr><td>🔬</td><td><b>ASIC design selected for tape-out</b> — SKY130A, TinyTapeout program</td></tr>
<tr><td>📄</td><td><b>Patent</b> — currently under review</td></tr>
</table>

<div align="center">

📰 **Publication** — *"System Analysis of 8-Channel WDM Optical Fiber Link Undergoing Fiber Nonlinearities with Machine Learning-Based BER Prediction"*, 6th ICRTETM 2026

</div>

<samp>

```
░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░
```

</samp>

## 📟 Telemetry

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=AbishekvGuru&theme=tokyonight&hide_border=true&background=0d1117&ring=7DD3FC&fire=67E8F9&currStreakLabel=7DD3FC" height="165"/>

<sub>Dropped the contribution-graph and language cards from this section — they're served by a free, shared community host that's been failing to load intermittently. This streak card comes from a more stable instance; I'd rather show one thing reliably than three things that half-load.</sub>

</div>

<br/>

<div align="center">

## 📡 Uplink

[![LinkedIn](https://img.shields.io/badge/-Abishek%20Guru-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mabishekguru2006)
[![Gmail](https://img.shields.io/badge/-abishekguruwork@gmail.com-0369a1?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abishekguruwork@gmail.com)

<samp>// end of transmission — probe responding on all channels</samp>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1420,55:0c4a6e,100:0a0e17&height=100&section=footer" width="100%"/>

</div>
