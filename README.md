<!-- ========================= HEADER ========================= -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&section=header&text=BISHAL&fontSize=70&fontAlignY=38&desc=DIGITAL%20DESIGN%20%7C%20RTL%20%7C%20COMPUTER%20ARCHITECTURE&descAlignY=62&animation=fadeIn&color=000000&fontColor=76B900"/>
</p>

<p align="center">
  <b>/// SYSTEM.ARCHITECT_</b> • Digital Design • RTL • Hardware Acceleration <b>_///</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SystemVerilog-RTL-76B900?style=for-the-badge&logo=siemens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Verilog-HDL-76B900?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ASIC-Design-76B900?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/RISC--V-Architecture-76B900?style=for-the-badge&logo=riscv&logoColor=white"/>
  <img src="https://img.shields.io/badge/AXI4--Lite-Interconnect-76B900?style=for-the-badge&logo=arm&logoColor=white"/>
  <img src="https://img.shields.io/badge/FPGA-RTL-76B900?style=for-the-badge&logo=amd&logoColor=white"/>
</p>

<p align="center">
  <a href="https://github.com/svsBishal">
    <img src="https://img.shields.io/badge/GitHub-Profile-111111?style=for-the-badge&logo=github&logoColor=76B900"/>
  </a>
  <a href="https://www.linkedin.com/in/bishal-sarma-41a9b128a/">
    <img src="https://img.shields.io/badge/LinkedIn-Network-111111?style=for-the-badge&logo=linkedin&logoColor=76B900"/>
  </a>
</p>

<br>

<!-- ========================= INTRO ========================= -->

## `> whoami --profile="hardware_engineer"`

**ROLE**  
Digital Design / RTL Engineer

**FOCUS**  
ASIC Design • RTL • Computer Architecture

**HDL**  
SystemVerilog • Verilog

**LANGUAGES**  
C/C++ • Python

**ARCHITECTURE**  
RISC-V • Pipelining • Caches

**INTERFACES**  
AMBA AHB • APB • AXI/AXI4-Lite • SPI • UART • I2C

**VERIFICATION**  
SystemVerilog • UVM • Reference Models

**AI HARDWARE**  
CNN Accelerators • Systolic Arrays

**FUTURE**  
Cryptographic & Specialized Accelerators

> I build hardware from the RTL level upward — starting from microarchitecture and synthesizable SystemVerilog/Verilog, through verification, processor design, interconnects, and specialized accelerators. My primary interest is designing hardware that is functionally correct and architecturally efficient.

## `> execute ./design_philosophy.sh`

**Specification**  
↓  
**Microarchitecture**  
↓  
**RTL Design**  
↓  
**Verification**  
↓  
**Synthesis**  
↓  
**PPA / Timing / Area**  
↓  
**ASIC**

### `/// CORE COMPETENCIES`

- **Architecture:** Pipelined processor design, datapath & control, parallel architectures
- **Memory:** Memory systems, cache architecture, on-chip communication
- **Logic Design:** RTL microarchitecture, hardware accelerators
- **Verification:** Design verification, reference modeling, FPGA prototyping, ASIC-oriented design

## `> cat current_build_targets.log`

### `[01] RTL Design & Verification`

SystemVerilog • UVM • Assertions • Scoreboards

### `[02] Computer Architecture`

RISC-V • Pipelines • Caches • Memory Systems

### `[03] Hardware Acceleration`

Systolic Arrays • CNN • Tensor Computation

### `[04] SoC / Interconnect Design`

AXI4-Lite • SPI • UART • FIFO

### `[05] Specialized Hardware`

Cryptographic & ML Accelerators

## `> ls -la /projects/hardware`

### `[01] AXI4-Lite → SPI Bridge`

**SystemVerilog | AXI4-Lite | SPI | FIFO | RTL**

A synthesizable AXI4-Lite to SPI bridge that allows an AXI4-Lite master to communicate with SPI peripherals through a memory-mapped interface. The design translates AXI4-Lite read/write transactions into SPI transfers while providing FIFO-based buffering between the AXI and SPI interfaces.

**Architecture**

AXI4-Lite Master  
↓  
AXI4-Lite Interface  
↓  
FIFO Buffer  
↓  
SPI Controller  
↓  
SPI Device

### `[02] RV32I 3-Stage Microprocessor`

**Verilog | RISC-V | Pipeline | Cache | CSR | UART**

A modular 3-stage pipelined RV32I processor implementing a compact CPU architecture with instruction/data caches, CSR support, interrupt and exception handling, and UART-based I/O.

**Pipeline**

Instruction Fetch  
↓  
Decode / Execute  
↓  
Memory / Writeback

### `[03] Output-Stationary Systolic Array CNN Accelerator`

**Verilog | INT8 | CNN | Systolic Array | Hardware Acceleration**

A reconfigurable 16×16 output-stationary systolic-array accelerator for INT8 CNN workloads. The architecture explores spatial computation, local data movement, parallel MAC execution, and efficient reuse of activations and weights.

**Architecture**

Input Activations  
↓  
16×16 MAC Array  
↓  
Output Features

## `> run ./verification_lab.sv`

> Hardware design is only as strong as its verification. My verification work focuses on developing environments that can independently determine whether the DUT behaves according to its specification.

**Verification Flow**

Test  
↓  
Transaction  
↓  
Driver + Reference Model  
↓  
DUT  
↓  
Monitor  
↓  
Scoreboard

**/// VERIFICATION PRIMITIVES**

SystemVerilog Testbenches • UVM Architecture • Virtual Interfaces • Mailboxes • Reference Models • Functional Checking • Clock-Synchronous Verification

## `> echo $TOOLCHAIN`

### HDL

SystemVerilog • Verilog

### Verification

UVM • Assertions • Scoreboards • Reference Models • Functional Coverage

### Software

C • C++ • Python

### Architecture

RISC-V • Pipelined CPUs • Cache Systems • Memory Systems • Parallel Architectures

### Interconnect

AMBA AHB • APB • AXI • AXI4-Lite • SPI • UART • I2C

### Acceleration

CNN Accelerators • MAC Arrays • Systolic Architectures • Tensor Operations • Specialized Datapaths

### Implementation

FPGA Prototyping • RTL Synthesis • Timing Analysis • Area Optimization • Power / Performance / Area

## `> deploy --future ./NeuEM_ASIC`

### `NeuEM — An ASIC Architecture for ML-KEM`

**Post-Quantum Cryptography | Hardware Acceleration | ASIC**

A future hardware architecture focused on accelerating ML-KEM through specialized datapaths and hardware-oriented optimization. The project explores how algorithmic operations in post-quantum cryptography can be mapped efficiently onto dedicated hardware.

**Architecture**

ML-KEM Algorithm  
↓  
Polynomial Operations + Modular Arithmetic  
↓  
Specialized Datapath  
↓  
Control Unit  
↓  
ASIC

## `> cat architecture_interests.txt`

### `[01] DIGITAL LOGIC`

RTL Microarchitecture • Datapath & Control • Finite State Machines • Pipelined Hardware

### `[02] COMPUTER ARCHITECTURE`

RISC-V • Processor Pipelines • Cache Architecture • Memory Hierarchies • Parallel Architectures

### `[03] SOC DESIGN`

AMBA Protocols • AXI / AXI4-Lite • AHB / APB • Peripheral Interfaces • On-Chip Communication

### `[04] HARDWARE ACCELERATION`

MAC Arrays • Systolic Architectures • CNN Acceleration • Tensor Operations • Specialized Datapaths

### `[05] VERIFICATION`

SystemVerilog • UVM • Assertions • Reference Modeling • Scoreboard-Based Checking

### `[06] IMPLEMENTATION`

FPGA Prototyping • RTL Synthesis • Timing • Area • Power / Performance / Area

## `> ./mission_statement`

I design hardware that is:

**Functionally Correct**  
**Architecturally Efficient**  
**Synthesizable**  
**Verifiable**  
**Scalable**

My design flow:

**Algorithm → Microarchitecture → RTL → Verification → ASIC**

<p align="center">
  <b>/// BUILDING HARDWARE FROM THE MICROARCHITECTURE UP. ///</b>
</p>
