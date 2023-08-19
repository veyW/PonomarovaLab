---
title: Team
nav:
  order: 3
  tooltip: About our team
---

 {% include icon.html icon="fa-solid fa-users" %}Team
[]: # Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
[]: # incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
[]: # nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/petri2.jpg" dark=true %}

<p style="text-align: center;">PEEK INSIDE OUR LAB</p>

{% include section.html %}

{% capture content %}

{% include figure.html image="images/lab1.jpg" %}
{% include figure.html image="images/lab2.jpg" %}
{% include figure.html image="images/lab3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
