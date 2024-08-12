---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
{% include section.html background="images/petri2.jpg" dark=true %}

<p style="text-align: center;">PEEK INSIDE OUR LAB</p>

{% include section.html %}

{% capture content %}

{% include figure.html image="images/lab1-min.jpg" %}
{% include figure.html image="images/lab2-min.jpg" %}
{% include figure.html image="images/lab3-min.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

<p style="text-align: center;">PEEK INSIDE OUR LAB</p>

Roshawn Morgan, Undergraduate Assistant, 2023-2024
Jordan Perez, Honors Student, 2023-2024
Vanessa Lewis, UPN Student, Summer 2024
