# 4-Bit ALU Using Two Registers

A 4-bit Arithmetic Logic Unit (ALU) implemented in Proteus using TTL logic components. The system uses two 4-bit registers, Register A and Register B, to store operands and perform arithmetic and logical operations selected through three control signals.

## Features

* Two 4-bit registers (A and B)
* 4-bit output
* Arithmetic and logical operations
* LED output display
* Implemented using standard TTL ICs:

  * 74LS173 (Registers)
  * 74LS283 (4-bit Adder)
  * 74LS151 (8-to-1 Multiplexers)
  * 74LS04, 74LS08, 74LS11, 74LS32 (Logic Gates)

## Function Table

| S2 | S1 | S0 | Operation |
| -- | -- | -- | --------- |
| 0  | 0  | 0  | A + B     |
| 0  | 0  | 1  | A - B     |
| 0  | 1  | 0  | A × 2     |
| 0  | 1  | 1  | B ÷ 2     |
| 1  | 0  | 0  | A AND B   |
| 1  | 0  | 1  | A OR B    |
| 1  | 1  | 0  | None      |
| 1  | 1  | 1  | None      |

## Software

* Proteus 8 Professional

## Objective

The objective of this project is to design and implement a simple 4-bit ALU capable of performing basic arithmetic and logical operations using digital logic circuits. The project demonstrates the fundamental concepts of processor datapath design and hardware-based computation.
