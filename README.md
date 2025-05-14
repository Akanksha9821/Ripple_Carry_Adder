
# 🧮 4-Bit Ripple Carry Adder

A simple digital design project that implements a **4-bit Ripple Carry Adder** using Verilog. This adder is built using a series of full adders where each carry output is passed to the next stage, forming a "ripple" effect.

---

## 📘 What is a Ripple Carry Adder?

A **Ripple Carry Adder (RCA)** is a basic type of binary adder used in digital electronics to perform binary addition. It connects several **full adder** circuits in series to add multi-bit binary numbers. Each full adder processes one bit and passes the carry to the next stage.

### 🔧 Key Features

- Adds two 4-bit binary numbers and an optional carry-in.
- Outputs a 4-bit sum and a carry-out.
- Built with 4 full adders in series.

---

## 🔁 How It Works

Each full adder adds two input bits (`A` and `B`) and a carry-in (`Cin`). It outputs a sum and a carry-out (`Cout`). The carry-out of each stage becomes the carry-in of the next.

