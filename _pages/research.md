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
<br>

3-D Converter-Level Packaging with TO-247 Package SiC Devices 
======
* Three-faced utilized heat sink for 75 kVA grid interface bi-directional converter, providing 35 % reduction in heat volume than 2-D layout.
* Cylindrical holes for heat dissipation, facilitating cost-effective fabrication.

<img src="/images/heat_sink1.jpg" width="450" height="400">   <img src="/images/heat_sink2.jpg" width="450" height="400">

PCB Power Loop Layout Optimization for TO-247 SiC Devices
======
* Vertical power layout, a common approach to lower PCB parasitic inductance $$L_\text{PCB}$$ to limit voltage overshoot.
* However, PCB parasitic inductance << TO-247 lead indutance &rarr; PCB capacitance $$C_\text{PCB}$$ becomes the dominant factor imapcting the switching transient.

<img src="/images/pcb1.jpg" width="800" height="400">  

* Small-signal models, incorporating $$C_\text{PCB}$$, for ringing frequency estimation.

<img src="/images/pcb2.jpg" width="800" height="400">  
