# 5-Bit Binary Adder with 7-Segment Display Control

## Abstract
This project implements a 5-bit binary adder system that performs
addition on two 5-bit binary numbers.

The results are displayed using a 7-segment display, and the
system supports a control bit to switch between decimal and hexadecimal representations for the inputs
and outputs.


## Problem Definition
The main objective of the project is to:
- Add two 5-bit binary numbers.
- Display the operands and result on a 7-segment display.
- Integrate a control unit for toggling between decimal and hexadecimal representation


# Requirements
[Logisim](http://www.cburch.com/logisim/download.html): Digital circuit simulation software.


---

## Team Members
1. [Ahmed M. Ezzeldeen](https://github.com/ahmed3zzeldeen/)
2. [Mostafa Khafgy](https://github.com/mostafaKhafgy)

---

## Task List

- [X] **Create the Full Adder Subcircuit** `Assign to` [Mostafa Khafgy](https://github.com/mostafaKhafgy)
- [X] **Create the 5-bit Full Adder Using the Full Adder Subcircuit**  `Assign to` [Mostafa Khafgy](https://github.com/mostafaKhafgy)
- [X] **Add 7-Segment Displays circuit** `Assign to` [Ahmed M. Ezzeldeen](https://github.com/ahmed3zzeldeen/) 
  - [X] Add 6x64 Decoder circuit from 4x16 Decoder circuits 
  - [X] Add 7-Segment Display circuit
  - [X] Segment - A, B, C, D, E, F, G 
  - [X] Add Get Segment carry to the next 7-Segment Display
  - [X] Add Display-Carry circuit
  - [X] Add Display-Hex circuit
- [X] **Add Control Bit for Decimal/Hexadecimal Switching** `Assign to` [Mostafa Khafgy](https://github.com/mostafaKhafgy)
- [X] **Logic for Display Mode** [Ahmed M. Ezzeldeen](https://github.com/ahmed3zzeldeen/)
- [X] **Connect Everything Together** `Assign to` [Ahmed M. Ezzeldeen](https://github.com/ahmed3zzeldeen/) and [Mostafa Khafgy](https://github.com/mostafaKhafgy)


let's start with the design of the Full Adder Subcircuit :smile: :fire: 
