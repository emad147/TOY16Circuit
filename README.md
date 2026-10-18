# 16-Bit Custom CPU Architecture

## 🧠 System Architecture

*\[]*

This CPU is built using fundamental digital logic components, featuring:

* **Arithmetic Logic Unit (ALU):** Handles core arithmetic (ADD, SUB) and bitwise logic operations.
* **Register File:** \[Specify the number, e.g., 4 or 8] general-purpose 16-bit registers for temporary data storage.
* **Control Unit:** Decodes incoming instructions and coordinates the flow of data across the data path.
* **Memory Integration:** Interfaced with Instruction Memory (ROM) and Data Memory (RAM).

## 🔬 Sub-Circuit Deep Dives

### The ALU (Arithmetic Logic Unit)

*\[Insert the exported PNG of your ALU here]*
Engineered using multiplexers and basic logic gates to compute operations based on opcodes.

### The Register File

*\[Insert the exported PNG of your Register File here]*
Constructed using D-flip-flops and decoders for precise read/write control operations.

## ⚙️ How to Run the Simulation

1. Download and install [Logisim](http://www.cburch.com/logisim/).
2. Clone this repository to your local machine.
3. Open Logisim, navigate to `File > Open`, and select the `.circ` file from this repository.
4. Use the `Poke` tool (the hand icon) to manually toggle the clock pulse and step through instructions.

