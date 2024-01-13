# Instruction-Set-Architecture-ISA-
The is project is created in Logisim software.
Following operations are performed by this Project

1. **ADD (Addition):**
   - Format: `ADD Rd, Rs1, Rs2`
   - Description: Add the contents of register `Rs1` to the contents of register `Rs2`, and store the result in register `Rd`.

2. **SUB (Subtraction):**
   - Format: `SUB Rd, Rs1, Rs2`
   - Description: Subtract the contents of register `Rs2` from the contents of register `Rs1`, and store the result in register `Rd`.

3. **MUL (Multiplication):**
   - Format: `MUL Rd, Rs1, Rs2`
   - Description: Multiply the contents of register `Rs1` by the contents of register `Rs2`, and store the result in register `Rd`.

4. **LOAD (Load from Memory):**
   - Format: `LOAD Rd, [Rs + Imm]`
   - Description: Load the value from memory at the address specified by the sum of the contents of register `Rs` and the immediate value `Imm` into register `Rd`.

5. **STORE (Store to Memory):**
   - Format: `STORE Rs, [Rd + Imm]`
   - Description: Store the contents of register `Rs` into the memory location specified by the sum of the contents of register `Rd` and the immediate value `Imm`.

6. **BEQ (Branch if Equal):**
   - Format: `BEQ Rs1, Rs2, Label`
   - Description: If the contents of registers `Rs1` and `Rs2` are equal, branch to the instruction labeled `Label`.

7. **JUMP (Unconditional Jump):**
   - Format: `JUMP Label`
   - Description: Unconditionally jump to the instruction labeled `Label`.

