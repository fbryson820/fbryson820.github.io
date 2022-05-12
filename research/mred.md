---
layout: page
title: "Miniature Robotic Electrodialysis (MR ED)"
---

Astrobiological missions that investigate ocean worlds could encounter high salinity brines. To address complications with salts, we are developing a miniature robotic electrodialysis system to desalt samples with dissolved organic molecule recovery. 

To this end, the Miniature Robotic Electrodialysis (MR ED) system has been developed and tested with a number of natural samples, including brines. It has an average dissolved organic carbon recovery of 71% with non-brine samples, and successfully desalted NaCl brines from South Bay Salt Works with 77% DOC recovery.

MR ED has so far been developed on the benchtop, but future work includes integrating the pump control (which circulates sample and concentrate at a high flow rate to increase desalting efficiency), power control with the existing Raspberry Pi-based sensing framework to create a self-contained, autonomous instrument.


<img src="/assets/img/mred.jpg" alt="Model of MR ED" width="300"/>

---

<div>
<h3 class="fw-bold border-bottom pb-3 mb-5">Publications and Presentations</h3>
  {% for item in site.data.publications.mred %}
    <p><a>{{ item.name }}</a></p>
  {% endfor %}
  {% for item in site.data.presentations.mred %}
    <p><a>{{ item.name }}</a></p>
  {% endfor %}
</div>

---
Planetary Habitability and Technology Lab, PI Dr. Britney Schmidt
