# 8086 Assembly Workshops

## Overview
This series of workshops explores core programming concepts and techniques in 8086 assembly language. Throughout these exercises, I have developed a deeper understanding of low-level programming, memory manipulation, and algorithm design. The workshops focus on implementing basic and intermediate routines that enhance both logical thinking and knowledge of computer architecture.

## What I Learned

### Control Flow with Loops and Conditions
I learned to create and manage loops using instructions like `loop`, and how to implement conditional checks with comparison (`cmp`) and jump instructions (`je`, `jne`). This allows efficient control over program flow and decision-making.

### Arithmetic Operations and Register Management
Working with 8086 assembly reinforced my ability to perform arithmetic operations using instructions like `add`, `sub`, and `div`. Managing data across different registers (`ax`, `bx`, `cx`, `dx`, etc.) while considering byte- and word-sized values became a crucial skill for handling data effectively.

### Memory Manipulation and Array Processing
I gained experience in working with memory segments and pointers (`ds`, `si`, `bx`). I learned to copy data between segments, manipulate memory addresses, and perform operations on arrays, such as sorting and summing, by incrementing and comparing pointer values.

## How to Run the Programs

To execute these programs on an 8086 simulator or emulator, follow these steps:

### Setup Your Environment
- Install an 8086 emulator like **EMU8086** or **DOSBox** if not running on original hardware.

### Assemble the Code
- Open your emulator or assembler tool and create a new assembly file (`.asm`).
- Copy the desired program code into the file.

### Compile the Program
- Use the assembler’s "Compile" or "Assemble" function to generate the machine code (`.com` or `.exe`).

### Run the Program
- Execute the compiled file in the emulator.
- Monitor the output or register changes directly within the emulator interface.

### Debug and Analyze
- Use debugging tools in your emulator to step through the program. Observe register and memory changes to verify that the program behaves as expected.

## Requirements

- **8086 Emulator:** EMU8086, DOSBox, or any compatible tool.
- **Assembler:** Built-in assembler with the emulator or an external assembler like TASM or MASM.
- **Basic Assembly Knowledge:** Familiarity with instructions, registers, and memory addressing.

## Conclusion
These workshops have provided hands-on experience with 8086 assembly language programming. Through working with loops, conditionals, memory manipulation, and arithmetic operations, I have built a stronger foundation in low-level programming and computer architecture. This knowledge is invaluable in understanding how modern computing systems function at their core.
