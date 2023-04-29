# Seatbelt-Alarm-System
LED Alarm System for seatbelts in vehicles.


Driving without fastening the seat belt was one of the most common traffic offenses in India. With 6,175 charges laid in the first six months, Young drivers were the least likely to buckle up their seat belt. In the year 2011 a survey conducted, it was found that 55% university students did not consistently wear a seat belt.I decided to work on this project that ensures that the driver wears his or her seatbelt at all times. To do so,I decided to make an LED Alarm for the safety of the driver and passengers in a vehicle. The LED lights up when the driver is not wearing the seatbelt thereby prompting him/her to do so.


Technology stack:


Tinkercad: used for designing the circuit 

Circuit Diagram software: used for designing the circuit diagram


OVERVIEW AND WORKING


The LED alarm system uses logic gates and a switch for alarming the driver in times of need. 
The following ICs have been used used to design the circuit for the same:

IC-7404(NOT)
IC-7408(AND)
IC-7432(OR)

The LED lights up whenever the Door(C) is open or the seatbelt(A) is taken off by the driver. 

The inverter(NOT) inverts the logical output for the seatbelt(A).
Logic ‘0’ for the vehicle door indicates that it is closed whereas logic ‘1’ indicates that the door is open.

The key(B) is also monitored for ignition state and state of rest and a possible combination of the key and the door is used to record the output using the truth table and TTL logic.

The switch enables and disables inputs for three different paths in order to record the expected output.

A and B are provided as inputs to the AND gate.The output of the AND gate and C serves as inputs for the OR gate.

The output of the OR gate is used to determine the state of the LED. 





The circuit has been implemented using Tinkercad software.
The LED glows when C is set to logic one i.e. when the door is open.
