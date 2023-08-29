---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are located in the Department of Biological Sciences \
2125 Derring Hall (Mail Code 0406) \
926 West Campus Drive \
Blacksburg, VA 24061 

{%
  include button.html
  type="email"
  text="asu [at] vt.edu.edu"
  
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Derring+Hall/@37.2270084,-80.4272244,15.55z/data=!4m6!3m5!1s0x884d95134febe121:0xdd03ef2d8f47eaf7!8m2!3d37.2291399!4d-80.4255126!16s%2Fg%2F11g6qt6vgv?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/unilogo.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/campus.jpeg"
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
