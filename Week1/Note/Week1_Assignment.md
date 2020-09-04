Week01- Pcomp

# Assignment 

##  [Electricity: The Basics](https://itp.nyu.edu/physicalcomputing/lessons/electricity-the-basics/) 

### definitions

**Electricity - electrical circuit**

​	a **power source** and **a components conver the energy** into other forms of energy

**Sensors**

​	convert other forms of energy into electrical energy

​	light bulbs, motors

**Electronics**

​	reading changes in electrical properties as information

**transduction** the process of changing one energy into another

**transducers** the devices do transduction

**Voltage** Volts

**Current** Amperes Amps

**Resistance** Ohms

**Direct Current(DC)**

​	All current flows one direction

**Alternating Current(AC)**

​	Current flow is reversed in a regular repeating cycle.

**Schematic diagrams**

[	Wikipedia page for “Electronic Symbol”](https://en.wikipedia.org/wiki/Electronic_symbol)

​	It’s arranged so that you can best understand the flow of the electricity. 

​	he power source is at the top, and the point of lowest energy, or **ground**, is at the bottom.  This diagram shows the flow of energy from the top of the diagram to the bottom.

![simple_circuit_schem2](https://itp.nyu.edu/physcomp/wp-content/uploads/simple_circuit_schem2.png)



### Components

**Conductors** 导体

**Insulators** 绝缘体

**Resistors** 电阻

![resistors_schem1](https://itp.nyu.edu/physcomp/wp-content/uploads/resistors_schem1.png)

<img src="/Users/yedianyang/Library/Application Support/typora-user-images/image-20200903232208729.png" alt="image-20200903232208729" style="zoom:40%;" />

**Capacitors** polarized & non-polarized

Clearn up the noise from the power supply

![capacitors_schem1](https://itp.nyu.edu/physcomp/wp-content/uploads/capacitors_schem1.png)

**Diodes** permit the flow of electricity in one direction

![diodes_schem](https://itp.nyu.edu/physcomp/wp-content/uploads/diodes_schem.png)

**Switches**

![switch_schem](https://itp.nyu.edu/physcomp/wp-content/uploads/switch_schem.png)

**transistors** 晶体管 and **relays** 继电器 

![transistor_relay_schem](https://itp.nyu.edu/physcomp/wp-content/uploads/transistor_relay_schem.png)



### Relationships

#### Ohm's Law

V = I*R

I = V/R

R = V/I



P = V*I

**Ground** is the place in a circuit with where the potential energy of the electrons is zero.

### Electrical Energy Flow in a Circuit

**Series**

![resistors_in_series-e1410098079494](https://itp.nyu.edu/physcomp/wp-content/uploads/resistors_in_series-e1410098079494.png)
$$
R_{total} = R_{1} + R_{2} + R_{3} + ···
$$
**Parallel**



![resistors_in_parallel-e1410098143792](https://itp.nyu.edu/physcomp/wp-content/uploads/resistors_in_parallel-e1410098143792.png)
$$
1/R_{total} = 1/R_{1} + 1/R_{2} + 1/R_{3} + ···
$$


## [Understanding DC Power Supplies](https://itp.nyu.edu/physicalcomputing/lessons/understanding-dc-power-supplies/)

The most common operating voltages for microcontrollers and digital processors are 5V and 3.3V.

Most common use spec. (**12V, 1000mA**)

![power_supply_polarity_011](https://itp.nyu.edu/physcomp/wp-content/uploads/power_supply_polarity_011.jpg)

<center>Symbol for a center-positive power supply.</center>

![power_supply_polarity_021](https://itp.nyu.edu/physcomp/wp-content/uploads/power_supply_polarity_021.jpg)

<center>Symbol for a center-negative power supply</center>



If the voltage showing on your multimeter is more than half a volt or a volt off its rating, then you most likely have what is called an unregulated power supply. The 12V Jameco power supply we used in this example is a regulated one, so that is why the voltage we received was so close to the voltage it was rated for.