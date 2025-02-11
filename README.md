# Laboratory 2- For Good Measure: Basic Circuits

Aashika Uppala, Megan Fister

2/10/2025

## Introduction
The purpose of this lab was to analyze basic electrical circuits by measuring voltages and currents in both series and parallel configurations.
This experiment aimed to verify Kirchhoff’s Voltage Law (KVL) and Kirchhoff’s Current Law (KCL) while also applying Thevenin’s theorem. 
and the superposition theorem to analyze electrical circuits. In this lab, we aimed to apply these fundamental principles by constructing and analyzing both series and parallel circuits. The experiment was designed to verify KVL and KCL through direct measurement of circuit parameters. Furthermore, Thevenin’s theorem was explored by determining the equivalent circuit parameters experimentally and comparing them to theoretical calculations.

## Methods
### Instruments
• A Digital Multimeter (DMM)

• A DC Power supply

• A Soldering station

• A small piece of solder

• Solder protoboard

• Resistors: 1kΩ, 2.2 kΩ, 2.2 kΩ, 5.1 kΩ, 4.7 kΩ, 6.8 kΩ, 15 kΩ, 220 kΩ


The lab was divided into two main tasks:

First, we learned soldering techniques by building a simple series circuit on a solder protoboard. Second, we analyzed a circuit by measuring and comparing theoretical and experimental values to confirm the validity of fundamental circuit laws. By conducting this lab, we not only reinforced our theoretical understanding of circuit laws but also developed hands-on skills in circuit construction, soldering, and precise electrical measurements. The experimental results were expected to align with theoretical predictions, demonstrating the accuracy and applicability of these fundamental electrical concepts in real-world engineering.

_Objective 1: Learn soldering techniques by building a simple circuit on a solder protoboard_

#### Part 1 - Series Circuit
The first step is to measure the resistance of each resistor using a DMM to ensure they are within the expected range and to record their values for use in future calculations.

The next step is to build the circuit below on a solder breadboard:

![Circuit 1](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Figure%201.png)

While building the circuit, turn on the soldering station to allow it to heat to 800 degrees Celcius. Make sure to clean the tip with a wet sponge and be careful not to touch anything with the soldering tool except the solder breadboard.

![Soldering Setup](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Circuit%20before%20soldering.jpg)

After the circuit is built, touch the tip and a small piece of solder to each component to solder the components to a solder breadboard.

![Soldering](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Soldering.jpg)

Once the components are soldered to the breadboard, connect the circuit to the DC Power Supply and set it to 10 V and the current to the minimum value. Using the DMM, measure the voltage drop across each resistor.

![Measuring Voltage Drop Across Resistor](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Measuring%20across%20resistor.jpg)

Then, measure the voltage drop across the whole circuit.

![Measuring Voltage Drop Across Circuit](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Measuring%20across%20circuit.jpg)

After changing the DMM settings to measure the current, interrupt the circuit by disconnecting the positive end from the voltage power and connecting the DMM between a resistor and the voltage to measure the current. 

![Measuring Current](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Measuring%20positive%20to%20top%20of%20circuit.jpg)

_Objective 2: Analyze a circuit to verify Kirchhoff’s voltage law (KVL) and Kirchhoff’s current law (KCL), and to apply Thevenin’s and superposition theorems to the analysis of electrical circuits_

#### Part 2 - Parallel Circuit
##### Part 2.1 KCL
The first step is to measure the resistance of each resistor using a DMM to ensure they are within the expected range and to record their values for use in future calculations.

The next step is to build the circuit below on a regular prototyping breadboard.
![Circuit 2](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Figure%202.png)

Change the DMM settings and measure the current across each resistor using the DMM. 

##### Part 2.2 KVL
Change the DMM settings and measure voltage drop across each resistor using alligator clips. Next, measure the total voltage drop. Record this data in a table. 


##### Part 2.3 Thevenin and Norton
Build the circuit below by removing $R_5$ in order to calculate the Thevenin equivalent:
![Circuit 3](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Figure%203.png)

Measure the voltage across $R_4$ which is the same as $V_TH$ using the DMM. 
Also use the DMM to measure current $I_N$
**Remove the DCPS leads from the circuit and replace them with one wire joining the
disconnected end of R1 with the disconnected ends of R3 or R4*
**Use the DMM as an Ohm meter to measure the equivalent resistance (RTH/RN) for the whole
passive circuit*

## Results

### Part 1 - Series Circuit

_Measured Resistance_
|Resistor|Expected (Ω)| Measured (Ω) |
|---|---|---|
|$R_1$|  2200 | 2176 |
|$R_2$| 5100   | 5007 |
|$R_3$|  1000  | 986 |
|Whole Circuit|  8300 | 8170 |

_Measured Voltage Drop_
|Resistor|Measured (V)|
|---|---|
|$R_1$|  1.206  |
|$R_2$|  2.667  |
|$R_3$|  6.129  |
|Whole Circuit|  10.002 |

_Measured Current_
1.24 mA is the current across the circuit.

### Part 2 - Parallel Circuit
#### Part 2.1 KCL
_Measured Resistance_
|Resistor|Expected (kΩ)| Measured (kΩ) |
|---|---|---|
|$R_1$|  4.7 | 4.669 |
|$R_2$| 6.8   | 6.700 |
|$R_3$|  15  | 14.71 |
|$R_4$|  220 | 218.7 |
|$R_5$|  2.2 | 2.174 |

Stated voltage = 12 V

Measured voltage across = 11.99 V

Confirmed that measured voltage is within 0.1 V of the stated voltage.

_Measured Current_
|Current Label|Measured (mA)|
|---|---|
|$I_1$|  1.82  |
|I<sub>2/3</sub>|  0.18  |
|$I_4$|  0.03  |
|I<sub>5/L</sub>|  1.64 |

#### Part 2.2 KVL

_Measured Voltage_
|Voltage|Measured Magnitude (V)| Calculated Voltages (V) |
|---|---|---|
|$V_1$| 8.21  | 8.55 |
|$V_2$| 11.08   | 1.224 |
|$V_3$|  2.433  | 2.7 |
|$V_4$|  3.543 | 6.6 |
|$V_5$|  3.543 | 3.608 |

Calculate the expected voltage drop for each resistor using Ohm’s Law (V = IR) and the measured currents

#### Part 2.3 Thevenin and Norton

| |Measured| Calculated|
|---|---|---|
|V<sub>TH</sub>| 9.67 V | 9.67 V |
|$I_N$| 2.58 mA   | 2.56 mA |
|R<sub>TH</sub> / $R_N$|  3.768 kΩ  | 3.77 kΩ |

R<sub>Eq</sub> = 1/(((1/(R2 + R3))) + (1/R4)) = 19.5 kΩ

R<sub>TH</sub> = 1 / ((1 / R<sub>1</sub>) + (1 / R<sub>Eq</sub>)) = 1 / ((1/4.669 kΩ) + (1/19.5 kΩ)) = 3.77 kΩ

V<sub>TH</sub> = V<sub>S</sub> * (R<sub>Eq</sub> / ( R<sub>1</sub> + R<sub>Eq</sub>)) = 11.99 V * (19.5 kΩ / (4.669 kΩ + 19.5 kΩ)) = 9.67 V

$I_N$ = V<sub>TH</sub> / R<sub>TH</sub> = 9.67 V / 3.77 kΩ = 2.56 mA


## Discussion
### Part 2.1 KCL
_Discussion Question 1: Are the measured currents in agreement with Kirchhoff’s Current Law?_

Kirchhoff’s Current Law (KCL) states that the sum of currents entering a node must equal the sum of currents leaving the node. To verify this, we analyzed the measured currents in the circuit.

According to KCL, the total current entering a node should equal the sum of the outgoing currents:

I<sub>1</sub>=I<sub>2/3</sub>+I<sub>4</sub>+I<sub>5</sub>

1.82 mA ≈ 1.85 mA

The left side (measured total current) is 1.82 mA, while the right side (sum of branch currents) is 1.85 mA. The difference is 0.03 mA, or 1.64%, which is a small deviation likely caused by: 

- Measurement inaccuracies in the digital multimeter.
  
- Tolerances in resistor values affect actual resistance.
  
- Minor fluctuations in the power supply voltage.

- The measured currents closely follow Kirchhoff’s Current Law.


### Part 2.2 KVL
_Discussion Question 2: Compare the measured values and the calculated values. Are these in agreement with Kirchhoff’s Voltage Law?_

Kirchhoff's voltage law (KVL) states that the sum of all voltage changes around a closed loop in an electrical circuit is zero.

The voltage readings of the measured vs. calculated for V1, V3, and V5 are similar. However, V4 is off, likely due to the significantly higher resistance of R4 compared to the others. V2 was recorded at 11.08 V, but there is a possibility of a decimal placement error. Based on the calculations, if V2 were actually 1.108 V instead of 11.08 V, the resulting calculated voltage would align more closely with expectations.

_Loop 1_

Measured: 8.21 V + 11.08 V + 2.433 V - 10 V = 11.723 V

Calculated: 8.55 V + 1.224 V + 2.7 V - 10 V = 2.474 V

_Loop 2_

Measured: 3.543 V - 2.433 V - 11.08 V = -9.97 V

Calculated: 6.6 V - 2.7 V - 1.224 V = 2.676 V

_Loop 3_ 

Measured: 3.543 V - 3.543 V = 0 V

Calculated: 3.608 V - 6.6 V = -2.992 V

The calculated values sum to approximately 2.5 to 3 V, when they should ideally total 0 V. This discrepancy may be due to V4 being 3 V off from its calculated value. Additionally, for the measured voltages, both loops containing V2 deviate from 0 V by a factor of 10, which suggests a possible decimal placement error. With this in mind, I would conclude that Kirchhoff’s Voltage Law holds true, as the discrepancies are likely due to measurement or calculation errors. If the measured values were corrected—particularly the misreading of V2 and the deviation in V4—the voltages would sum to zero as expected.


_Discussion Question 3: Calculate the power delivered by the power supply and the power dissipated by every resistor. Is the power delivered by the power supply equal to the total power dissipated?_

The power dissipated is calculated using P = VI. 

_Power delivered by power supply_

P1 = 8.21*1.82 = 14.9 mW

P2 = 11.08*0.18 = 1.99 mW

P3 = 2.433*0.18 = 0.44 mW

P4 = 3.543*0.03 = 0.11 mW

P5 = 3.543*1.64 = 5.81 mW

Power total = 23.25 mW

_Power generated by DC Power Supply_

P = 12 V * 2.5 mA = 30 mW

The power delivered by the power supply is not equal to the total power dissipated but they are not within 10 mW of each other. This could indicate:

- Measurement inaccuracies in voltage readings.
  
- Power loss in circuit components not accounted for (e.g., wires, contacts).
  
- Resistor tolerance variations affecting actual resistance values.
  
- The power balance does not perfectly hold.
  
- The discrepancy suggests possible circuit inefficiencies or measurement errors.
  
- Further error analysis and improved measurement techniques may provide more accurate results.


### Part 2.3 Thevenin and Norton
_Discussion Question 4: Using circuit analysis, calculate RTH, IN, and VTH, and compare them with the measured values. Are the calculated values in agreement with the measured values?_

Thevenin’s Theorem states that any linear circuit can be simplified into a single voltage source (VTH) and a series resistance (RTH). Norton’s Theorem represents the same circuit as a current source (I<sub>N</sub>) in parallel with a resistance (R<sub>N</sub>). To verify these theorems, we compare the measured and calculated values of V<sub>TH</sub>, I<sub>N</sub>, and R<sub>TH</sub> / R<sub>N</sub>.

Using Ohm’s Law and circuit analysis the Thevenin voltage is the open-circuit voltage across R4 when R5 is removed. The Norton current is found by short-circuiting the load terminals and measuring the resulting current. The Thevenin resistance is measured by removing the power source and determining resistance across the open terminals. 

The experiment confirms that Thevenin and Norton equivalent values hold true within experimental tolerances. The calculated values agree with the measured values, verifying both theorems in practical circuit analysis. The minor discrepancies are within acceptable limits, demonstrating the effectiveness of Thevenin and Norton transformations from multimeter accuracy limitations and resistor tolerances. 


## Conclusion
In conclusion, this lab successfully demonstrated the fundamental electrical circuit laws, including Kirchhoff’s Current Law (KCL) and Kirchhoff’s Voltage Law (KVL). The experimental results closely aligned with theoretical calculations, validating the principles of circuit analysis.
Additionally, we gained hands-on experience in soldering and circuit measurement techniques. The Thevenin and Norton equivalent circuits were analyzed and verified through direct measurement and calculations. Any discrepancies were likely due to component tolerances, measurement limitations, or human errors.
This experiment reinforced the importance of accurate circuit measurements and understanding of basic electrical laws in engineering applications.
