# Simple-555-Timer-Sponsored-by-JLCPCB

Thank you JLCPCB for sponsoring this project. Please order your PCB at https://jlcpcb.com/RAT

Hardware components

JLCPCB Customized PCB ×	1	

NE555 Timer through hole ×	1	

IC socket 8 pins 2.54mm through hole ×	1	

Male Header 40 Position 1 Row (0.1") ×	1	

Capacitor 10 nF ×	2	

0.25W 1000 Ohm Resistor ×	1

Hand tools and fabrication machines

Soldering iron (generic)	

Solder Wire, Lead Free

This project is about making a simple 555 Timer circuit with only 1 resistor and 2 capacitors. Use a ceramic capacitor for C2.

I would also like to thank the online community for sharing the schematic to build the circuit.

This project is one of the smallest customized 555 Timer PCB. It is 25.4cm by 25.4cm size.

Why do we want a 555 Timer instead of a microcontroller signal output?

A 555 Timer can provide up to about 14V output peak to peak signal. Whereas, a microcontroller usually can provide up to 5V peak to peak signal.

Please use a constant input voltage of between 5V and 15V for the NE555 Timer.

For example, R1 = 1k Ohms, C1 = 33nF. We will get frequency = 11.11 kHz, duty cycle = 67%.

With the help of an Arduino, you can use the Frequency meter .ino code to find out the frequency and duty cycle of a 555 Timer.

![image](https://user-images.githubusercontent.com/85741357/181509800-f2eb8a4f-1dbf-4dd9-b8f4-39c288a49d24.png)

R1 = 1k Ohms, C1 = 33nF, frequency = 11.11 kHz, duty cycle = 67%

I have yet to figure out the formula for calculating the frequency of the 555 Timer for this setup. Do let me know if you have the answer.

Tips: JLCPCB offers cheaper price for small PCBs of 10cm by 10cm. You can panelize your PCBs to less than or equal to the dimension.

Hope you enjoy this project. Once again, I would like to thank JLCPCB for sponsoring this project, and please order your PCBs at https://jlcpcb.com/RAT
