<head>

<script type="text/javascript" async src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML"> 
  
</script>

</head>



<div style="text-align: justify; font-size: 18px;font-family: 'Nunito Sans',sans-serif;">
<h3>Introduction</h3>
A Maxwell bridge is a modification to a Wheatstone bridge used to measure an unknown inductance (usually of low Q value) in calibrated resistance and inductance or resistance and capacitance. The bridge is known as a Maxwell-Wien bridge when the calibrated components are a parallel resistor and capacitor. It is named for James C. Maxwell, who first described it in 1873.<br><br> 
It uses the principle that the positive phase angle of an inductive impedance can be compensated by the negative phase angle of a capacitive impedance when put in the opposite arm and the circuit is at resonance; i.e., no potential difference across the detector (an AC voltmeter or ammeter)) and hence no current flows through it. The unknown inductance then becomes known in terms of this capacitance.<br>

<center> 

![circuit](images/circuit.png)

**Fig. 1 Maxwell Bridge**

</center>

Regarding the picture, in a typical application R<sub>1</sub> and R<sub>4</sub> are known fixed entities, and R<sub>2</sub> and  C<sub>2</sub> are known variable entities. R<sub>2</sub> and  C<sub>2</sub> are adjusted until the bridge is balanced. R<sub>3</sub> and  L<sub>3</sub> can then be calculated based on the values of the other components

### Types of Maxwell’s Bridge
Two methods are used for determining the self-inductance of the circuit. They are

1. Maxwell’s Inductance Bridge
2. Maxwell’s inductance Capacitance Bridge

### Maxwell’s Inductance Bridge
In such type of bridges, the value of unknown resistance is determined by comparing it with the known value of the standard self-inductance. The connection diagram for the balance Maxwell bridge is shown in the figure below.

<center> 

![circuit](images/circuit2.png)

**Fig. 2 Maxwell Inductance Bridge**

</center>

Where, L1 – Unknown inductance of resistance R1.<br>
L2 – Variable inductance of fixed resistance r2.<br>
R2 – Variable resistance connected in series with inductor L2.<br>
R3, R4 – Known non-inductance resistance.<br>

At balance,

<center>

$$L_1 = \frac{R3}{R4}L2$$

</center>

<center>

$$R1 = \frac{R3}{R4}(R2+r2)$$

</center>

The value of the R3 and R4 resistance varies from 10 to 1000 ohms with the help of the resistance box. Sometimes for balancing the bridge, the additional resistance is also inserted into the circuit. The phasor diagram of Maxwell’s inductance bridge is shown in the figure below.

<center> 

![circuit](images/circuit3.jpg)

**Fig. 3 Phasor Diagram of Maxwell Inductance Bridge**

</center>

### Maxwell’s Inductance Capacitance Bridge
In this type of bridge, the unknown resistance is measured with the help of the standard variable capacitance. The connection diagram of the Maxwell Bridge is shown in the figure below.

<center> 

![circuit](images/circuit4.png)

**Fig. 4 Maxwell Inductance Capacitance Bridge**

</center>

For balance condition, 

<center>

$$(R1 + jωL_1) \left (\frac{R4}{1 + jωC_4R_4} \right ) = R2R3$$

</center>

<center>

$$R_1R_4 = jωL_1R_4 = R_2R_3 + jωC_4R_4R_2R_3$$

</center>

By separating the real and imaginary equation we get,

<center>

$$R_1 = \frac{R_2R_3}{R_4}$$

</center>

<center>

$$L_1 = R_2R_3C_4$$

</center>

The above equation shows that the bridges have two variables R<sub>4</sub> and C<sub>4</sub> which appear in one of the two equations and hence both the equations are independent. The circuit quality factor is expressed as 

<center>

$$Q = \frac{ωL_1}{R_1} = ωC_4R_4$$

</center>

The phasor diagram of Maxwell’s inductance capacitance bridge is shown in the figure below.

<center> 

![circuit](images/circuit5.jpg)

**Fig. 5 Phasor Diagram of Maxwell Inductance Capacitance Bridge**

</center>

### Advantages of the Maxwell’s Bridge:
The following are the advantages of the Maxwell bridge-

1. The balance equation of the circuit is free from frequency.
2. Both the balance equations are independent of each other.
3. Maxwell’s inductor capacitance bridge is used for the measurement of the high-range inductance.

### Disadvantages of the Maxwell’s Bridge:
The main disadvantages of the bridge are

1. The Maxwell inductor capacitance bridge requires a variable capacitor which is very expensive. Thus, sometimes the standard variable capacitor is used in the bridges.
2. The bridge is only used for the measurement of medium-quality coils.


</div>
