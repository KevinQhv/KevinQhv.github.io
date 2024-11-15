---
title: "Publications"
date: 2024-01-05T17:54:41+02:00
draft: false
tags: [Publication, Conference, Poster]
summary: "This section presents the different presentations of my work"
---

## International Conferences

* **DSD 2024** - [*Exploring Fault Injection Attacks on CVA6 PMP Configuration Flow*](https://hal.science/hal-04683083v1/file/2024_DSD_Exploring_Fault_Injection_Attacks_on_CVA6_PMPConfiguration_Flow.pdf)

-***Abstract***-

<p align="justify">
Fault Injection Attacks (FIA) pose significant threats to the security and reliability of embedded systems.
FIAs can be used to target an embedded processor by manipulating its clock signal, power supply or by using electromagnetic pulses.
In this study, we analyze FIA on the Physical Memory Protection (PMP) configuration flow of a CVA6 RISC-V core. 
Fault injection campaigns targeting an FPGA implementation on an ARTY A7-100T board are performed to characterize the fault effects.
For that purpose, we rely on clock glitches. Moreover, in order to further characterize the induced faults, Error-Correction Code (ECC) is considered. 
We extend the ID pipeline stage with hardware modules to filter faults using Hamming code.
Experimental results demonstrate that FIA has multiple effects on the PMP configuration registers.
By classifying these effects in regards with injection parameters, we highlight that a given effect can be obtained with high probability by an attacker. 
Furthermore, thanks to integrated ECC modules used as filters, we confirm that single bit-flips is a prevalent effect in our experiments. 
Particularly, results demonstrate that numerous fault effects observed in the PMP configuration registers are caused by single bit-flips in the ID stage of the CVA6 core.
</p>

## National Conferences

- 

## Posters

* **JAIF 2024** -  [*Characterizing Clock Glitching Attacks on CVA6 PMP Configuration Flow*](https://hal.science/hal-04729593/document)

-***Abstract***-

<p align="justify">
Fault-Injection Attacks (FIA)[1] pose significant threats to the security and reliability of embedded systems. 
Nashimoto et al.[2] have illustrated the possibility to modify the Physical Memory Protection (PMP) configuration registers on a RISC-V processor through FIA using clock glitching. 
However, their study did not delve into the consequences of faults on these PMP configuration registers. 
Thus, in this study, we investigate the effects of clock glitching on the PMP configuration flow of a CVA6 RISC-V core.
</p>

