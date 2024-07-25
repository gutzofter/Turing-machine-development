### Opcode Listing (Version 0.0.3)

#### Data Transfer Instructions
| Opcode | Mnemonic | Type         | Format       |
|--------|----------|--------------|--------------|
| 0x01   | MOV      | Data Transfer | `MOV REG, DATA` |
| 0x02   | LOAD     | Data Transfer | `LOAD REG, MEM` |
| 0x03   | STORE    | Data Transfer | `STORE REG, MEM` |

#### Arithmetic Instructions
| Opcode | Mnemonic | Type        | Format        |
|--------|----------|-------------|---------------|
| 0x10   | ADD      | Arithmetic  | `ADD REG, REG` |
| 0x11   | SUB      | Arithmetic  | `SUB REG, REG` |
| 0x12   | MUL      | Arithmetic  | `MUL REG, REG` |
| 0x13   | DIV      | Arithmetic  | `DIV REG, REG` |

#### Logical Instructions
| Opcode | Mnemonic | Type     | Format        |
|--------|----------|----------|---------------|
| 0x20   | AND      | Logical  | `AND REG, REG` |
| 0x21   | OR       | Logical  | `OR REG, REG`  |
| 0x22   | XOR      | Logical  | `XOR REG, REG` |
| 0x23   | NOT      | Logical  | `NOT REG`      |

#### Control Flow Instructions
| Opcode | Mnemonic | Type          | Format             |
|--------|----------|---------------|---------------------|
| 0x30   | JMP      | Control Flow  | `JMP LABEL`         |
| 0x31   | CALL     | Control Flow  | `CALL FUNC`         |
| 0x32   | RET      | Control Flow  | `RET`               |
| 0x33   | CMP      | Control Flow  | `CMP REG, REG`      |
| 0x34   | JNE      | Control Flow  | `JNE LABEL`         |
| 0x35   | JEQ      | Control Flow  | `JEQ LABEL`         |

#### Input/Output Instructions
| Opcode | Mnemonic | Type         | Format       |
|--------|----------|--------------|--------------|
| 0x40   | IN       | I/O          | `IN REG, PORT` |
| 0x41   | OUT      | I/O          | `OUT REG, PORT` |

#### C-Compliant Instructions
| Opcode | Mnemonic | Type             | Format              |
|--------|----------|------------------|----------------------|
| 0x50   | MOVI     | Data Transfer    | `MOVI REG, IMM`      |
| 0x51   | SHL      | Arithmetic       | `SHL REG, IMM`       |
| 0x52   | SHR      | Arithmetic       | `SHR REG, IMM`       |
| 0x53   | INC      | Arithmetic       | `INC REG`            |
| 0x54   | DEC      | Arithmetic       | `DEC REG`            |
| 0x55   | NEG      | Arithmetic       | `NEG REG`            |
| 0x56   | NOT      | Logical          | `NOT REG`            |
| 0x57   | MOVA     | Data Transfer    | `MOVA REG, ADDR`     |
| 0x58   | PUSH     | Stack Operation  | `PUSH REG`           |
| 0x59   | POP      | Stack Operation  | `POP REG`            |
| 0x5A   | CALL     | Function Call    | `CALL FUNC`          |
| 0x5B   | RET      | Function Return  | `RET`                |

#### Process Transition Table
| State | Input | Next State | Action       |
|-------|-------|------------|--------------|
| S0    | I0    | S1         | `ACTION1`    |
| S1    | I1    | S2         | `ACTION2`    |
| S2    | I2    | S3         | `ACTION3`    |
| S3    | I3    | S0         | `ACTION4`    |

### Version Information
- [Opcode Listing Version 0.0.1](#)
- [Opcode Listing Version 0.0.2](#)
- [Opcode Listing Version 0.0.3](#)

### Assembly Code Listings
- [Basic Input/Output System (BIOS) - Version 0.0.1](#)
- [Multiplication Transition Table - Version 0.0.1](#)
- [Bitwise Operations - Version 0.0.1](#)
- [Transition Table - Version 0.0.1](#)
- [Process Transition Table - Version 0.0.1](#)

Note: The URLs are placeholders and should be replaced with actual links where the code listings and versions are hosted.
