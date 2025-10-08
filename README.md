# SERIAL-IN-SERIAL-OUT-SHIFT REGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)


The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

Step 1: Apply the first data bit serially at the input terminal of the first flip-flop.

Step 2: On the first clock pulse, the input bit is stored in the first flip-flop.

Step 3: Apply the next data bit and, with the next clock pulse, shift the previous bit into the second flip-flop.

Step 4: Continue applying input bits, and with each clock pulse, all stored bits shift one position to the right.

Step 5: After all bits are entered, continue giving clock pulses to shift data out serially from the last flip-flop.

Step 6: The output appears serially in the same order as the input but delayed by the number of stages in the register.

**PROGRAM**

 Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by: POPURI SAHITHYA  RegisterNumber: 25004681

<img width="1546" height="650" alt="{265A386E-79C4-499B-BE25-A3AD6ACD11BB}" src="https://github.com/user-attachments/assets/d9004c9d-f1b1-4141-8f94-e6c883676140" />

**RTL LOGIC FOR SISO Shift Register**

<img width="1496" height="686" alt="{B9B6BB41-F729-4342-90D7-706D13D18670}" src="https://github.com/user-attachments/assets/ed1fd96e-9c25-4bad-8778-eff60dfee020" />


**TIMING DIGRAMS FOR SISO Shift Register**

<img width="1028" height="155" alt="{6B4D6E4F-6A0B-478A-A8FD-C654FF215EB6}" src="https://github.com/user-attachments/assets/03640c6c-216b-468b-9d7c-30d452e25963" />

**RESULTS:**
Thus SISO Shift Register using verilog and validating their functionality using their functional tables has successful execution of the program.
