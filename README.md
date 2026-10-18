# 16-Bit Custom CPU Architecture

## 🧠 System Architecture

*\[<img width="2981" height="1461" alt="MainCPU" src="https://github.com/user-attachments/assets/266ab617-6a53-4204-9885-142c758b943b" />
]*

This CPU is built using fundamental digital logic components, featuring:

* **Arithmetic Logic Unit (ALU):** Handles core arithmetic (ADD, SUB) and bitwise logic operations.
* **Register File:** \[Specify the number, e.g., 4 or 8] general-purpose 16-bit registers for temporary data storage.
* **Control Unit:** Decodes incoming instructions and coordinates the flow of data across the data path.
* **Memory Integration:** Interfaced with Instruction Memory (ROM) and Data Memory (RAM).

## 🔬 Sub-Circuit Deep Dives

### The ALU (Arithmetic Logic Unit)

*\[<img width="2099" height="1522" alt="ALU" src="https://github.com/user-attachments/assets/65d83202-4252-48a3-ae22-064cd60192fb" />
]*
Engineered using multiplexers and basic logic gates to compute operations based on opcodes.

### The Register File

*\[<img width="1070" height="708" alt="RegisterFile" src="https://github.com/user-attachments/assets/4eb115a1-8415-41c2-9497-5b61ba9d21f0" />
]*
Constructed using D-flip-flops and decoders for precise read/write control operations.

## ⚙️ How to Run the Simulation
Download and install Logisim.
Clone this repository to your local machine.
Open Logisim, navigate to `File > Open`, and select the `.circ` file from this repository.
Use the `Poke` tool (the hand icon) to manually toggle the clock pulse and step through instructions.

1. Download and install [Logisim](http://www.cburch.com/logisim/).
2. Clone this repository to your local machine.
3. Open Logisim, navigate to `File > Open`, and select the `.circ` file from this repository.
4. Use the `Poke` tool (the hand icon) to manually toggle the clock pulse and step through instructions.

