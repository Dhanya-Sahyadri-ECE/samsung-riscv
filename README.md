# RISC-V Talent Development Program Powered by SAMSUNG and VSD
This is a RISC-V Internship using VSDSquadron Mini based  on RISC-V architecture and uses open-source tools to teach students about VLSI SoC design and RISC-V. The instructor and guide for this internship program is Mr. Kunal Ghosh, Co-Founder of VSD.

# ABOUT ME🚀
Name: Dhanya
-
College: Sahyadri College of Engineering and Management, Adyar, Mangaluru.
-
Email ID: dhanyan.ec22@sahyadri.edu.in or shettydhanya650@gmail.com
-
LinkedIn: [DHANYA ](https://www.linkedin.com/in/dhanya-shetty-66462626a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
-
<details>
<summary>TASK1:Development of C Based LAB</summary>
  https://github.com/Dhanya-Sahyadri-ECE/samsung-riscv/tree/ce8bf109ff0fc8f74c7ade2352a3bca843dedb95/TASK1
</details>
 <details>
<summary>TASK2:Simulation with Spike</summary>
https://github.com/Dhanya-Sahyadri-ECE/samsung-riscv/tree/ce8bf109ff0fc8f74c7ade2352a3bca843dedb95/TASK2
 </details>
 <details>
<summary>TASK3:32 bit segment of objdump</summary>
https://github.com/Dhanya-Sahyadri-ECE/samsung-riscv/tree/ce8bf109ff0fc8f74c7ade2352a3bca843dedb95/TASK3

1. *lui* (Load Upper Immediate)
   - Instruction: lui a0, 0x2b
   - Opcode: 0110111
   - Format: U-type
   - 32-bit Encoding: 00000000001010110000000010110111
*Machine Code:* 002b537  
| *imm[31:12]* | *rd*   | *opcode* |  
|:--------------:|:--------:|:----------:|  
| 0000000000101011 | 01010 | 0110111 |

2. *addi* (Add Immediate)
   - Instruction: addi sp, sp, -32
   - Opcode: 0010011, Funct3: 000
   - Format: I-type
   - 32-bit Encoding: 11111111111000001010001010010011
*Machine Code:* fe010113  
| *imm[11:0]*  | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:--------------:|:--------:|:----------:|:--------:|:-----------:|  
| 111111111110 | 00010  | 000      | 00010  | 0010011   |

3. *addi* (Add Immediate)
   - Instruction: addi a0, a0, -992
   - Opcode: 0010011, Funct3: 000
   - Format: I-type
   - 32-bit Encoding: 11111111000000000101010110010011
*Machine Code:* c2050513  
| *imm[11:0]*  | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:--------------:|:--------:|:----------:|:--------:|:-----------:|  
| 111111000010 | 01010  | 000      | 01010  | 0010011   |

5. *jal* (Jump and Link)
   - Instruction: jal ra, 10454
   - Opcode: 1101111
   - Format: J-type
   - 32-bit Encoding: 00000010001100100000111111001111
*Machine Code:* 394000ef  
| *imm[20]* | *imm[10:1]* | *imm[11]* | *imm[19:12]* | *rd*  | *opcode* |  
|:-----------:|:-------------:|:-----------:|:--------------:|:-------:|:----------:|  
| 0         | 1110010000  | 0         | 00011110     | 00001 | 1101111  |

6. *addi* (Add Immediate)
   - Instruction: addi a2, sp, 12
   - Opcode: 0010011, Funct3: 000
   - Format: I-type
   - 32-bit Encoding: 00000000001101000011001010010011
*Machine Code:* 00c10613  
| *imm[11:0]* | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:-------------:|:--------:|:----------:|:--------:|:-----------:|  
| 000000001100 | 00010 | 000      | 00011  | 0010011   

7. *addi* (Add Immediate)
   - Instruction: addi a1, sp, 8
   - Opcode: 0010011, Funct3: 000
   - Format: I-type
   - 32-bit Encoding: 00000000001001000010001010010011
Machine Code:* 00810513  
| *imm[11:0]* | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:-------------:|:--------:|:----------:|:--------:|:-----------:|  
| 000000001000 | 00010 | 000      | 00010  | 0010011   |

8. *jal* (Jump and Link)
   - Instruction: jal ra, 1048a
   - Opcode: 1101111
   - Format: J-type
   - 32-bit Encoding: 00001010001100100000111111001111
*Machine Code:* 394000ef  
| *imm[20]* | *imm[10:1]* | *imm[11]* | *imm[19:12]* | *rd*  | *opcode* |  
|:-----------:|:-------------:|:-----------:|:--------------:|:-------:|:----------:|  
| 0         | 1110010001  | 0         | 00011110     | 00001 | 1101111  |

9. *lw* (Load Word)
   - Instruction: lw a0, 8(sp)
   - Opcode: 0000011, Funct3: 010
   - Format: I-type
   - 32-bit Encoding: 00000000001000010000001010010011
*Machine Code:* 00812283  
| *imm[11:0]* | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:-------------:|:--------:|:----------:|:--------:|:-----------:|  
| 000000001000 | 00010 | 010      | 01010  | 0000011   |

10. *sext.w* (Sign Extend Word)
    - Instruction: sext.w a1, a0
    - Opcode: Custom extension
    - 32-bit Encoding: Not defined (depends on ISA extension)
*Machine Code:* 0800059b  
| *imm[11:0]* | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:-------------:|:--------:|:----------:|:--------:|:-----------:|  
| 000010000000 | 00010 | 000      | 00010  | 0011011   |

11. *lui* (Load Upper Immediate)
    - Instruction: lui a0, 0x2b
    - Opcode: 0110111
    - Format: U-type
    - 32-bit Encoding: 00000000001010110000000010110111
*Machine Code:* 002b537  
| *imm[31:12]* | *rd*   | *opcode* |  
|:--------------:|:--------:|:----------:|  
| 0000000000101011 | 01010 | 0110111 |

12. *addi* (Add Immediate)
    - Instruction: addi a0, a0, -960
    - Opcode: 0010011, Funct3: 000
    - Format: I-type
    - 32-bit Encoding: 11111111001000000101010010010011
*Machine Code:* fc050513  
| *imm[11:0]* | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:-------------:|:--------:|:----------:|:--------:|:-----------:|  
| 111111000010 | 01010 | 000      | 01010  | 0010011   |

13. *jal* (Jump and Link)
    - Instruction: jal ra, 10454
    - Opcode: 1101111
    - Format: J-type
    - 32-bit Encoding: 00000010001100100000111111001111
*Machine Code:* 394000ef  
| *imm[20]* | *imm[10:1]* | *imm[11]* | *imm[19:12]* | *rd*  | *opcode* |  
|:-----------:|:-------------:|:-----------:|:--------------:|:-------:|:----------:|  
| 0         | 1110010000  | 0         | 00011110     | 00001 | 1101111  |

14. *ld* (Load Doubleword)
    - Instruction: ld ra, 24(sp)
    - Opcode: 0000011, Funct3: 011
    - Format: I-type
    - 32-bit Encoding: 00001100001100100000111010010011
*Machine Code:* 01812083  
| *imm[11:0]* | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:-------------:|:--------:|:----------:|:--------:|:-----------:|  
| 000000001100 | 00010 | 011      | 00001  | 0000011   |

15. *ret* (Return)
    - Instruction: ret
    - Pseudoinstruction (maps to jalr x0, ra, 0)
    - Opcode: 1100111, Funct3: 000
    - Format: I-type
    - 32-bit Encoding: 00000000000000001100111001100111
*Machine Code:* 00008067  
| *imm[11:0]* | *rs1*  | *funct3* | *rd*   | *opcode*  |  
|:-------------:|:--------:|:----------:|:--------:|:-----------:|  
| 000000000000 | 00001 | 000      | 00000  | 1100111   |
</details>
