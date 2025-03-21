# 16-bit ALU in Logisim  

## 🖥️ Overview  
This project is a **16-bit Arithmetic Logic Unit (ALU)** implemented in **Logisim**, based on the design principles from the book *The Elements of Computing Systems (Nand2Tetris)*. The ALU is a crucial component of a CPU, responsible for performing arithmetic and logical operations.  

## ⚙️ Features  

![Screenshot (860)](https://github.com/user-attachments/assets/1d936173-7087-4844-b5c2-b38628a755a7)


- Supports **multiplexed control inputs** to select operations  
- Zero and negative flag outputs for condition checking  
- Designed using **basic logic gates (AND, OR, NOT, XOR, Multiplexers, Adders)**  

## 🛠️ Built With  
- **Logisim** – A digital circuit design and simulation software  
- **Boolean Algebra & Digital Logic** concepts from *The Elements of Computing Systems*  

## 🚀 How to Use  
1. Download **Logisim** from [Logisim Website](http://www.cburch.com/logisim/).  
2. Clone this repository or download the `.circ` file:
   ```bash
   git clone https://github.com/yourusername/16-bit-ALU-Logisim.git
## 🖼️CirCuit Diagram
![Screenshot (858)](https://github.com/user-attachments/assets/f4180a31-53f4-4024-8406-1091208e37d7)
## Explanation of the ALU Logic
1. Zeroing Inputs (zx, zy): Sets x or y to 0000 0000 0000 0000 if required.
2. Negating Inputs (nx, ny): Applies bitwise NOT to x or y if needed.
3. Performing Operation (f): Uses Addition if f == 1, else performs Bitwise AND.
4. Negating Output (no): If no == 1, negates the final output.
5. Computing Flags (zr, ng):
6. zr = 1 if output is 0000 0000 0000 0000 (zero flag).
7. ng = 1 if output is negative (out[15] == 1).
## Circuit User Interface

![Screenshot (859)](https://github.com/user-attachments/assets/d219881b-458e-4dc4-8608-cd61fb5a7616)

## 📖 References
- **The Elements of Computing Systems (Nand2Tetris) by Noam Nisan & Shimon Schocken**
- **Nand2Tetris Course**
