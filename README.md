<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b3d2e,45:14532d,100:b87333&height=220&section=header&text=ABISHEK%20GURU&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=RTL%20%2F%20ASIC%20%C2%B7%20Analog%20%26%20PCB%20%C2%B7%20Embedded%20AI&descAlignY=52&descSize=17" width="100%"/>

<a href="https://linkedin.com/in/mabishekguru2006">
  <img src="https://img.shields.io/badge/LinkedIn-mabishekguru2006-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:abishekguruwork@gmail.com">
  <img src="https://img.shields.io/badge/Email-abishekguruwork%40gmail.com-B87333?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/Chennai%2C%20India-VIT%20Vellore-14532d?style=for-the-badge&logo=googlemaps&logoColor=white" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=2600&pause=900&color=D4A24C&center=true&vCenter=true&width=680&lines=probing+RR-intervals+one+spike+at+a+time...;RTL+%E2%86%92+gate-level+%E2%86%92+GDS+%E2%86%92+SKY130A+tapeout;instrumentation+amps+%2B+0.5%E2%80%9350+Hz+bandpass%2C+DRL-shielded;ESP32+firmware+listening+for+arrhythmia" alt="Typing SVG" />

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
| **Chips Taped Out** | 1 × SKY130A (TinyTapeout, event-driven SNN core) |
| **Hackathon Wins** | 6 |
| **Patents Pending** | 1 (vision-based assistive automation) |
| **Operating Domains** | VLSI/RTL · Analog+PCB · Embedded AI |

</div>

<br/>

## 🔧 Top-Level Module

```verilog
// abishek_guru.v — top-level identity module
// target application : biomedical hardware x embedded ML

module abishek_guru #(
    parameter DOMAIN = "VLSI/RTL | ANALOG_PCB | EMBEDDED_AI"
) (
    input  wire         clk_curiosity,
    input  wire         rst_n,             // never actively driven low
    input  wire  [2:0]  focus_sel,         // 000:RTL 001:PCB 010:MCU_FW 011:ML
    output reg   [7:0]  chips_taped_out,
    output reg   [7:0]  hackathons_won,
    output reg           ieee_cas_secretary,
    output reg           patent_pending
);

    initial begin
        chips_taped_out   = 8'd1;   // SNN AFib Detector, SKY130A PDK
        hackathons_won     = 8'd6;
        ieee_cas_secretary = 1'b1;
        patent_pending     = 1'b1;  // vision-based home automation
    end

    // synthesis translate_off
    // fun_fact: also debugged control panels on a Toyota assembly line
    // synthesis translate_on

endmodule
```

<br/>

## 🔩 About This Part

I work across three connected layers of the same stack: **VLSI/ASIC & RTL design**, **analog + PCB hardware** (mostly biosignal front-ends), and **embedded systems / embedded AI**. Almost everything I build lands where **biomedical electronics meets hardware ML** — EEG/ECG acquisition, arrhythmia detection, health monitoring — with side interests in hardware security, neuromorphic computing, and optical fiber comms.

Off the bench: **Secretary, IEEE Circuits and Systems (CAS) @ VIT**, plus industrial-side time on assembly-line maintenance and PLC automation at **Toyota Kirloskar Motor**, and condition-monitoring / industrial IoT at **Schneider Electric**.

<samp>

```
░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░
```

</samp>

## 🧪 Tape-outs & Builds

<table>
<tr>
<td width="50%" valign="top">

### 🧠 SNN AFib Detector
**Spiking Reservoir Computing ASIC**
`Process: SKY130A` `Status: Taped Out — Apr 2026` `Flow: Verilog → gate-level → GDS`

959-cell event-driven ASIC for real-time AFib and asystole detection. 5-stage pipeline: RR feature extraction → spike encoding → 8-neuron LIF reservoir w/ recurrent feedback → dual-window readout. Gate-level tricks (sign-extension, MSB comparators, bit-slicing) trimmed area and hold power in the sub-µW range.

[`→ repo`](https://github.com/AbishekvGuru/SNN_AFib_Detector)

</td>
<td width="50%" valign="top">

### 🫀 Single-Channel EEG Front-End
**Analog Acquisition Board**
`Tools: KiCad · LTspice` `Status: Fabricated — Nov 2025`

Instrumentation-amp + 0.5–50 Hz band-pass front-end with driven-right-leg (DRL) circuitry. LTspice-validated at **14,500 V/V** measured gain (target 15,000 V/V) and **98% rejection** of 50 Hz mains interference via low-noise layout.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 Portable Multi-Sensor Health Monitor
**ESP32 Acquisition + Inference Pipeline**
`Rev: 3 PCB spins` `Status: Deployed — Oct 2025`

ECG (AD8232) + SpO₂/HR (MAX30100) + motion (MPU6050) → Wi-Fi → cloud dashboard. On-signal 1D-CNN over 5,655 PhysioNet ECG traces: **93.8% accuracy / 75% recall** for AFib. Stacked LightGBM+LSTM ensemble for sepsis risk: **0.95 AUC**.

</td>
<td width="50%" valign="top">

### 👁️ Vision-Based Home Automation
**Hands-Free Assistive Controller**
`MCU: ESP32` `Status: Patent Under Review`

Wi-Fi control of lights, fans, alarms and emergency alerts, driven by facial recognition, hand gestures, eye tracking, and ECG monitoring — with a live-streaming cloud dashboard for remote patient monitoring.

</td>
</tr>
</table>

<div align="center">

📄 **Publication** — *"System Analysis of 8-Channel WDM Optical Fiber Link Undergoing Fiber Nonlinearities with Machine Learning-Based BER Prediction"*, 6th ICRTETM 2026

</div>

<samp>

```
░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░
```

</samp>

## 🗂️ Repositories on the Bench

<div align="center">

<a href="https://github.com/AbishekvGuru/SNN_AFib_Detector"><img src="https://img.shields.io/badge/repo-SNN__AFib__Detector-14532d?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://github.com/AbishekvGuru/innovact25"><img src="https://img.shields.io/badge/repo-innovact25-14532d?style=for-the-badge&logo=github&logoColor=white" /></a>
<br/>
<a href="https://github.com/AbishekvGuru/nexus"><img src="https://img.shields.io/badge/repo-nexus-14532d?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://github.com/AbishekvGuru/electrohack"><img src="https://img.shields.io/badge/repo-electrohack-14532d?style=for-the-badge&logo=github&logoColor=white" /></a>
<br/>
<a href="https://github.com/AbishekvGuru/parle-g-samartha"><img src="https://img.shields.io/badge/repo-parle--g--samartha-14532d?style=for-the-badge&logo=github&logoColor=white" /></a>

<sub>(swapped the old repo "pin cards" for plain badges — the pin-card image service kept failing to load)</sub>

</div>

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

🟢 `HDL & Languages` &nbsp;&nbsp; 🟡 `EDA & Bench Tools` &nbsp;&nbsp; 🟠 `Embedded & Hardware` &nbsp;&nbsp; 🔵 `Signal & ML`

<br/><br/>

<img src="https://img.shields.io/badge/Verilog%20HDL-14532d?style=flat-square" />
<img src="https://img.shields.io/badge/Python-14532d?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Embedded%20C-14532d?style=flat-square" />
<img src="https://img.shields.io/badge/MATLAB-14532d?style=flat-square&logo=mathworks&logoColor=white" />
<img src="https://img.shields.io/badge/8051%20Assembly-14532d?style=flat-square" />

<br/>

<img src="https://img.shields.io/badge/Cadence%20Virtuoso-B87333?style=flat-square" />
<img src="https://img.shields.io/badge/Cadence%20AWR-B87333?style=flat-square" />
<img src="https://img.shields.io/badge/KiCad-B87333?style=flat-square&logo=kicad&logoColor=white" />
<img src="https://img.shields.io/badge/LTspice-B87333?style=flat-square" />
<img src="https://img.shields.io/badge/ModelSim-B87333?style=flat-square" />
<img src="https://img.shields.io/badge/Quartus%20Prime-B87333?style=flat-square" />
<img src="https://img.shields.io/badge/NI%20Multisim-B87333?style=flat-square" />
<img src="https://img.shields.io/badge/Keil%20uVision-B87333?style=flat-square" />

<br/>

<img src="https://img.shields.io/badge/ESP32-D97706?style=flat-square&logo=espressif&logoColor=white" />
<img src="https://img.shields.io/badge/Arduino-D97706?style=flat-square&logo=arduino&logoColor=white" />
<img src="https://img.shields.io/badge/UART%20%7C%20SPI%20%7C%20I%C2%B2C-D97706?style=flat-square" />
<img src="https://img.shields.io/badge/Modbus%20RS485%2FTCP-D97706?style=flat-square" />
<img src="https://img.shields.io/badge/Zigbee-D97706?style=flat-square" />
<img src="https://img.shields.io/badge/PLC%20Ladder%20Logic-D97706?style=flat-square" />

<br/>

<img src="https://img.shields.io/badge/1D--CNN-0E7490?style=flat-square" />
<img src="https://img.shields.io/badge/LSTM-0E7490?style=flat-square" />
<img src="https://img.shields.io/badge/LightGBM-0E7490?style=flat-square" />
<img src="https://img.shields.io/badge/Spiking%20Neural%20Networks-0E7490?style=flat-square" />

</div>

<br/>

## 🏅 Calibration Log

<table>
<tr><td>🥇</td><td><b>6× Hackathon Winner</b> — Hack-a-Tron Yantra'24, PCB Showdown Gravitas'24, ElectroHack Yantra'25, Electroutsav Hackathon, Hackulus Gravitas'25, Celestia Gravitas'25</td></tr>
<tr><td>🎓</td><td><b>Secretary, IEEE Circuits and Systems (CAS) @ VIT</b> — ran technical events, mentored members in circuits, embedded systems and PCB design</td></tr>
<tr><td>🛠️</td><td><b>Workshop Lead, "PCB Nexus"</b> — hands-on KiCad workshop for 100+ participants, schematic-to-fabrication</td></tr>
<tr><td>🙋</td><td><b>Student Volunteer</b> — VDAT 2024, ITC India 2025 & 2026</td></tr>
<tr><td>⚙️</td><td><b>Toyota Kirloskar Motor</b> — cut control-panel fault-tracing time <b>70%</b> (20 min → 6 min) via Kaizen / 5-Why standardization</td></tr>
<tr><td>📄</td><td><b>Patent under review</b> — vision-based assistive home automation system</td></tr>
</table>

<samp>

```
░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░░░●░░░░░░░░
```

</samp>

## 📟 Telemetry

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AbishekvGuru&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=D4A24C&icon_color=14532d&text_color=c9d1d9&count_private=true&cache_seconds=1800" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=AbishekvGuru&theme=tokyonight&hide_border=true&background=0d1117&ring=D4A24C&fire=B87333&currStreakLabel=D4A24C" height="165"/>

<sub>These two cards are drawn live by a free, shared community service — if one shows as broken, it's almost always that service being briefly overloaded, not this file. It usually fixes itself within a day; re-opening the raw image URL in a browser forces a refresh sooner.</sub>

</div>

<br/>

<div align="center">

## 📡 Uplink

[![LinkedIn](https://img.shields.io/badge/-Abishek%20Guru-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mabishekguru2006)
[![Gmail](https://img.shields.io/badge/-abishekguruwork@gmail.com-B87333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abishekguruwork@gmail.com)

<samp>// end of transmission — probe responding on all channels</samp>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:b87333,55:14532d,100:0b3d2e&height=100&section=footer" width="100%"/>

</div>
