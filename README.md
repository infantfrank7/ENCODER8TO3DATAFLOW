Developed by: S INFANT JESUS 

RegisterNumber: 24001856


### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**
* Open Quartus2
* open new file
* create veri log file and using tools view the logic diagram
* Then click on netlist viewer and press RTL viewer to view the OUTPUT in graph format

**TRUTHTABLE**

![ENCODER TRUTHTABLE](https://github.com/user-attachments/assets/e7f39be5-fdb1-4e5a-98e9-536db576aef7)

**PROGRAM**

![encoder code](https://github.com/user-attachments/assets/927b812f-cd27-43ea-b7c5-75d27b162671)

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![encoder logic gates](https://github.com/user-attachments/assets/c367d0cb-554d-41a1-bf21-4fe4873b8ffd)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![encoder waveform](https://github.com/user-attachments/assets/7ea9fa80-46ee-48e7-91d4-4b31114104fa)


**RESULTS**

Hence implemented  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables



