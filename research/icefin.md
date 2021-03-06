---
layout: page
title: "Icefin"
---
<img src="/assets/img/icefin.jpg" alt="Model of the Icefin vehicle" width="700"/>

---

Planetary Habitability and Technology Lab, Dr. Britney Schmidt

[schmidt.astro.cornell.edu/icefin/](https://schmidt.astro.cornell.edu/icefin/)

---

Icefin is a hybrid remote or autonomous underwater vehicle (ROV/AUV). It is designed to be modular and field portable for deployments primarily in the under-ice ocean. It uses a sensing suite, including oceanographic sensors and sonar, to explore the ice and water conditions around ice shelves.

Frances has been a member of the Icefin team since 2018, and has worked on the electrical and mechanical systems as well as an internal integrated sensing system. She completed a field season in Antarctica with Icefin in 2018.

Icefin was developed first as a prototype under PI Schmidt’s startup funds in the College of Science at Georgia Tech, and is now located at Cornell University. Since 2016, Icefin has been fully developed by the Planetary Habitability and Technology team.

---

<div>
<h3 class="fw-bold border-bottom pb-3 mb-5">Publications and Presentations</h3>
  {% for item in site.data.publications.icefin %}
    <p><a href="{{ item.url }}">{{ item.name }}</a></p>
  {% endfor %}
  {% for item in site.data.presentations.icefin %}
    <p><a>{{ item.name }}</a></p>
  {% endfor %}
</div>