---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the Computer and Information Science and Engineering Department at the University of Florida.

{%
  include link.html
  type="email"
  icon=""
  text="kgraim@ufl.edu"
  tooltip=""
  link="kgraim@ufl.edu"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Department+of+Computer+and+Information+Science+and+Engineering/@29.6520985,-82.354201,15.23z/data=!4m5!3m4!1s0x0:0xd21b17bc0529867e!8m2!3d29.6483268!4d-82.3440276"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address
432 Newell Dr 
Gainesville, FL 32611
USA
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/UF_Campus_FriesSculpture.jpeg"
  caption="CISE Department"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/UF_CenturyTower.jpeg"
  caption="University of Florida"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}



{% capture col2 %}
{%
  include figure.html
  image="images/UF_Campus_FriesSculpture.jpeg"
  caption="CISE Department"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/UF_CenturyTower.jpeg"
  caption="University of Florida"
%}
{% endcapture %}
{% capture col3 %}
{%
  include figure.html
  image="images/GatorGlobe.jpeg"
  caption="University of Florida"
%}
{% endcapture %}
{% include three-col.html col1=col1 col2=col2 col3=col3 %}
