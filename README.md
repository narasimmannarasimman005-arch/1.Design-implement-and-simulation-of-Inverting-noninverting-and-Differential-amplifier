# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**


<img width="840" height="390" alt="image" src="https://github.com/user-attachments/assets/7393f5cc-bad5-4d5d-91e9-41a8304083e0" />

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**

  
  <img width="662" height="446" alt="image" src="https://github.com/user-attachments/assets/e497acf1-eec8-44e1-901f-0594a1956a01" />


  **MODEL GRAPH:**
  
  
<img width="755" height="553" alt="image" src="https://github.com/user-attachments/assets/6bae5edf-0333-414b-93f4-ee4c461ebd75" />


  **TABULATION:**
 

<img width="526" height="467" alt="image" src="https://github.com/user-attachments/assets/6109f765-d747-4cb3-b3a4-9d85080bdc74" />


**graph**


<img width="650" height="378" alt="image" src="https://github.com/user-attachments/assets/b3d97853-b69f-4614-b3c4-6b77224b8d7d" />

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**

  <img width="476" height="315" alt="image" src="https://github.com/user-attachments/assets/ad988ef7-fb6f-4065-ae9b-b3df60d4f2ee" />



  **MODEL GRAPH:**

  <img width="486" height="253" alt="image" src="https://github.com/user-attachments/assets/11d68adc-18d2-4d6e-ab6f-dd94a8ad4736" />


  **TABULATION:**

  <img width="513" height="317" alt="image" src="https://github.com/user-attachments/assets/83ae6ec5-66a2-40d4-8e67-a9d90fb21015" />

 **graph**
 

 <img width="590" height="463" alt="image" src="https://github.com/user-attachments/assets/d4ae376d-3ab2-4711-b34e-a80e02474bdc" />


  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**

  <img width="625" height="540" alt="image" src="https://github.com/user-attachments/assets/7a16aef0-9e4a-4830-b2d0-97a902bff2fc" />



  **MODEL GRAPH:**

  <img width="535" height="301" alt="image" src="https://github.com/user-attachments/assets/94baaea3-328c-4753-80b9-06ac7ad96301" />



  **TABULATION:**

  <img width="518" height="500" alt="image" src="https://github.com/user-attachments/assets/21cbc522-ff05-421c-a414-f0b0e6691c85" />

**graph**


<img width="646" height="698" alt="image" src="https://github.com/user-attachments/assets/9a3d333c-d205-4b05-a3d5-d8addb7581ec" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**

   <img width="1600" height="817" alt="image" src="https://github.com/user-attachments/assets/3f2507b1-9588-4744-9d15-fe57489b1f96" />



   <img width="1600" height="827" alt="image" src="https://github.com/user-attachments/assets/e7344719-7d8b-4e70-beba-656d79c1c25a" />



   <img width="1600" height="808" alt="image" src="https://github.com/user-attachments/assets/ce91e76b-b5c1-40b7-a192-6c3baf640d05" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






