---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<br>

3-D Converter-Level Packaging with TO-247 SiC Devices 
======
* Three-faced utilized heat sink for a 75 kVA grid interface bi-directional converter, providing a 35 % reduction in heat volume compared to a 2-D layout.
* Cylindrical holes for heat dissipation, facilitating cost-effective fabrication.

<img src="/images/heat_sink.jpg" width="800" height="400">

PCB Power Loop Layout Optimization for TO-247 SiC Devices
======
* Vertical power layout, a common approach to lower PCB parasitic inductance $$L_\text{PCB}$$ to limit voltage overshoot.
* However, PCB parasitic inductance $$<<$$ TO-247 lead inductance and PCB capacitance $$C_\text{PCB}$$ becomes the dominant factor impacting the switching transient.

<img src="/images/pcb1.jpg" width="800" height="400">  

* Small-signal models, incorporating $$C_\text{PCB}$$, for ringing frequency estimation.

<img src="/images/pcb2.jpg" width="800" height="400">  

Simplified Analytical Modeling of Reflected Wave Transients in Two-Level Motor Drives with Output Reactor
======
* Output reactor, the standard approach for reflected wave mitigation in cable-connected drives up to 300 ft. 
* However, for reflected wave estimation, the user has to resort to computationally expensive simulations.
* A lumped circuit model based on dominant pole approximation proposed with closed-form expressions for peak motor-side overvoltage and drive-side overcurrent, and slew-rates ($$\text{d}v/\text{d}t$$ and $$\text{d}i/\text{d}t$$).

<img src="/images/reactor.jpg" width="800" height="400">  

Two-Level Split-Phase Topology for Enhanced Reflected Wave Suppression in Two-Level Cable-Connected Drives
======
* Output reactor in Two-Level (2L) drives lowers the motor-side voltage's slew rate ($$\text{d}v/\text{d}t$$) with a slight reduction in overvoltage peaks.
* Two-Level Split-Phase (2L-SP), which has a similar structure to 2L, provides enhanced reflected wave suppression without the need for additional hardware or control due to its lower output $$\text{d}v/\text{d}t$$.
* Same power device count for both configurations if anti-parallel diode is used for 2L.

<img src="/images/rwp_2LSP.jpg" width="800" height="400">  

Evaluation of Common Mode (CM) Conducted EMI in Two-Level Split-Phase Topology
======
* Output reactor in Two-Level (2L) drives lowers the motor-side voltage's slew rate ($$\text{d}v/\text{d}t$$) with a slight reduction in overvoltage peaks.
* Two-Level Split-Phase (2L-SP), which has a similar structure to 2L, provides enhanced reflected wave suppression without the need for additional hardware or control due to its lower output $$\text{d}v/\text{d}t$$.
* Same power device count for both configurations if anti-parallel diode is used for 2L.

<img src="/images/rwp_2LSP.jpg" width="800" height="400">  

Non-Invasive Health Monitoring for DC-DC Converters
======
* Performance evaluation of Particle Swarm Optimization and Genetic Algorithms for Digital Twin (DT)-based health monitoring.
* Faster convergence with Genetic Algorithm.

<img src="/images/PSO_GA.jpg" width="800" height="400">

* Practical implementation of DT-based health monitoring for a four-phase interleaved converter of a 75 kVA grid-interface bidirectional converter.

<img src="/images/DT_health.jpg" width="800" height="400">

Integrated Magnetics for Interleaved Boost Converter
======
* Gapped E-core-based structure with decoupled Common Mode (CM) and Differential Mode (DM) inductances.

<img src="/images/e_core.jpg" width="800" height="400">

Partial Discharge Testing in Motors Fed by Voltage Source PWM Motor Drives
======
* Evaluation of PWM waveform characteristics on Partial Discharge Inception Voltage (PDIV) in twisted pairs at different pressures.
  
<img src="/images/PD.jpg" width="800" height="400">

Isolated Active Voltage Injection-Based MVDC Hybrid Circuit Breaker
======
* Hybrid Circuit Breaker (HCB), comprising an electro-mechanical switch (EMS) in series with Voltage Injector Building Block (VIBB).
* E-core-based integrated magnetic structure for injection.
* Miniscule post-fault interruption residual energy.

<img src="/images/MVDC_HCB.jpg" width="800" height="400">
