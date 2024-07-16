Adder Analysis in VLSI Using Xilinx Vivado
This repository contains the implementation and analysis of various adder architectures in VLSI using Xilinx Vivado design software. The goal of this project is to compare different adder topologies based on parameters such as on-chip power consumption and delay, and to determine the most efficient adder for different applications.

Project Description
In this project, we have implemented and analyzed the following adder architectures:

Carry Skip Adder (CSkA)
Carry Select Adder (CSlA)
Carry Lookahead Adder (CLA)
Kogge Stone Adder (KSA)
Brent Kung Adder (BKA)
The analysis focuses on three main parameters:

Utilization (in terms of LUTs and IOs)
On-chip power consumption (in watts)
Data path delay (in nanoseconds)
Key Findings
Brent Kung Adder (BKA) has the minimum on-chip power consumption and minimum data path delay, making it the most energy-efficient adder.
Carry Skip Adder (CSkA) consumes the maximum on-chip power.
Kogge Stone Adder (KSA) has the maximum data path delay.
Carry Skip Adder (CSkA) is suitable for low power applications despite its higher power consumption compared to others.
Comparison Table
S.No	Adder Types	Utilization (%)	On-chip Power (W)	Delay (ns)
LUTs	IOs	
1	Carry Skip Adder	4	14	2.944
2	Carry Select Adder	1	14	2.61
3	Carry Lookahead Adder	1	14	2.709
4	Kogge Stone Adder	1	14	2.675
5	Brent Kung Adder	1	14	2.598
