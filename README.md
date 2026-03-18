🧠 Hamming Code (7,4) – RTL Design & Verification
📌 Description

This project implements a Hamming (7,4) error control coding scheme using Verilog HDL, enabling single-bit error detection and correction in digital communication systems.
The design consists of modular RTL blocks for encoding, syndrome-based error detection, and error correction. The encoder generates parity bits using XOR logic, while the decoder computes syndrome bits to identify error positions. A correction mechanism is implemented to flip the erroneous bit and recover the original data.
The functionality is verified using testbenches and simulation waveform analysis.

⚙️ Features

✔ Single-bit error detection
✔ Single-bit error correction
✔ Parity bit generation using XOR logic
✔ Syndrome calculation for error localization
✔ Bit correction using XOR operation
✔ Verified using simulation testbench

🏗️ Design Modules
🔹 Hamming Encoder
Converts 4-bit input data into 7-bit Hamming code
Generates parity bits using combinational XOR logic
🔹 Hamming Decoder
Computes syndrome bits (c1, c2, c3)
Detects presence and position of error
🔹 Error Correction Module
Identifies erroneous bit using syndrome
Corrects single-bit error
Outputs corrected 4-bit data

🧪 Testbench

Separate testbench for each module
Applies multiple input patterns
Includes error injection scenarios

Verifies:

Encoding correctness
Error detection
Error correction

📊 Simulation & Waveform

Simulation performed using:
ModelSim
Cadence Xcelium
Waveforms demonstrate:
Correct encoding process
Syndrome-based error detection
Successful error correction

🛠️ Tools & Technologies

Verilog HDL
ModelSim
Cadence Xcelium
EDA Playground
