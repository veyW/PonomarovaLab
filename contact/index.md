---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We have several job openings (PhD candidates, research technicians, staff scientists). Please email your CV and a few lines about your goals and interests to oponomarova@salud.unm.edu

{%
  include button.html
  type="email"
  text="oponomarova@salud.unm.edu"
  link="oponomarova@salud.unm.edu"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/QsqcKtpkpfxzp9cf9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/ethan-wright-magoon.jpeg"
  caption="New Mexico, photo by Ethan Wright-Magoon"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="joonyeop-baek.jpg"
  caption="New Mexico, photo by Joonyeop Baek"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
