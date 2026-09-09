# Hi, I'm John Sara 👋

**Computer Engineering Sophomore @ UT Dallas | Economics Minor**  
Focusing on Low-Latency Systems, RTL Design, FPGA Acceleration, and Hardware/Software Co-Design.

[LinkedIn](https://linkedin.com) • [GitHub](https://github.com/john-sara)

---

## 🚀 Key Projects

### ⚡ Hardware-Accelerated HFT Order Matching Engine
**C++20 | SystemVerilog | AXI4-Stream | DPI-C | Verilator | GoogleTest | CMake**
* Architected a single-cycle FPGA matching engine in SystemVerilog processing price-time priority execution at **3.33 ns latency** (@ 300MHz target clock).
* Engineered a lock-free C++ host driver with zero-copy bit packing over an **AXI4-Stream** transport layer, establishing a sub-nanosecond payload baseline (**1.25 ns/order**).
* Built a hardware-in-the-loop co-simulation testbench using **DPI-C**, **Verilator**, and **GoogleTest** to verify cycle-accurate logic, residual inventory state, and stream handshaking.
* 🔗 [View Repository](https://github.com/john-sara/hft-matching-engine)

### 💻 Synthesizable RISC-V (RV32I) Processor Core
**Verilog | RTL Design | AMD Vivado | Behavioral Simulation | Logic Verification**
* Designed and verified a synthesizable single-cycle 32-bit RV32I datapath featuring an integrated ALU and dual-port synchronous register file.
* Developed a continuous 50MHz hardware clock testbench to validate instruction execution and pipeline logic inside AMD Vivado.
* 🔗 [View Repository](https://github.com/john-sara/riscv-rv32i-core)

---

## 💼 Experience

### Hardware Infrastructure Intern | LANWAN Enterprise
*Orange County, CA • June 2025 – August 2026*
* **Systems Architecture:** Deployed and optimized enterprise server hardware infrastructure and managed physical communication bus arrays.
* **Diagnostics & Uptime:** Diagnosed physical hardware failures and tracked system uptime metrics across physical and network layers.
* **Technical Operations:** Communicated operational bottlenecks and system metrics directly to infrastructure management teams.

---

## 🛠️ Technical Skillset

* **Languages:** C++20, SystemVerilog, Verilog, C, Python, SystemC
* **Hardware & Protocols:** AXI4-Stream, DPI-C, PCIe, RISC-V (RV32I), FPGA Synthesis, Digital Logic Design
* **Tools & Simulation:** Verilator, AMD Vivado, GoogleTest, CMake, Git, Linux/WSL, CTest, GTKWave
