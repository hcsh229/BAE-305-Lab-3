# BAE-305-Lab-3
# Let’s Switch: Transistors as Switches
Group Members: Heath Shewmaker and Terence Redford

Submitted: 2/19/2025

# Introduction:
The aim of this lab was to dive into the capabilities of a circuit utilizing Diodes and transistors, specifically bipolar junction transistors (BJT). We compared the voltages across an LED of a “transistor as switch” circuit to a circuit using an actual sliding switch to visualize the semi-conductive capabilities of a transistor. We also controlled the current running through an LED and a motor using a BJT and a potentiometer. This lab served as additional practice for measuring voltage and current through circuit elements using the DMM, while also shedding light on the intricacies of real transistors and how they differ from the ideal transistor we have studied in class. 
# Methods: 
Step 1: The Resistances of each resistor were verified to ensure tighter accuracy when comparing the measured voltages and currents to the values calculated using Ohm’s law. The results of the measurements are tabulated with respect to the expected values below:

 ![image](https://github.com/user-attachments/assets/fde73ef1-815e-4695-84df-509f2d056c58)

 Table 1: Expected Resistance vs. Actual Resistance

Step 2: A circuit utilizing the 270-ohm resistor, an LED, and a sliding switch was constructed. We recorded the voltage with respect to ground at 4 test points with the switch both on and off, making sure to measure as close to the components as possible to negate any small voltage drops. We also measured the current through the LED with the switch both on and off. These values will be used and compared against the calculations composed from Ohm’s law, shown in the results section. Pictured below is the circuit: 

![image](https://github.com/user-attachments/assets/2ebef62b-bdf5-445e-9983-fe415e14c1d6)

Figure 1: Circuit utilizing a resistor, LED, and sliding switch.

Step 3: Next, we constructed a circuit which contained a sliding switch, a BJT, an LED, 270-ohm resistor, and 1k ohm resistor. We then measured the voltage with respect to ground at 7 test points, as well as the current through the LED and 1k ohm resistor, with the switch both on and off. These values will be used and compared against the calculations composed from Ohm’s law, shown in the results section. Pictured below is the circuit:

![image](https://github.com/user-attachments/assets/eae5fbc1-d369-44b9-85ae-7c34bea05a90) 

Figure 2: Circuit utilizing a switch, BJT, LED, and 2 resistors.


Step 4: A circuit using an LED, BJT, 270-ohm resistor, 1k ohm resistor, and potentiometer was then built. Voltages were measured at 6 test points with minimum voltage, peak voltage, and two midpoints. We found minimum and peak voltage by tuning the potentiometer until the voltage began to change, indicating a change in brightness. We also measured voltage across and current through circuit components at these 4 voltage levels. These were to be used to compare current in the base and collector, gain, and collector-emitter voltage to the varying input voltages. Pictured below is the circuit:

 ![image](https://github.com/user-attachments/assets/e3a4b280-0f83-4cf6-9b28-c7cf272212f8)

 Figure 3: Circuit utilizing an LED, BJT, 2 resistors, and a potentiometer.


Step 5: Next, we built a circuit with an electric motor, LED, BJT, 2.2k ohm resistor, 1k ohm resistor, and the potentiometer. We were supposed to take voltage measurements at 6 test points, once again at minimum voltage, peak voltage, and two midpoints. We also needed to measure the voltage across and current through the components at each voltage level. These were to be used to compare current in the base and collector, gain, and collector-emitter voltage to the varying input voltages. Pictured below is the circuit:

![image](https://github.com/user-attachments/assets/c815cb0c-4677-4771-b694-2f716144eeba)

Figure 4: Circuit utilizing an electric motor, LED, BJT, 2 resistors, and a potentiometer.


# Results: 

Step 2: In the first circuit we observed that the switch functioned as expected, as either a break in the circuit or simply as a wire. We also noticed that the LED dissipated approximately 1.93 V when paired in series with the 270 ohm resistor. This was something we noted because we knew it would be relevant in the next circuits, since the LED would be used with this resistor in each circuit. The measurements we obtained are displayed below in table 2:

![image](https://github.com/user-attachments/assets/53cad16f-8f60-4a26-ba0c-0d971fbe101e)

Table 2: Measurements of Circuit 1

We were able to find the current through the resistor with both the switch on and off, using Ohm’s law. 

 ![image](https://github.com/user-attachments/assets/2cf361f5-951d-4337-bac2-d87fd2092900)

 Figure 5: Current calculations for circuit 1.

Step 3: In the second circuit we Observed that when the switch was closed, allowing current to flow to the resistor and the Base terminal of the transistor, the potential difference over the 1 KiloOhm resistor was 4.36V. This confirmed that the transistor needed a potential difference of about 0.7V in order to allow current to pass through. This was expected because we have learned that these components are designed specifically to function most optimally at this voltage. The measurements we obtained that support this are given below in table 3.

![image](https://github.com/user-attachments/assets/23e8765f-4bd0-4d22-be3e-a47e0da0a58f)

Table 3: Measurements of curcuit 2.

 We calculated the current through each resistor, also using Ohm’s law.

 ![image](https://github.com/user-attachments/assets/72273891-4239-4bb0-ae97-7c549ad0f6e6)

 Figure 6: Current calculations for circuit 2.

Step 4: This circuit replaces the switch in the previous section with a potentiometer. By engaging with this circuit, we understood that the reason this was done was to showcase a particular nuance of the function of a transistor. By using the potentiometer to vary the resistance on the part of the circuit attached to the Base terminal of the transistor, we observed that not only could we switch the LED on and off, but there was a range of brightnesses we could adjust through by slowly modifying the potentiometers’ value. By doing this we tabulated the following values in table 4:

![image](https://github.com/user-attachments/assets/235d8f06-beba-4560-900e-39aef99c83ac)

Table 4: Circuit 3 measurements.

The values in this table demonstrate that even though the transistor is designed to function optimally at a potential difference of 0.7V, it can still partially allow current through at slightly lower voltages. This is due to the Saturation region, where if sufficient potential difference is present in the base terminal, it will partially allow the flow of current through the transistor, and as the potential difference approaches the maximum value of 0.7V, the current allowed through increases to the maximum. We see this trend illustrated in the data, where at  0.541V the transistor lets a minuscule amount of current flow (0.68 milliamps), which although small is still enough to allow the LED to have very dim glow, and at what appeared to us to be the minimum resistance for maximum brightness, the voltage is 0.648V, which is close to 0.7V

For the Motor Driving circuit, we did not have enough time to take measurements during the Lab period, due to time we used fixing mistakes on earlier circuits. However, we were able to observe a general trend. The trend we observed was that by adjusting the potentiometer, we could fine tune the speed of the motor as desired. We also noticed that there was a maximum and minimum value that was reached, even though the potentiometer was still able to change its resistance (lower or greater respectively). We came to the following conclusions about these observations:

1) The sudden stopping of the motor occurred when the resistance of the potentiometer was so large that it dissipated enough of the 5V source voltage, that the potential difference that reaches the transistor was not high enough to allow any current through the collector, which would cause no current to exit the emitter and thus completely cut the motor off.


2) Similarly, the maximum speed of the motor occurred when the potentiometer was at a sufficiently low value that the transistor had reached its full saturation, allowing all the current to pass through without any hinderance. Increasing the resistance any more would not influence the flow of current through the transistor, since it is already allowing all the current to pass through.

3) The ability to adjust the speed indicated that we were within the saturation range, where the transistor was allowing partial flow of current, but was still restricting how much could be transferred to the motor. Adjusting the potentiometer would allow us to slightly change the voltage input into the Base terminal, adjusting what percentage of current was allowed to flow into the collector and out the emitter.

# Discussion: 
Discussion Question 1: How does the current through the LED compare between circuits
1 and 2?
-	We used an ammeter in series with the LED to measure the current through it in each circuit. This revealed that with the switch on, both circuits ran about 13 milli-Amps through the LED, proving that a transistor can be used as a switch. This makes sense, since when the potential difference at the base terminal of the BJT is 0.7V, we could expect it to have no resistance to the current flowing from the collector, and thus it would simply act like a closed switch for that part of the circuit.


Discussion Question 2: The datasheet mentions a maximum voltage drop (VCE) of 1.2V at
saturation. We would like a much smaller value, such as the fraction of a volt that you
measured in the first circuit across the switch, S1, when it is on. How does your
measured VCE compare to the one listed in the datasheet? Do you think we are
operating this transistor in the saturation region?
-	We did measure a very small fraction of a volt for the drop across the transistor (Vce). Our reading was much much smaller than the maximum drop of 1.2V, leading us to believe that we were using this transistor in its saturation region. 

# Conclusion: 
Our aim in this lab was to learn about the unique properties of Bipolar Junction Transistors, and to use them in circuits as both switches, and then also as current restrictors. The main takeaway from this lab was that transistors are highly specialized components, and that one must be very careful and intentional in designing circuits around them, since they have very narrow ranges of optimal use, and cannot simply be put in any circuit the way one could add a resistor or similar component. We also reinforced our knowledge about 0.7V being the standard voltage drop for the Base terminal of  many common transistors. Finally, we experimented with the concept of the saturation region and broadened our intuition for non-idealized (real world) scenarios. We did so by using circuits where the resistances before the base terminal were variable, allowing us to tune the potential difference entering the base terminal. In doing this we discovered that transistors could act as current flow restrictors, and with fine tuning the saturation region can be used to our advantage to change the speed of motors or brightness of LEDs autonomously.
Another takeaway that we got from this lab related to learning how to wire circuits that are not simple linear designs. These circuits featured multiple locations where source voltages came from and involved more complex circuitry than we have typically wired before. From this we gained a new appreciation for the complexities of translating theoretical circuit designs into physical component wirings.
