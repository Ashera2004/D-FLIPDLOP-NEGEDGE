# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/48c81fe8-bc3f-40e7-95e2-519fc155ad51)

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/e5f3fda7-68ec-4a3a-a0a4-cf6f9cc4ab55)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/8592c0d8-2917-4142-91b9-d6c30dd891d2)

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

**Procedure**

1. Start a New Project in Quartus:

  • Open Quartus Prime and create a new project.
   
  • Define the project name and directory location.
  
2. Write the Verilog Code for the D Flip-Flop:

  • Use a positive edge-triggered approach to model the D flip-flop in Verilog.
  
  • The value of the output should change based on the D input during the positive clock edge.

3. Compile and Simulate:

  • Compile the design and run the simulation in Quartus.
  
  • Observe the output waveform to verify the functionality of the D flip-flop.

4. Analyze the Results:

  • Ensure that the output Q follows the D input at each positive clock edge, and holds the value between clock edges.


**PROGRAM**


![d_flipflop_code](https://github.com/user-attachments/assets/bbf4744e-4a4d-4466-a6d6-9fbddc44200b)


**RTL LOGIC FOR FLIPFLOPS**

![d_flipflop_rtl](https://github.com/user-attachments/assets/a1688f95-1312-4955-9b13-1ad0ae385047)



**TIMING DIGRAMS FOR FLIP FLOPS**



![d_flipflop_waveform](https://github.com/user-attachments/assets/8f7bea7f-4830-431c-94cb-737f9ed54acb)





**RESULTS**

• The Verilog code for the D flip-flop works correctly according to the truth table.

• The simulation results match the expected behavior of the D flip-flop. 
 
• The output waveform from the simulation will show that Q follows D on every positive clock edge, and holds the value when the clock is not transitioning.

• The functionality of the D flip-flop is validated using the simulation and timing diagram.


