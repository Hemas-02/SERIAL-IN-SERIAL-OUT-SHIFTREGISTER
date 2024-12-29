# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

## AIM:

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

## SOFTWARE REQUIRED:

Quartus prime

## THEORY

## SISO shift Register

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

## Procedure
/* write all the steps invloved */

## PROGRAM
![Screenshot 2024-12-29 144108](https://github.com/user-attachments/assets/516e3008-d648-4f46-ae0a-4ee8cadd1741)


## RTL LOGIC FOR SISO Shift Register
![WhatsApp Image 2024-12-29 at 14 36 33_2411531f](https://github.com/user-attachments/assets/e8bb9dd0-af00-4b1b-8be0-6bda3414c1dc)

## TIMING DIGRAMS FOR SISO Shift Register
![WhatsApp Image 2024-12-29 at 14 36 33_c476b217](https://github.com/user-attachments/assets/b3875d92-899d-4f57-bfe3-79c473df755d)

## RESULTS
 Implementation of SISO Shift Register using verilog and validating their functionality using their
 functional tables is verified
