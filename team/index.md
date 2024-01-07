---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

This is us...

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: technician" %}

{% include section.html background="images/background.jpg" dark=true %}

what to write here?
{% include section.html %}

{% capture content %}

{% include figure.html image="images/CBweb.jpg" %}
{% include figure.html image="images/Phoebe.jpg" %}
{% include figure.html image="images/Sulagna2.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
