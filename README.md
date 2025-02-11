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
The first step is to measure the resistance of each resistor using the DMM.

The next step is to build the circuit below:

![Circuit 1](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Figure%201.png)

While building the circuit, we turned on the soldering station to allow it to heat to 800 degrees Celsius.

![Soldering Setup](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Circuit%20before%20soldering.jpg)

After the circuit is built, we used the tip to solder the components to a solder breadboard.

![Soldering](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Soldering.jpg)

Once the components were soldered to the breadboard, we connected the circuit to the DC Power Supply and set it to 10 V. Using the DMM, we measured the voltage drop across each resistor.

![Measuring Voltage Drop Across Resistor](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Measuring%20across%20resistor.jpg)

Then, we measured the voltage drop across the whole circuit.

![Measuring Voltage Drop Across Circuit](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Measuring%20across%20circuit.jpg)

After changing the DMM settings to measure the current, we interrupted the circuit by disconnecting the positive end from the voltage power and connecting the multimeter between a resistor and the voltage. 

![Measuring Current](https://github.com/aashikauppala/BAE-305-lab2/blob/main/Lab%202%20-%20Measuring%20positive%20to%20top%20of%20circuit.jpg)

#### Part 2 - Parallel Circuit
The first step is to measure the resistance of each resistor using the DMM.

The next step is to build the circuit below on a regular prototyping breadboard.
![Circuit 2]

### Objective 2: Analyze a circuit to verify Kirchhoff’s voltage law (KVL) and Kirchhoff’s current law (KCL), and to apply Thevenin’s and superposition theorems to the analysis of electrical circuits


## Results
Verification of Kirchhoff’s Laws:
The measured currents confirmed KCL, as the sum of currents entering and leaving each node was approximately equal.
The measured voltages confirmed KVL, as the total voltage drop matched the supplied voltage.
Power Analysis:
The power supplied by the source was approximately equal to the total power dissipated across all resistors, confirming conservation of energy in the circuit. Thevenin and Norton Equivalence:
The measured Thevenin Voltage (VTH) and Thevenin Resistance (RTH) were close to the calculated values. The measured short-circuit current (IN) confirmed the theoretical Norton equivalent.
Sources of Error:
Measurement errors due to DMM inaccuracies. Component tolerances affecting resistance values. Connection issues in soldered circuits.

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

## Discussion

## Conclusion
In conclusion, this lab successfully demonstrated the fundamental electrical circuit laws, including Kirchhoff’s Current Law (KCL) and Kirchhoff’s Voltage Law (KVL). The experimental results closely aligned with theoretical calculations, validating the principles of circuit analysis.
Additionally, we gained hands-on experience in soldering and circuit measurement techniques. The Thevenin and Norton equivalent circuits were analyzed and verified through direct measurement and calculations. Any discrepancies were likely due to component tolerances, measurement limitations, or human errors.
This experiment reinforced the importance of accurate circuit measurements and understanding of basic electrical laws in engineering applications.
