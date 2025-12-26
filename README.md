# 5.VERIFICATION-OF-NORTON-S-THEOREM
#NAME:A.SARANRAJ

#REGISTER NO:25018567

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

<img width="347" height="313" alt="image" src="https://github.com/user-attachments/assets/14c7b70d-944e-48b0-9c7f-900bc8c4b82c" />



1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**

<img width="543" height="290" alt="image" src="https://github.com/user-attachments/assets/cfe5f8d1-24b2-4482-bc72-3106e94b9c6a" />



**To measure RTh or RN**

<img width="502" height="165" alt="image" src="https://github.com/user-attachments/assets/43c07e2f-3360-42a3-8fd5-cead54299869" />


**To measure IN or Isc**


 <img width="543" height="223" alt="image" src="https://github.com/user-attachments/assets/3738a36c-a452-425a-ac9f-81fe53f68f1d" />




**Norton’s equivalent circuit**
<img width="375" height="220" alt="image" src="https://github.com/user-attachments/assets/6808b22e-f8ab-4720-9a40-2bac68cb9cd5" />


**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
To measure I L
<img width="239" height="120" alt="image" src="https://github.com/user-attachments/assets/61f45660-ada1-4827-883d-910660ad0ceb" />


**TABULAR COLUMN:2**

To measure RTh or RN

Vi (volts)	RTh (Ω)
<img width="215" height="102" alt="image" src="https://github.com/user-attachments/assets/06d09dbe-56e0-4fba-a58f-d5895aa28a9d" />


**TABULAR COLUMN:3**

To measure IN or Isc

Vi (volts)	IN (amps)
<img width="243" height="127" alt="image" src="https://github.com/user-attachments/assets/a2a59737-bf5b-44ad-bf3c-95bf5390a7bc" />


	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 

\

<img width="400" height="628" alt="image" src="https://github.com/user-attachments/assets/f21d72e8-1212-4f6a-a44b-938d48afe7d1" />

<img width="368" height="423" alt="image" src="https://github.com/user-attachments/assets/0f176b37-156a-4528-b0c0-ed31016a5a49" />

**RESULT:**



<img width="334" height="380" alt="image" src="https://github.com/user-attachments/assets/b34f4d8c-5c0b-4cca-8d58-af1492812f9f" />

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
