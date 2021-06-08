---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the Computer and Information Science and Engineering Department at the University of Florida.
We are located on the 5th floor of the CSE building.

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

That St & The Other St  
Porters Lake, NS B3E 1H3  
Canada
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="The Center for Wit and Sagacity"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Department of Metaphor"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
