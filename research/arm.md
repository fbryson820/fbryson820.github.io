---
layout: page
title: "Solid Sampling Arm for ROV/AUVs"
---

The sampling of solids around ocean interfaces could answer key questions in the characterization of ocean worlds and assessing their habitability and requires further development of technology. The Planetary Habitability and Technology Lab's ROV/AUV [Icefin](https://schmidt.astro.cornell.edu/icefin/) provides a platform to test this technology in under-ice environments.

To this end, a manipulator arm has been developed to recover sediment samples from a lightweight ROV/AUV. The arm is controllable by a custom GUI and a Teensy 3.2, which is a microcontroller that has heritage in sensor networks with Icefin. It collects sediment cores using an adapted sediment core catcher as the end effector.

The arm is currently being tested in the lab with various types of sediment for characterization before testing with Icefin's interface.

---

<div>
<h3 class="fw-bold border-bottom pb-3 mb-5">Publications and Presentations</h3>
  {% for item in site.data.publications.arm %}
    <p><a href="{{ item.url }}">{{ item.name }}</a></p>
  {% endfor %}
  {% for item in site.data.presentations.arm %}
    <p><a>{{ item.name }}</a></p>
  {% endfor %}
</div>
---

Planetary Habitability and Technology Lab, PI Dr. Britney Schmidt