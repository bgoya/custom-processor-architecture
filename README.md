# Extending a Custom Processor Architecture in Logisim

Project focused on assembly programming and low-level computer architecture using a custom processor simulated in Logisim.

The work explores processor internals through assembly development, stack manipulation, instruction analysis and ISA extension by implementing new microinstructions directly into the processor architecture.



## Overview

This project was developed as part of a Computer Systems course centered around processor architecture and low-level execution models.

Using the OrgaSmall architecture in Logisim, the project involved:
- writing and analyzing assembly programs,
- understanding instruction execution at the microinstruction level,
- extending the processor instruction set,
- and modifying the assembler and control memory to support new operations.

The project combines practical assembly programming with architecture-level modifications and processor simulation.



## Features

- Assembly programming on a custom architecture
- Stack manipulation and control flow handling
- Processor microinstruction analysis
- Custom ISA extension
- Modified assembler support
- Control memory integration
- Logisim-based processor simulation



## Stack

- Assembly
- Logisim
- Python
- Microcode
- Computer Architecture



## Architecture

The project uses the OrgaSmallWithStack processor architecture simulated in Logisim.

Main components explored during development include:
- Program Counter (PC)
- Register File
- ALU
- Stack Pointer
- Control Unit
- RAM
- Microinstruction memory



## Assembly Programming

Several assembly programs were implemented and analyzed to understand:
- arithmetic and logical operations,
- jumps and branching,
- stack usage,
- subroutine calls,
- and instruction execution flow.

The programs interact directly with registers, memory and processor flags while executing inside the simulated architecture.



## ISA Extension

One of the main goals of the project was extending the processor instruction set by implementing new custom instructions.

This required:
- modifying processor microinstructions,
- updating the control memory,
- integrating the new instruction into the architecture,
- and adapting the assembler to recognize the new opcode.

The implementation includes:
- custom `.ops` microinstruction definitions,
- updated memory files,
- and a modified assembler written in Python.



## Stack and Control Flow

The project also explores low-level stack operations and execution control through instructions such as:
- PUSH
- POP
- CALL
- RET
- JMP
- JZ

These instructions were analyzed both at the assembly level and at the microinstruction execution level.



## Key Learnings

- Assembly language programming
- Processor architecture fundamentals
- Stack-based execution
- ISA design and extension
- Instruction decoding
- Microinstruction execution
- Low-level debugging
- Computer architecture simulation



## Repository Structure

```
.
├── asm/
├── microcode/
├── assembler/
├── logisim/
├── assets/
└── README.md
```

## Future Improvements

Potential future extensions include:

- implementing additional custom instructions,
- improving memory management,
- adding interrupt handling,
- and exploring pipelined execution models.

## Author

Developed as a group project for the Computer Systems course at Universidad Torcuato Di Tella. Forked from [taimouteo's tp1-td2](https://github.com/taimouteo/tp1-td2).
