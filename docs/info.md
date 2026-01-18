## How it works

This project implements a **2-input NAND logic gate**.

The NAND gate performs the logical negation of the AND operation.  
Its function is defined as:

**F = ¬(A · B)**

The circuit has:
- Two inputs: **A**, **B**
- One output: **F**

The output **F** is logic `0` only when **both A and B are logic `1`**.  
For all other input combinations, the output **F** is logic `1`.

---

## How to test

Apply all combinations of inputs **A** and **B** and verify the output **F** using the NAND truth table.

| A | B | F |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

Each input combination should be held stable for several clock cycles (for example, 25 cycles) before checking the output.

---

## External hardware

None.
