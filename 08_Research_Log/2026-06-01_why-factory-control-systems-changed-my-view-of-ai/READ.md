# Why Factory Control Systems Changed My View of AI

About three months have passed since I started working at a Broadcom-related FC-BGA substrate manufacturing site.

During this period, I observed the installation, setup, wiring, and power-on testing of conveyor systems. To be honest, however, I understood very little about control panels themselves. To me, a control panel was simply a large box filled with circuit breakers and cables.

There was, however, one question that continued to bother me.

Why does each machine require such a large control panel?

Why does each manufacturer's equipment have its own separate control panel?

Why can't an entire factory be operated through a single control panel?

Today, I finally understood the reason, and I want to record that realization here.

A control panel is not merely a power distribution box.

Each piece of equipment contains its own PLC, I/O modules, and communication devices, operating as an independent control system. At the same time, these systems are connected to one another through a network.

Until now, I had viewed conveyors simply as machines. In reality, however, a conveyor is an information system controlled through sensors, PLCs, I/O modules, and communication networks.

What impressed me most was the blue LAN cable connected to the lower section of the control panel.

Until today, I had regarded it as nothing more than a communication cable. In reality, it formed part of the factory's nervous system, connecting PLCs to one another and linking them to higher-level systems.

Motors move individual machines.

Information coordinates the movement of the factory as a whole.

This realization also affected my understanding of AI.

Previously, I viewed AI primarily as a matter of software and GPUs.

However, the more I observed the FC-BGA manufacturing environment, the more I began to see AI as part of a much larger industrial system.

Data centers run on electricity.

GPUs consume electricity.

FC-BGA substrates support GPUs.

And FC-BGA factories themselves are operated through PLCs and control systems.

Electricity generated at power plants passes through substations, factories, control panels, and PLCs before ultimately becoming AI computing capability.

Today, by understanding the structure of a control panel, I finally understood the answer to a question I had carried for nearly three months.

An AI manufacturing site is not merely a collection of machines.

It is a vast network of interconnected control systems.

---

# Learning Notes

Through discussions with IHI engineers, I gained a basic understanding of the structure of a factory control panel.

## Control Panel Components

* Power Supply Unit
* PLC
* I/O Modules
* Network Hub

## PLC

A PLC (Programmable Logic Controller) controls industrial equipment.

It receives signals from sensors and sends commands to motors and actuators.

In many ways, it functions as the "brain" of the equipment.

## I/O Modules

I/O (Input / Output) modules act as the interface between the PLC and field devices.

**Input**

* Sensors
* Switches

**Output**

* Motors
* Relays

These modules function as the "nervous system" of the equipment.

## Hub

The blue LAN cables at the bottom of the control panel were connected to a network hub.

The hub forms part of the factory communication network, linking PLCs and higher-level systems.

## PLC Power Supply

PLCs typically operate on 24VDC internally.

However, the electrical power supplied by the factory is usually:

* 230VAC
* 415VAC (three-phase)

Therefore, power conversion takes place inside the control panel.

Factory Power
↓
Power Supply Unit
↓
24VDC
↓
PLC
