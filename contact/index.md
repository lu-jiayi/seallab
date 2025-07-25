---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{%
  include button.html
  type="email"
  text="Email Jiayi"
  link="jlg363@alumni.stanford.edu"
%}

{%
  include button.html
  type="address"
  tooltip="The location of Northwestern Department of Linguistics on Google Maps"
  link="https://www.google.com/maps/place/2016+Sheridan+Rd,+2016+Sheridan+Rd,+Evanston,+IL+60208/@42.0541328,-87.6776211,17.75z/data=!4m6!3m5!1s0x880fd075548138e1:0x6d1360409fb1196c!8m2!3d42.0544676!4d-87.6776634!16s%2Fg%2F1thx96l5?entry=ttu&g_ep=EgoyMDI1MDcyMi4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
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
