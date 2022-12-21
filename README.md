# Diy-Led-Chaser

![Screenshot (703)](https://user-images.githubusercontent.com/118633170/208941971-5877f40c-daac-4350-bd13-674c80d1e03c.png)


If you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com/RNA) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors

[JLCPCB](https://jlcpcb.com/RNA)


Please use the following link to register an account in [JLCPCB](https://jlcpcb.com/RNA)

https://jlcpcb.com/RNA


Pcb Manufacturing

----------

2 layers

4 layers

6 layers

jlcpcb.com/RNA


PCBA Services

[JLCPCB](https://jlcpcb.com/RNA) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com/RNA), giving you peace-of-mind that you won't run into any last minute part shortages. jlcpcb.com/RNA



3d printing

-------------------

SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes [JLCPCB](https://jlcpcb.com/RNA) better companion among other manufactures try out [JLCPCB](https://jlcpcb.com/RNA) 3D Printing servies

[JLCPCB](https://jlcpcb.com/RNA) 3D Printing starts at $1 &Get $54 Coupons for new users

![Screenshot (705)](https://user-images.githubusercontent.com/118633170/208942019-c93b058b-2930-46db-a203-8adb8aa00f0b.png)
![Screenshot (704)](https://user-images.githubusercontent.com/118633170/208942043-f404ab0d-111d-4165-8e76-a8ae3fc66efb.png)

6 channel LED chaser is based on LED flashing, If you want to build a 6 LED Chaser circuit we suggest this circuit first. It uses popular IC is a simple and affordable IC-4017 decade counter and IC-555. When we power the circuit, LEDs start glowing one by one for a defined time period. Means first LED Q1 glows and then Q2 glows and Q1 turned OFF and then Q3 glows and Q2 turned OFF and so on. When we change resistance of variable resistor then speed of LED's increase. Because frequency of 555 timer increases and this increases frequency signal is directly connected to counter's trigger pin

This is the circuit of a simple LED chaser. The LEDs lights one by one for a period of 1second and the cycle repeats giving the running light appearance. The circuit uses two ICs (one is 555) to drive the LEDs.



IC1 (NE555) is the popular timer IC wired in the Astable Multivibrator mode. Resistors R1, VR1 and capacitor C1 act as the timing components and the output pulses are available from the output pin 3 of IC1. These pulses are given to the input pin 14 of the Johnson decade counter IC CD4017. Out of the 10 outputs of IC2, eight outputs are used to drive the LEDs. The ninth output pin 9 is connected to the reset pin 15 to stop the counting. So that the cycle repeats. With the value of C1, each LED remains on for 1second. When one LED turns off, the second on turns on. This cycle repeats giving the running light appearance. Resistor R3 keeps the input pin 14 of IC2 low after each pulse.VR1 adjusts the speed of LED chasing.

Meanwhile, the working operation of this circuit is simple and adorable. Here, we have likewise employed a 555 timer IC in Astable mode for creating a trigger pulse for a short time span. Henceforth, a variable resistor is associated with changing the cycle frequency of the 555 timer yield. However, a CD4017 counter IC is additionally related to this circuit to give the LEDs a lighting effect.

Also, the ten red LEDs are further associated with Q0-Q9 (pin 3) through a 150-ohm resistor. MR (pin 15), and 555 timer pin (pin 13) are legitimately associated with ground and likewise, the output pin of the counter is straightforwardly associated with the yield pin of 555 Timer. Thus, the circuit gives a blinking effect in a sequential manner. You can likewise change the speed of LEDs with the help of a 10k Pot.

This circuit can likewise be used in many applications from home decoration to security alarms. Meanwhile, the most popular application of LED Chaser circuits is deployed in advertising displays, running light ropes, and in small discos. Additional applications are in Knight riders, decoration of home, shops, and likewise parties and occasional lightings.

![Screenshot (708)](https://user-images.githubusercontent.com/118633170/208942324-9f4348ea-6378-47a4-b29b-aa02a0eca50d.png)
![Screenshot (709)](https://user-images.githubusercontent.com/118633170/208942336-4fc3c59d-ec64-4a25-8ddf-34441408e957.png)


To make this simple LED chaser circuit I have used a 555 timer & 4017 IC. Here the 555 timer IC will generate the clock pulse for CD4017 IC. Then 4017 IC will blink the LEDs in sequence as per the signal in the clock pin (14).

I have used a 5V DC supply, but you can also use the 12V DC supply (no changes required for 12V).



An LED chaser or sequencer is a popular LED driving circuit. It’s used in running-light rope displays to flash different lighting patterns. In a chaser or sequencer circuit, a controller commands the sequence and timing of the flashing LEDs to illuminate different kinds of lighting patterns. 

This LED chaser is built on Arduino UNO. Arduino is currently the most popular single-board microcontroller. In this sequencer, seven LEDs are interfaced with Arduino to demonstrate 13 different lighting patterns. 

In fact, it’s possible to design an LED chaser with several LEDs by using shift registers. In this LED chaser, LEDs are directly interfaced to Arduino pins since Arduino’s GPIO can output forward voltage and the current required to switch them ON/OFF.

The LEDs are controlled via the digital output from Arduino. The UNO is programmed to output logical signals with different sequence over its pins with the appropriate timing pattern to show different LED light patterns. 

ght Emitting Diodes (LEDs) are semiconductor diodes that emit light in a forward bias condition. These diodes are similar to signal diodes that are in functioning. 

![Screenshot (710)](https://user-images.githubusercontent.com/118633170/208942356-3d307557-c380-4de7-b0fe-8efad6c61414.png)
![Screenshot (711)](https://user-images.githubusercontent.com/118633170/208942362-618d0969-29ee-4915-8640-9c1c544c7e94.png)


LEDs are distinguished by the range of wavelengths they emit. According to the bandwidth of light that’s emitted, they require different forward voltage to bias. The forward operating voltage for most of the LEDs varies from 1.2 to 3.6V, depending on their color. 

Much like signal diodes, LEDs are also current-controlled devices and require between 12 to 30 mA for maximum illumination. For normal illumination, LEDs typically draw 5 mA of current. 

Arduino’s GPIO can source or sink up to 40 mA of current. The voltage output of Arduino’s digital I/O channels is 5 and 3.3V for logical HIGH on 5 and 3.3V boards. The voltage level for logical LOW is 0V on both types of boards. The pins can sink the same voltage levels when configured as the input. So, LEDs can be directly driven by the Arduino’s I/O channels. 

LEDs are two-terminal devices. This means they can be interfaced in a circuit in two ways. In one way, a device (such as Arduino’s channel) sources current to the LED. In this method of interfacing, the cathode of the LED is connected to the ground while the anode is connected to the current source. 

In the second method, the device sinks current through the LED. In this method of interfacing, the anode of the LED is connected to the DC power supply rail and the cathode is connected to the current sink. 

However, there must be a series resistor connected with the LED in both cases to protect the LED from overcurrent. 

![Screenshot (712)](https://user-images.githubusercontent.com/118633170/208942415-9b69704f-41f9-4f74-b178-4ac3aaef425d.png)


When the forward current is sourced or sinks through the LED, it switches ON and starts glowing. The forward current flows through the LED when it’s set to forward biased by applying the appropriate voltage. When the forward voltage is dropped or the reverse voltage is applied to an LED, it switches OFF and stops glowing. 

When the forward current is sourced or sinks through the LED, it switches ON and starts glowing. The forward current flows through the LED when it’s set to forward biased by applying the appropriate voltage. When the forward voltage is dropped or the reverse voltage is applied to an LED, it switches OFF and stops glowing. 

In this circuit, seven LEDs are connected to Arduino UNO’s 0, 1, 2, 3, 5, 6, and 7 channels so that the pins must sink current through the LEDs. The red color LEDs are used in the circuit that requires a forward operating voltage of between 1.6 to 2V. 

Resistors of 330 ohms are also connected to each LED in the series. With this value of a series resistor at each pin, Arduino’s channels must sink 9 to 11 mA of current when the LEDs are forward biased.

![Screenshot (707)](https://user-images.githubusercontent.com/118633170/208942303-6ad87748-a819-4a5e-8242-fceaa9506216.png)


Remember, the chaser or sequencer is an LED driver circuit that operates LEDs based on a predetermined sequence and timing schedule. In this LED driver circuit, the controller (Arduino UNO) is programmed to flash 13 different lighting patterns. In the first lighting pattern, the LEDs are switched ON one after the other (from left to right) and then switched OFF one after the other (also from left to right). 

A delay of 300 milliseconds is used when illuminating each LED and a delay of 200 milliseconds is used when switching them OFF. 

![Screenshot (718)](https://user-images.githubusercontent.com/118633170/208942388-76f8870b-cd20-4d1e-945a-74e5f7141133.png)
