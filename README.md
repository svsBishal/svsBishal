<!-- ========================= HEADER ========================= -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&section=header&text=BISHAL&fontSize=70&fontAlignY=38&desc=DIGITAL%20DESIGN%20%7C%20RTL%20%7C%20COMPUTER%20ARCHITECTURE&descAlignY=62&animation=fadeIn"/>
</p>

<p align="center">
  <b>Digital Design • RTL • Computer Architecture • Hardware Acceleration</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SystemVerilog-RTL-2E75B6?style=flat-square"/>
  <img src="https://img.shields.io/badge/Verilog-HDL-6A5ACD?style=flat-square"/>
  <img src="https://img.shields.io/badge/ASIC-Design-8A2BE2?style=flat-square"/>
  <img src="https://img.shields.io/badge/RISC--V-Architecture-F39C12?style=flat-square"/>
  <img src="https://img.shields.io/badge/AXI4--Lite-Interconnect-27AE60?style=flat-square"/>
  <img src="https://img.shields.io/badge/FPGA-RTL-2980B9?style=flat-square"/>
</p>

<p align="center">
  <a href="https://github.com/svsBishal">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=flat-square&logo=github"/>
  </a>
  <a href="https://www.linkedin.com/in/bishal-sarma-41a9b128a/">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin"/>
  </a>
</p>


<!-- ========================= INTRO ========================= -->

## `> whoami`

```text
╔══════════════════════════════════════════════════════════════╗
║                       HARDWARE PROFILE                       ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  Role        : Digital Design / RTL Engineer                 ║
║  Focus       : ASIC • RTL • Computer Architecture            ║
║                                                              ║
║  HDL         : SystemVerilog • Verilog                       ║
║  Languages   : C/C++                                         ║
║                                                              ║
║  Architecture: RISC-V • Pipelining • Caches                  ║
║  Interfaces  : AMBA AHB • APB • AXI/AXI4-Lite •              ║
║                        SPI • UART • I2C                      ║
║  Verification: SystemVerilog • UVM • Reference Models        ║
║                                                              ║
║  AI Hardware : CNN Accelerators • Systolic Arrays            ║
║  Future      : Cryptographic & Specialized Accelerators      ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

```
I build hardware from the RTL level upward — starting from microarchitecture and synthesizable SystemVerilog/Verilog, through verification, processor design, interconnects and specialized accelerators.

My primary interest is designing hardware that is not only functionally correct, but also architecturally efficient.

<!-- ========================= DESIGN PHILOSOPHY ========================= -->

## `> design_philosophy`
```text
SPECIFICATION
     │
     ▼
MICROARCHITECTURE
     │
     ▼
RTL DESIGN
     │
     ▼
VERIFICATION
     │
     ▼
SYNTHESIS
     │
     ▼
PPA / TIMING / AREA
     │
     ▼
     ASIC
```
Areas I care about
RTL microarchitecture
Pipelined processors
Datapath and control design
Memory systems and caches
On-chip communication
Hardware accelerators
Parallel architectures
Verification and reference modeling
FPGA prototyping
ASIC-oriented design

<!-- ========================= CURRENT FOCUS ========================= -->
## `> current_focus`

```text
┌────────────────────────────────────────────────────────────┐
│                    CURRENT BUILD TARGETS                   │
├────────────────────────────────────────────────────────────┤
│                                                            │
│  [01] RTL Design & Verification                            │
│       SystemVerilog • UVM • Assertions • Scoreboards       │
│                                                            │
│  [02] Computer Architecture                                │
│       RISC-V • Pipelines • Caches • Memory Systems         │
│                                                            │
│  [03] Hardware Acceleration                                │
│       Systolic Arrays • CNN • Tensor Computation           │
│                                                            │
│  [04] SoC / Interconnect Design                            │
│       AXI4-Lite • SPI • UART • FIFO                        │
│                                                            │
│  [05] Specialized Hardware                                 │
│       Cryptographic & ML Accelerators                      │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

<!-- ========================= PROJECTS ========================= -->
## `> hardware_projects`
```text
01 AXI4-Lite → SPI Bridge

```
SystemVerilog | AXI4-Lite | SPI | FIFO | RTL

A synthesizable AXI4-Lite to SPI bridge that allows an AXI4-Lite master to communicate with SPI peripherals through a memory-mapped interface.

The architecture translates AXI4-Lite read/write transactions into SPI transfers while using FIFO-based buffering between the bus and SPI domains.
``` text
AXI4-Lite MASTER
       │
       ▼
┌──────────────────┐
│ AXI4-Lite SLAVE  │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│   FIFO BUFFER    │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│   SPI CONTROLLER │
└────────┬─────────┘
         │
         ▼
      SPI DEVICE

```
Concepts

<p> <img src="https://img.shields.io/badge/Memory--Mapped%20I%2FO-34495E?style=flat-square"/> 
  <img src="https://img.shields.io/badge/Bus%20Protocols-2980B9?style=flat-square"/> 
  <img src="https://img.shields.io/badge/FIFO-Buffer-27AE60?style=flat-square"/> 
  <img src="https://img.shields.io/badge/FSM-Control-8E44AD?style=flat-square"/> 
  <img src="https://img.shields.io/badge/SPI-RTL-E67E22?style=flat-square"/> 
  <img src="https://img.shields.io/badge/RTL%20Design-2C3E50?style=flat-square"/> </p> <p> 
  <a href="https://github.com/svsBishal/axi4-lite-to-spi-bridge"> 
  <img src="https://img.shields.io/badge/View%20Repository-GitHub-181717?style=for-the-badge&logo=github"/> </a> </p> ```
