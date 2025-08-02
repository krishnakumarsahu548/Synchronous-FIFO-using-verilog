# Synchronous-FIFO-using-verilog
This project implements a **Synchronous FIFO** memory using Verilog/SystemVerilog. The FIFO is clocked by a single clock signal and uses standard read/write control logic. It is useful in buffering, communication, and data transfer between different blocks in digital systems.


##  Features

- Fixed-depth, configurable-width FIFO
- Synchronous read and write with single clock
- Read and write pointers
- Status flags: `full`, `empty`, `almost_full`, `almost_empty`
- Overflow/underflow protection
- Suitable for FPGA and ASIC-based designs

---

##  Technologies Used

- **Language:** Verilog / SystemVerilog
- **Tools:** Xilinx Vivado / ModelSim / QuestaSim
- **Target FPGA (Optional):** (e.g., Boolean Board / Basys 3)

---

## FIFO Operation

- **Write Operation:** Data is written on rising edge of clock when `write_en` is high and FIFO is not full
- **Read Operation:** Data is read on rising edge of clock when `read_en` is high and FIFO is not empty

---

##  Testbench & Simulation

The included testbench verifies:

- Normal read/write operation
- Full and empty flag behavior
- Overflow and underflow conditions

---

## RTL 
<img width="1920" height="1018" alt="image" src="https://github.com/user-attachments/assets/d09f5ab6-7f50-4d99-a781-a98441c8c9cd" />

## simu
