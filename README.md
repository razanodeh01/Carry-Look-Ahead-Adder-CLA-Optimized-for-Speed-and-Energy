# Carry look ahead adder CLA optimized for speed and energy
## 📌 Project Overview
This project presents a 16-bit Carry Look-Ahead Adder (CLA) optimized for speed and energy efficiency. Unlike traditional adders, the CLA minimizes carry propagation delay using a hierarchical approach with Generate (G) and Propagate (P) signals, leading to fast and low-power addition operations.

✅ **Designed using CMOS logic (NMOS & PMOS transistors).**

✅ **Optimized for speed & low power consumption.**

✅ **Built hierarchically using 1-bit, 2-bit, 3-bit, and 4-bit CLA units.**

✅ **Simulated in LTSpice & validated using Verilog testbenches.**



## 🔥 Key Features
1️⃣ High-Speed Carry Computation - Uses parallel carry logic for rapid execution.

2️⃣ Scalability - Composed of 1-bit, 2-bit, 3-bit, 4-bit, and 16-bit CLA units.

3️⃣ Low Power Consumption - Optimized CMOS logic design for minimal energy use.

4️⃣ Simulation Validation - Tested using LTSpice & Verilog testbenches.

5️⃣ Efficient Hardware Implementation - Ideal for modern processors & embedded systems.


## 🧠 Carry Look-Ahead Adder Logic
The Carry Look-Ahead Adder (CLA) improves upon the Ripple Carry Adder (RCA) by precomputing carry signals:

🔹 **Generate (G)**: A carry is generated if both input bits are 1.

🔹 **Propagate (P)**: A carry is propagated if at least one input bit is 1.

Mathematically, the CLA operates as follows:

  🟢 **Carry Equation:**
        𝐶𝑜𝑢𝑡 = 𝐺 + (𝑃 × 𝐶𝑖𝑛)

  🔵 **Sum Equation:**
      𝑆 = 𝐴 ⊕ 𝐵 ⊕ 𝐶𝑖𝑛


## 📊 Performance Metrics

![Image](https://github.com/user-attachments/assets/df7d8d3a-50e5-419e-9bd9-13bc4d16178e)

### Key Observations:
  1. As bit-width increases, power & area scale proportionally.
  2. Delay is significantly reduced compared to Ripple-Carry Adders due to parallel carry computation.
  3. 16-bit CLA optimally balances speed & energy efficiency.

## 👥 Authors:
1. [**Razan Abdalrahman**](https://github.com/razanodeh01)
2. [**Masa Itmaizi**](https://github.com/Masa-Itmazi)
3. [**Katya Kobari**](https://github.com/KatyaKobari)
